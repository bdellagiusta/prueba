<template>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.11.2/css/all.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css"/>
  <div class="hello">
    <div class="banner">¿Qué mirás, bobo?</div>
    

    <div v-on:click="isHidden = !isHidden">
      <div v-if="isHidden">
        <img class="img" src="../assets/filmin.webp" width="300" height="150"/>
      </div>
      <div v-if="!isHidden">
        <img class="img" src="../assets/lcdl.png" width="300" height="150"/>

        </div>
      </div>
    <div id="hello" v-if="isHidden">
        <a :href='randomElementFilmin.url'>
        <p class="title" >{{randomElementFilmin.name}}</p></a>
        <p class="year">{{randomElementFilmin.year}}</p>
        <button class="botton" @click="reloadPage"><i class="fa fa-refresh" aria-hidden="true"></i>
          Refresh</button>
     </div>
     <div id="hello" v-if="!isHidden">
      <a :href='randomElementCantina.url'>
      <p class="title" >{{randomElementCantina.name}}</p></a>
      <p class="year">{{randomElementCantina.year}}</p>
      <button class="botton"  @click="reloadPage"><i class="fa fa-refresh" aria-hidden="true"></i>
        Refresh</button>
        
   </div>
    </div>



    <footer>
      <div class="footer-container">
        <div class="left-col">
          <img src="logo.png" alt="" class="logo">
          <div class="social-media">
            <a href="https://www.facebook.com/profile.php?id=100006733605951"><i class="fab fa-facebook-f"></i></a>
            <a href="https://twitter.com/iamcoffeeboy0"><i class="fab fa-twitter"></i></a>
            <a href="https://www.instagram.com/iamcoffeeboy0/"><i class="fab fa-instagram"></i></a>
          </div>
          <p class="rights-text">© 2022 Created by <b>@iamcoffeeboy0</b>  </p>
          <p class="rights-text">All Rights Reserved.</p>  
        </div>
      </div>
    </footer>
</template>

<script>
export default {
  name: 'HelloWorld',
  setup (){
    return
  },
  methods: {
    reloadPage() {
      window.location.reload();
    }
  },
data() {
    return {
      isHidden: true,
      cantina:[
  {
    name: "Memento Mori",
    year: 1999,
    url: "https://boxd.it/v2c"
  },
  {
    name: "Veteran",
    year: 2015,
    url: "https://boxd.it/bCEO"
  },
  {
    name: "Unstoppable",
    year: 2018,
    url: "https://boxd.it/kiCc"
  },
  {
    name: "Thread of Lies",
    year: 2014,
    url: "https://boxd.it/7B9i"
  },
  {
    name: "The Vanished",
    year: 2018,
    url: "https://boxd.it/iqEQ"
  },
  {
    name: "The Negotiation",
    year: 2018,
    url: "https://boxd.it/jNZ0"
  },
  {
    name: "Sinkhole",
    year: 2021,
    url: "https://boxd.it/n4EO"
  },
  {
    name: "Silmido",
    year: 2003,
    url: "https://boxd.it/1ELs"
  },
  {
    name: "Perfect Number",
    year: 2012,
    url: "https://boxd.it/4sc2"
  },
  {
    name: "Over the Rainbow",
    year: 2002,
    url: "https://boxd.it/62jg"
  },
  {
    name: "Once in a Summer",
    year: 2006,
    url: "https://boxd.it/1uO2"
  },
  {
    name: "Old Days",
    year: 2016,
    url: "https://boxd.it/f89u"
  },
  {
    name: "Night and Day",
    year: 2008,
    url: "https://boxd.it/lGG"
  },
  {
    name: "My Way",
    year: 2011,
    url: "https://boxd.it/3heY"
  },
  {
    name: "Montage",
    year: 2013,
    url: "https://boxd.it/5SR8"
  },
  {
    name: "may-18",
    year: 2007,
    url: "https://boxd.it/lbo"
  },
  {
    name: "Mandala",
    year: 1981,
    url: "https://boxd.it/7xMU"
  },
  {
    name: "Love at the End of the World",
    year: 2015,
    url: "https://boxd.it/cQ8O"
  },
  {
    name: "Lost in the Mountains",
    year: 2009,
    url: "https://boxd.it/6AGy"
  },
  {
    name: "Like You Know It All",
    year: 2009,
    url: "https://boxd.it/33A2"
  },
  {
    name: "Kingmaker",
    year: 2022,
    url: "https://boxd.it/l430"
  },
  {
    name: "Keys to the Heart",
    year: 2018,
    url: "https://boxd.it/fA72"
  },
  {
    name: "Introduction",
    year: 2021,
    url: "https://boxd.it/tWbo"
  },
  {
    name: "Hello Brother",
    year: 2005,
    url: "https://boxd.it/4YzW"
  },
  {
    name: "Gyeongju",
    year: 2014,
    url: "https://boxd.it/8eOu"
  },
  {
    name: "Dooman River",
    year: 2010,
    url: "https://boxd.it/32ek"
  },
  {
    name: "Deliver Us from Evil",
    year: 2020,
    url: "https://boxd.it/lnfO"
  },
  {
    name: "Crocodile",
    year: 1996,
    url: "https://boxd.it/1voa"
  },
  {
    name: "Cold Eyes",
    year: 2013,
    url: "https://boxd.it/68Ai"
  },
  {
    name: "Eungyo",
    year: 2012,
    url: "https://boxd.it/3VZq"
  },
  {
    name: "Your Name.",
    year: 2016,
    url: "https://boxd.it/cUqs"
  },
  {
    name: "A Family",
    year: 2020,
    url: "https://boxd.it/rCMg"
  },
  {
    name: "Under the Open Sky",
    year: 2020,
    url: "https://boxd.it/rk3i"
  },
  {
    name: "Tokyo Family",
    year: 2013,
    url: "https://boxd.it/5Gwi"
  },
  {
    name: "The Pornographers",
    year: 1966,
    url: "https://boxd.it/Wco"
  },
  {
    name: "The Life of Oharu",
    year: 1952,
    url: "https://boxd.it/UFy"
  },
  {
    name: "The Kirishima Thing",
    year: 2012,
    url: "https://boxd.it/5nry"
  },
  {
    name: "The Insect Woman",
    year: 1963,
    url: "https://boxd.it/VAE"
  },
  {
    name: "The Idiot",
    year: 1951,
    url: "https://boxd.it/1x0O"
  },
  {
    name: "The Human Condition III: A Soldier's Prayer",
    year: 1961,
    url: "https://boxd.it/1dIQ"
  },
  {
    name: "The Human Condition II: Road to Eternity",
    year: 1959,
    url: "https://boxd.it/1dJa"
  },
  {
    name: "The Human Condition I: No Greater Love",
    year: 1959,
    url: "https://boxd.it/1jAy"
  },
  {
    name: "The Flavor of Green Tea Over Rice",
    year: 1952,
    url: "https://boxd.it/spi"
  },
  {
    name: "The Face of Jizo",
    year: 2004,
    url: "https://boxd.it/3Esa"
  },
  {
    name: "Bumpkin Soup",
    year: 1985,
    url: "https://boxd.it/15K"
  },
  {
    name: "The Discarnates",
    year: 1988,
    url: "https://boxd.it/4duK"
  },
  {
    name: "The Crucified Lovers",
    year: 1954,
    url: "https://boxd.it/1bMw"
  },
  {
    name: "The Cherry Orchard",
    year: 1990,
    url: "https://boxd.it/3tKs"
  },
  {
    name: "The Burmese Harp",
    year: 1956,
    url: "https://boxd.it/1fKa"
  },
  {
    name: "The Bird People in China",
    year: 1998,
    url: "https://boxd.it/1p9o"
  },
  {
    name: "Sympathy for the Underdog",
    year: 1971,
    url: "https://boxd.it/3bHK"
  },
  {
    name: "Swing Girls",
    year: 2004,
    url: "https://boxd.it/1ag0"
  },
  {
    name: "Sway",
    year: 2006,
    url: "https://boxd.it/OGg"
  },
  {
    name: "Swallowtail Butterfly",
    year: 1996,
    url: "https://boxd.it/20b2"
  },
  {
    name: "Street of Shame",
    year: 1956,
    url: "https://boxd.it/UWO"
  },
  {
    name: "Seven Weeks",
    year: 2014,
    url: "https://boxd.it/apMe"
  },
  {
    name: "Sansho the Bailiff",
    year: 1954,
    url: "https://boxd.it/1Dkq"
  },
  {
    name: "Samurai Rebellion",
    year: 1967,
    url: "https://boxd.it/2loc"
  },
  {
    name: "Rhapsody in August",
    year: 1991,
    url: "https://boxd.it/1D8a"
  },
  {
    name: "Red Post on Escher Street",
    year: 2020,
    url: "https://boxd.it/pdpi"
  },
  {
    name: "Red Beard",
    year: 1965,
    url: "https://boxd.it/251m"
  },
  {
    name: "Red Angel",
    year: 1966,
    url: "https://boxd.it/3bla"
  },
  {
    name: "Rashomon",
    year: 1950,
    url: "https://boxd.it/2a9K"
  },
  {
    name: "R100",
    year: 2013,
    url: "https://boxd.it/5Qc8"
  },
  {
    name: "Profound Desires of the Gods",
    year: 1968,
    url: "https://boxd.it/D20"
  },
  {
    name: "Princess Mononoke",
    year: 1997,
    url: "https://boxd.it/2b4w"
  },
  {
    name: "Pigs and Battleships",
    year: 1961,
    url: "https://boxd.it/1jQG"
  },
  {
    name: "Brother and Sister",
    year: 1953,
    url: "https://boxd.it/4qke"
  },
  {
    name: "Noroi: The Curse",
    year: 2005,
    url: "https://boxd.it/1BN6"
  },
  {
    name: "Mother",
    year: 1952,
    url: "https://boxd.it/1010"
  },
  {
    name: "Midnight Swan",
    year: 2020,
    url: "https://boxd.it/rcKS"
  },
  {
    name: "Memories of Matsuko",
    year: 2006,
    url: "https://boxd.it/1iVU"
  },
  {
    name: "Love and Honor",
    year: 2006,
    url: "https://boxd.it/1Dle"
  },
  {
    name: "Love & Pop",
    year: 1998,
    url: "https://boxd.it/2sv0"
  },
  {
    name: "Miss Lonely",
    year: 1985,
    url: "https://boxd.it/7LgI"
  },
  {
    name: "License to Live",
    year: 1998,
    url: "https://boxd.it/IGY"
  },
  {
    name: "Late Chrysanthemums",
    year: 1954,
    url: "https://boxd.it/19Cu"
  },
  {
    name: "Lady Snowblood",
    year: 1973,
    url: "https://boxd.it/26Fi"
  },
  {
    name: "Labyrinth of Cinema",
    year: 2019,
    url: "https://boxd.it/mNzW"
  },
  {
    name: "Kamikaze Girls",
    year: 2004,
    url: "https://boxd.it/1ucC"
  },
  {
    name: "GO",
    year: 2001,
    url: "https://boxd.it/176c"
  },
  {
    name: "Fish Story",
    year: 2009,
    url: "https://boxd.it/16Z6"
  },
  {
    name: "Black Rain",
    year: 1989,
    url: "https://boxd.it/24NY"
  },
  {
    name: "Be with You",
    year: 2004,
    url: "https://boxd.it/1bm4"
  },
  {
    name: "One Day We'll Talk About Today",
    year: 2020,
    url: "https://boxd.it/mH2i"
  },
  {
    name: "On the Run",
    year: 1988,
    url: "https://boxd.it/3Aye"
  },
  {
    name: "Loving You",
    year: 1995,
    url: "https://boxd.it/50yc"
  },
  {
    name: "Love for All Seasons",
    year: 2003,
    url: "https://boxd.it/PFS"
  },
  {
    name: "Long Arm of the Law",
    year: 1984,
    url: "https://boxd.it/2hOK"
  },
  {
    name: "Green Snake",
    year: 1993,
    url: "https://boxd.it/12Vk"
  },
  {
    name: "Flirting Scholar",
    year: 1993,
    url: "https://boxd.it/17Ig"
  },
  {
    name: "Election 2",
    year: 2006,
    url: "https://boxd.it/1MRe"
  },
  {
    name: "Don't Go Breaking My Heart",
    year: 2011,
    url: "https://boxd.it/2eUA"
  },
  {
    name: "Center Stage",
    year: 1991,
    url: "https://boxd.it/2enm"
  },
  {
    name: "Not One Less",
    year: 1999,
    url: "https://boxd.it/1b58"
  },
  {
    name: "Nice View",
    year: 2022,
    url: "https://boxd.it/ueSg"
  },
  {
    name: "My Memories of Old Beijing",
    year: 1983,
    url: "https://boxd.it/5SKw"
  },
  {
    name: "Long Day's Journey Into Night",
    year: 2018,
    url: "https://boxd.it/hw1I"
  },
  {
    name: "I Wish I Knew",
    year: 2010,
    url: "https://boxd.it/mOc"
  },
  {
    name: "HI",
    year: 2014,
    url: "https://boxd.it/dui0"
  },
  {
    name: "Fleeing by Night",
    year: 2000,
    url: "https://boxd.it/76Jk"
  },
  {
    name: "Fearless",
    year: 2006,
    url: "https://boxd.it/20Qa"
  },
  {
    name: "City of Life and Death",
    year: 2009,
    url: "https://boxd.it/1C3I"
  },
  {
    name: "Yojimbo",
    year: 1961,
    url: "https://boxd.it/1SRY"
  },
  {
    name: "Wife of a Spy",
    year: 2020,
    url: "https://boxd.it/pHCc"
  },
  {
    name: "Wife! Be Like a Rose!",
    year: 1935,
    url: "https://boxd.it/3fxa"
  },
  {
    name: "Wife",
    year: 1953,
    url: "https://boxd.it/4iVc"
  },
  {
    name: "When a Woman Ascends the Stairs",
    year: 1960,
    url: "https://boxd.it/19Ck"
  },
  {
    name: "Violent Cop",
    year: 1989,
    url: "https://boxd.it/1Rym"
  },
  {
    name: "Twenty-Four Eyes",
    year: 1954,
    url: "https://boxd.it/UJA"
  },
  {
    name: "True Mothers",
    year: 2020,
    url: "https://boxd.it/ozs2"
  },
  {
    name: "Tokyo Twilight",
    year: 1957,
    url: "https://boxd.it/sq6"
  },
  {
    name: "Tokyo Story",
    year: 1953,
    url: "https://boxd.it/1HuY"
  },
  {
    name: "Tokyo Drifter",
    year: 1966,
    url: "https://boxd.it/OTY"
  },
  {
    name: "The Yen Family",
    year: 1988,
    url: "https://boxd.it/5WVe"
  },
  {
    name: "Wandering",
    year: 2022,
    url: "https://boxd.it/w4wo"
  },
  {
    name: "The Third Murder",
    year: 2017,
    url: "https://boxd.it/fqF4"
  },
  {
    name: "The Sword of Doom",
    year: 1966,
    url: "https://boxd.it/1EoS"
  },
  {
    name: "The Most Terrible Time in My Life",
    year: 1994,
    url: "https://boxd.it/30Ko"
  },
  {
    name: "The Face of Another",
    year: 1966,
    url: "https://boxd.it/1nso"
  },
  {
    name: "Suzaki Paradise: Red Light District",
    year: 1956,
    url: "https://boxd.it/47wA"
  },
  {
    name: "Sudden Rain",
    year: 1956,
    url: "https://boxd.it/4qZQ"
  },
  {
    name: "Repast",
    year: 1951,
    url: "https://boxd.it/LlE"
  },
  {
    name: "Mirrored Mind",
    year: 2005,
    url: "https://boxd.it/2MxK"
  },
  {
    name: "Linda Linda Linda",
    year: 2005,
    url: "https://boxd.it/1s1C"
  },
  {
    name: "Lightning",
    year: 1952,
    url: "https://boxd.it/47mg"
  },
  {
    name: "Kids Return",
    year: 1996,
    url: "https://boxd.it/1sfY"
  },
  {
    name: "It's a Summer Film!",
    year: 2020,
    url: "https://boxd.it/s5fg"
  },
  {
    name: "Irezumi",
    year: 1966,
    url: "https://boxd.it/1cXg"
  },
  {
    name: "I Wish",
    year: 2011,
    url: "https://boxd.it/2L3k"
  },
  {
    name: "I Just Didn't Do It",
    year: 2007,
    url: "https://boxd.it/1AyE"
  },
  {
    name: "Honokaa Boy",
    year: 2009,
    url: "https://boxd.it/3NAs"
  },
  {
    name: "Happy Hour",
    year: 2015,
    url: "https://boxd.it/bXge"
  },
  {
    name: "Hanagatami",
    year: 2017,
    url: "https://boxd.it/hnUO"
  },
  {
    name: "Hana & Alice",
    year: 2004,
    url: "https://boxd.it/1qXa"
  },
  {
    name: "Graveyard of Honor",
    year: 2002,
    url: "https://boxd.it/1D80"
  },
  {
    name: "Graveyard of Honor",
    year: 1975,
    url: "https://boxd.it/2pVa"
  },
  {
    name: "GONIN",
    year: 1995,
    url: "https://boxd.it/1t5g"
  },
  {
    name: "Ginza Cosmetics",
    year: 1951,
    url: "https://boxd.it/3W9q"
  },
  {
    name: "Funeral Parade of Roses",
    year: 1969,
    url: "https://boxd.it/28Cg"
  },
  {
    name: "Floating Clouds",
    year: 1955,
    url: "https://boxd.it/2FLU"
  },
  {
    name: "Drunken Angel",
    year: 1948,
    url: "https://boxd.it/1uYQ"
  },
  {
    name: "Distance",
    year: 2001,
    url: "https://boxd.it/1wvc"
  },
  {
    name: "Crying Out Love in the Center of the World",
    year: 2004,
    url: "https://boxd.it/1bme"
  },
  {
    name: "Crazy Thunder Road",
    year: 1980,
    url: "https://boxd.it/2Vrw"
  },
  {
    name: "Crazed Fruit",
    year: 1956,
    url: "https://boxd.it/35g4"
  },
  {
    name: "Charisma",
    year: 1999,
    url: "https://boxd.it/2ogU"
  },
  {
    name: "Casting Blossoms to the Sky",
    year: 2012,
    url: "https://boxd.it/4aPq"
  },
  {
    name: "Bullet Ballet",
    year: 1998,
    url: "https://boxd.it/1uMg"
  },
  {
    name: "Branded to Kill",
    year: 1967,
    url: "https://boxd.it/1HSQ"
  },
  {
    name: "Boiling Point",
    year: 1990,
    url: "https://boxd.it/1sQA"
  },
  {
    name: "Blue",
    year: 2002,
    url: "https://boxd.it/3q1k"
  },
  {
    name: "Belladonna of Sadness",
    year: 1973,
    url: "https://boxd.it/2q"
  },
  {
    name: "August in the Water",
    year: 1995,
    url: "https://boxd.it/3xQE"
  },
  {
    name: "Asako I & II",
    year: 2018,
    url: "https://boxd.it/hyNk"
  },
  {
    name: "Angel Dust",
    year: 1994,
    url: "https://boxd.it/1esa"
  },
  {
    name: "An Autumn Afternoon",
    year: 1962,
    url: "https://boxd.it/CUU"
  },
  {
    name: "Tales of a Golden Geisha",
    year: 1990,
    url: "https://boxd.it/2V6e"
  },
  {
    name: "The Wiser Age",
    year: 1962,
    url: "https://boxd.it/4ygO"
  },
  {
    name: "A Taxing Woman",
    year: 1987,
    url: "https://boxd.it/XXA"
  },
  {
    name: "The Story of Yonosuke",
    year: 2013,
    url: "https://boxd.it/61pM"
  },
  {
    name: "9 Souls",
    year: 2003,
    url: "https://boxd.it/1Jqk"
  },
  {
    name: "Your Name Engraved Herein",
    year: 2020,
    url: "https://boxd.it/qWwA"
  },
  {
    name: "Terrorizers",
    year: 1986,
    url: "https://boxd.it/2IRG"
  },
  {
    name: "The Sandwich Man",
    year: 1983,
    url: "https://boxd.it/5q56"
  },
  {
    name: "The Great Buddha+",
    year: 2017,
    url: "https://boxd.it/h2rw"
  },
  {
    name: "Taipei Suicide Story",
    year: 2020,
    url: "https://boxd.it/rPVK"
  },
  {
    name: "Super Citizen Ko",
    year: 1995,
    url: "https://boxd.it/bm7k"
  },
  {
    name: "Rebels of the Neon God",
    year: 1992,
    url: "https://boxd.it/mp2"
  },
  {
    name: "Pushing Hands",
    year: 1991,
    url: "https://boxd.it/1w38"
  },
  {
    name: "Moneyboys",
    year: 2021,
    url: "https://boxd.it/pdYi"
  },
  {
    name: "Man in Love",
    year: 2021,
    url: "https://boxd.it/u1t8"
  },
  {
    name: "La Luxure",
    year: 1962,
    url: "https://boxd.it/x6GM"
  },
  {
    name: "In Our Time",
    year: 1982,
    url: "https://boxd.it/4glG"
  },
  {
    name: "Growing Up",
    year: 1983,
    url: "https://boxd.it/5q4i"
  },
  {
    name: "Flowers of Shanghai",
    year: 1998,
    url: "https://boxd.it/Omq"
  },
  {
    name: "Daughter of the Nile",
    year: 1987,
    url: "https://boxd.it/3pU4"
  },
  {
    name: "CafÃ© LumiÃ¨re",
    year: 2003,
    url: "https://boxd.it/yNA"
  },
  {
    name: "A Summer at Grandpa's",
    year: 1984,
    url: "https://boxd.it/3fGQ"
  },
  {
    name: "YMCA Baseball Team",
    year: 2002,
    url: "https://boxd.it/3Z1Y"
  },
  {
    name: "Woman on the Beach",
    year: 2006,
    url: "https://boxd.it/tKm"
  },
  {
    name: "Whispering Corridors",
    year: 1998,
    url: "https://boxd.it/127a"
  },
  {
    name: "Wedding Dress",
    year: 2010,
    url: "https://boxd.it/69OU"
  },
  {
    name: "Way Back Home",
    year: 2013,
    url: "https://boxd.it/77ME"
  },
  {
    name: "Virgin Stripped Bare by Her Bachelors",
    year: 2000,
    url: "https://boxd.it/tFw"
  },
  {
    name: "Timeless Bottomless Bad Movie",
    year: 1997,
    url: "https://boxd.it/3sKm"
  },
  {
    name: "The Woman Who Ran",
    year: 2020,
    url: "https://boxd.it/oEEi"
  },
  {
    name: "The Warrior",
    year: 2001,
    url: "https://boxd.it/28KO"
  },
  {
    name: "The Tiger",
    year: 2015,
    url: "https://boxd.it/cpvG"
  },
  {
    name: "The Terror Live",
    year: 2013,
    url: "https://boxd.it/6gEs"
  },
  {
    name: "The Show Must Go On",
    year: 2007,
    url: "https://boxd.it/r2s"
  },
  {
    name: "The Novelist's Film",
    year: 2022,
    url: "https://boxd.it/yZX6"
  },
  {
    name: "The Last Witness",
    year: 1980,
    url: "https://boxd.it/6CEY"
  },
  {
    name: "The Killer",
    year: 2022,
    url: "https://boxd.it/zmR6"
  },
  {
    name: "The Harmonium in My Memory",
    year: 1999,
    url: "https://boxd.it/4ygY"
  },
  {
    name: "The Girl on a Bulldozer",
    year: 2022,
    url: "https://boxd.it/trTa"
  },
  {
    name: "The Contact",
    year: 1997,
    url: "https://boxd.it/5zQK"
  },
  {
    name: "The Coachman",
    year: 1961,
    url: "https://boxd.it/7T7E"
  },
  {
    name: "The Chase",
    year: 2017,
    url: "https://boxd.it/hAMe"
  },
  {
    name: "The Box",
    year: 2021,
    url: "https://boxd.it/mPoG"
  },
  {
    name: "The Book of Fish",
    year: 2021,
    url: "https://boxd.it/lnua"
  },
  {
    name: "The Bacchus Lady",
    year: 2016,
    url: "https://boxd.it/dzXs"
  },
  {
    name: "The Age of Shadows",
    year: 2016,
    url: "https://boxd.it/cruq"
  },
  {
    name: "The Admiral: Roaring Currents",
    year: 2014,
    url: "https://boxd.it/8J0U"
  },
  {
    name: "Tazza: The High Rollers",
    year: 2006,
    url: "https://boxd.it/16Yi"
  },
  {
    name: "Tale of Cinema",
    year: 2005,
    url: "https://boxd.it/31H6"
  },
  {
    name: "Sunny",
    year: 2008,
    url: "https://boxd.it/Z8u"
  },
  {
    name: "Spiritwalker",
    year: 2020,
    url: "https://boxd.it/mdKa"
  },
  {
    name: "Special Delivery",
    year: 2022,
    url: "https://boxd.it/momI"
  },
  {
    name: "Sopyonje",
    year: 1993,
    url: "https://boxd.it/45Da"
  },
  {
    name: "Snowy Road",
    year: 2015,
    url: "https://boxd.it/fDru"
  },
  {
    name: "Short Vacation",
    year: 2020,
    url: "https://boxd.it/rSDa"
  },
  {
    name: "Seoul Station",
    year: 2016,
    url: "https://boxd.it/dBYs"
  },
  {
    name: "Sad Movie",
    year: 2005,
    url: "https://boxd.it/1H0a"
  },
  {
    name: "Sorry Apple",
    year: 2005,
    url: "https://boxd.it/1uRK"
  },
  {
    name: "Our Sunhi",
    year: 2013,
    url: "https://boxd.it/6juq"
  },
  {
    name: "Ode To My Father",
    year: 2014,
    url: "https://boxd.it/a4Bu"
  },
  {
    name: "Nobody's Daughter Haewon",
    year: 2013,
    url: "https://boxd.it/50g8"
  },
  {
    name: "Nameless Gangster",
    year: 2012,
    url: "https://boxd.it/39VA"
  },
  {
    name: "My Perfect Roommate",
    year: 2022,
    url: "https://boxd.it/A7RC"
  },
  {
    name: "My Lovely Angel",
    year: 2021,
    url: "https://boxd.it/uNtU"
  },
  {
    name: "My First Client",
    year: 2019,
    url: "https://boxd.it/lLYS"
  },
  {
    name: "My Dear Enemy",
    year: 2008,
    url: "https://boxd.it/1F4k"
  },
  {
    name: "Missing You",
    year: 2016,
    url: "https://boxd.it/dDmA"
  },
  {
    name: "Life Is Beautiful",
    year: 2022,
    url: "https://boxd.it/mO1c"
  },
  {
    name: "Kim Min-young of the Report Card",
    year: 2021,
    url: "https://boxd.it/ujaI"
  },
  {
    name: "Io Island",
    year: 1977,
    url: "https://boxd.it/3xM8"
  },
  {
    name: "I Want to Know Your Parents",
    year: 2022,
    url: "https://boxd.it/njg8"
  },
  {
    name: "Hunt",
    year: 2022,
    url: "https://boxd.it/rgNG"
  },
  {
    name: "Hill of Freedom",
    year: 2014,
    url: "https://boxd.it/8MSU"
  },
  {
    name: "Helpless",
    year: 2012,
    url: "https://boxd.it/3FKa"
  },
  {
    name: "Happy End",
    year: 1999,
    url: "https://boxd.it/1sq8"
  },
  {
    name: "Hansan: Rising Dragon",
    year: 2022,
    url: "https://boxd.it/lDUI"
  },
  {
    name: "Ha Ha Ha",
    year: 2010,
    url: "https://boxd.it/gQm"
  },
  {
    name: "Going by the Book",
    year: 2007,
    url: "https://boxd.it/14Mu"
  },
  {
    name: "Rafiki",
    year: 2018,
    url: "https://boxd.it/iMFc"
  },
  {
    name: "Flame in Valley",
    year: 1967,
    url: "https://boxd.it/8bp2"
  },
  {
    name: "Everglow",
    year: 2020,
    url: "https://boxd.it/qVjA"
  },
  {
    name: "Escape from Mogadishu",
    year: 2021,
    url: "https://boxd.it/mrOq"
  },
  {
    name: "Endless Rain",
    year: 2021,
    url: "https://boxd.it/op4O"
  },
  {
    name: "Declaration of Fools",
    year: 1984,
    url: "https://boxd.it/7UK8"
  },
  {
    name: "Crush and Blush",
    year: 2008,
    url: "https://boxd.it/z34"
  },
  {
    name: "Confidential Assignment 2: International",
    year: 2022,
    url: "https://boxd.it/rEds"
  },
  {
    name: "Confidential Assignment",
    year: 2017,
    url: "https://boxd.it/fp68"
  },
  {
    name: "City of the Rising Sun",
    year: 1999,
    url: "https://boxd.it/7ZOu"
  },
  {
    name: "Chilsu and Mansu",
    year: 1988,
    url: "https://boxd.it/7BPe"
  },
  {
    name: "Painted Fire",
    year: 2002,
    url: "https://boxd.it/1Hcg"
  },
  {
    name: "Cart",
    year: 2014,
    url: "https://boxd.it/8VOC"
  },
  {
    name: "Bunt",
    year: 2007,
    url: "https://boxd.it/35kq"
  },
  {
    name: "Bori",
    year: 2018,
    url: "https://boxd.it/lpIe"
  },
  {
    name: "Birdcage Inn",
    year: 1998,
    url: "https://boxd.it/26jG"
  },
  {
    name: "Amen",
    year: 2011,
    url: "https://boxd.it/4SsK"
  },
  {
    name: "Along with the Gods: The Two Worlds",
    year: 2017,
    url: "https://boxd.it/dVlA"
  },
  {
    name: "Along with the Gods: The Last 49 Days",
    year: 2018,
    url: "https://boxd.it/iMGu"
  },
  {
    name: "Aimless Bullet",
    year: 1961,
    url: "https://boxd.it/2skQ"
  },
  {
    name: "A Year-End Medley",
    year: 2021,
    url: "https://boxd.it/uY1W"
  },
  {
    name: "A Werewolf Boy",
    year: 2012,
    url: "https://boxd.it/4c2A"
  },
  {
    name: "A Frozen Flower",
    year: 2008,
    url: "https://boxd.it/1HTa"
  },
  {
    name: "A Day Off",
    year: 1968,
    url: "https://boxd.it/80Vw"
  },
  {
    name: "Forever the Moment",
    year: 2008,
    url: "https://boxd.it/1GYS"
  },
  {
    name: "Dongju: The Portrait of a Poet",
    year: 2016,
    url: "https://boxd.it/djza"
  },
  {
    name: "A Boy and Sungreen",
    year: 2018,
    url: "https://boxd.it/k9oA"
  },
  {
    name: 2037,
    year: 2022,
    url: "https://boxd.it/vrma"
  },
  {
    name: "Yellow Flowers On the Green Grass",
    year: 2015,
    url: "https://boxd.it/cjXa"
  },
  {
    name: "The Scent of Green Papaya",
    year: 1993,
    url: "https://boxd.it/1EWq"
  },
  {
    name: "Journey From the Fall",
    year: 2006,
    url: "https://boxd.it/1v7y"
  },
  {
    name: "Dreamy Eyes",
    year: 2019,
    url: "https://boxd.it/mRNo"
  },
  {
    name: "Love of Siam",
    year: 2007,
    url: "https://boxd.it/pso"
  },
  {
    name: "One for the Road",
    year: 2021,
    url: "https://boxd.it/tbjq"
  },
  {
    name: "Once Upon a Time... This Morning",
    year: 1994,
    url: "https://boxd.it/bm5o"
  },
  {
    name: "Mysterious Object at Noon",
    year: 2000,
    url: "https://boxd.it/3gqu"
  },
  {
    name: "Memoria",
    year: 2021,
    url: "https://boxd.it/iwtE"
  },
  {
    name: "Friend Zone",
    year: 2019,
    url: "https://boxd.it/lqvg"
  },
  {
    name: "Cemetery of Splendor",
    year: 2015,
    url: "https://boxd.it/9tIo"
  },
  {
    name: "Insiang",
    year: 1976,
    url: "https://boxd.it/3FMg"
  },
  {
    name: "The Wandering Princess",
    year: 1960,
    url: "https://boxd.it/7zw0"
  },
  {
    name: "Love Under the Crucifix",
    year: 1962,
    url: "https://boxd.it/7Atm"
  },
  {
    name: "Triangle of Sadness",
    year: 2022,
    url: "https://boxd.it/hXlq"
  },
  {
    name: "The Fabelmans",
    year: 2022,
    url: "https://boxd.it/ugoM"
  },
  {
    name: "Terrifier 2",
    year: 2022,
    url: "https://boxd.it/oI10"
  },
  {
    name: "Take Out",
    year: 2004,
    url: "https://boxd.it/17DA"
  },
  {
    name: "Bullet Train",
    year: 2022,
    url: "https://boxd.it/qW26"
  },
  {
    name: "Aftersun",
    year: 2022,
    url: "https://boxd.it/Arw0"
  },
  {
    name: "The Raid",
    year: 2011,
    url: "https://boxd.it/3hBy"
  },
  {
    name: "The Raid 2",
    year: 2014,
    url: "https://boxd.it/5uz0"
  },
  {
    name: "Satan's Slaves",
    year: 2017,
    url: "https://boxd.it/gJ1E"
  },
  {
    name: "Impetigore",
    year: 2019,
    url: "https://boxd.it/l1fs"
  },
  {
    name: "Twelve Nights",
    year: 2000,
    url: "https://boxd.it/Pp6"
  },
  {
    name: "Tricky Brains",
    year: 1991,
    url: "https://boxd.it/ZxE"
  },
  {
    name: "Three Husbands",
    year: 2018,
    url: "https://boxd.it/k6Pe"
  },
  {
    name: "Threeâ€¦ Extremes",
    year: 2004,
    url: "https://boxd.it/1eGw"
  },
  {
    name: "The Prodigal Son",
    year: 1981,
    url: "https://boxd.it/Zvy"
  },
  {
    name: "The Longest Nite",
    year: 1998,
    url: "https://boxd.it/103g"
  },
  {
    name: "The Legend of Drunken Master",
    year: 1994,
    url: "https://boxd.it/1Si0"
  },
  {
    name: "The Bare-Footed Kid",
    year: 1993,
    url: "https://boxd.it/4oiK"
  },
  {
    name: "Shanghai Blues",
    year: 1984,
    url: "https://boxd.it/4zMG"
  },
  {
    name: "School on Fire",
    year: 1988,
    url: "https://boxd.it/3MAc"
  },
  {
    name: "Rouge",
    year: 1987,
    url: "https://boxd.it/2cdk"
  },
  {
    name: "ProtÃ©gÃ©",
    year: 2007,
    url: "https://boxd.it/1JPO"
  },
  {
    name: "Police Story 3: Super Cop",
    year: 1992,
    url: "https://boxd.it/1Uyk"
  },
  {
    name: "One Nite in Mongkok",
    year: 2004,
    url: "https://boxd.it/1oQc"
  },
  {
    name: "Love Unto Wastes",
    year: 1986,
    url: "https://boxd.it/4SqE"
  },
  {
    name: "Lost and Found",
    year: 1996,
    url: "https://boxd.it/3Vt0"
  },
  {
    name: "Infernal Affairs III",
    year: 2003,
    url: "https://boxd.it/1Okw"
  },
  {
    name: "Infernal Affairs II",
    year: 2003,
    url: "https://boxd.it/1Tla"
  },
  {
    name: "Hand Rolled Cigarette",
    year: 2020,
    url: "https://boxd.it/rPmK"
  },
  {
    name: "Fly Me to Polaris",
    year: 1999,
    url: "https://boxd.it/PsY"
  },
  {
    name: "Eros",
    year: 2004,
    url: "https://boxd.it/135k"
  },
  {
    name: "Drifting",
    year: 2021,
    url: "https://boxd.it/rNl6"
  },
  {
    name: "Dragons Forever",
    year: 1988,
    url: "https://boxd.it/1BtK"
  },
  {
    name: "Dangerous Encounters of the First Kind",
    year: 1980,
    url: "https://boxd.it/3xOy"
  },
  {
    name: "Bullets Over Summer",
    year: 1999,
    url: "https://boxd.it/2cQG"
  },
  {
    name: "Big Bullet",
    year: 1996,
    url: "https://boxd.it/39Ks"
  },
  {
    name: "Beyond the Dream",
    year: 2019,
    url: "https://boxd.it/p9gm"
  },
  {
    name: "Ashes of Time",
    year: 1994,
    url: "https://boxd.it/111K"
  },
  {
    name: "A Chinese Ghost Story",
    year: 1987,
    url: "https://boxd.it/1lmI"
  },
  {
    name: "Waiting Alone",
    year: 2005,
    url: "https://boxd.it/2Ane"
  },
  {
    name: "The Story of Qiu Ju",
    year: 1992,
    url: "https://boxd.it/16FU"
  },
  {
    name: "The Piano in a Factory",
    year: 2010,
    url: "https://boxd.it/2oTM"
  },
  {
    name: "The King of Masks",
    year: 1995,
    url: "https://boxd.it/1vKU"
  },
  {
    name: "The Falls",
    year: 2021,
    url: "https://boxd.it/wb8I"
  },
  {
    name: "Suzhou River",
    year: 2000,
    url: "https://boxd.it/1Tsq"
  },
  {
    name: "So Long",
    year: 2017,
    url: "https://boxd.it/ix88"
  },
  {
    name: "Saturday Fiction",
    year: 2019,
    url: "https://boxd.it/hXmo"
  },
  {
    name: "Pickpocket",
    year: 1997,
    url: "https://boxd.it/zPi"
  },
  {
    name: "One Second",
    year: 2020,
    url: "https://boxd.it/l71G"
  },
  {
    name: "Mountain Patrol",
    year: 2004,
    url: "https://boxd.it/1KSO"
  },
  {
    name: "Lighting Up the Stars",
    year: 2022,
    url: "https://boxd.it/zFts"
  },
  {
    name: "In the Heat of the Sun",
    year: 1994,
    url: "https://boxd.it/523q"
  },
  {
    name: "House of Flying Daggers",
    year: 2004,
    url: "https://boxd.it/1YoI"
  },
  {
    name: "Cliff Walkers",
    year: 2021,
    url: "https://boxd.it/nJda"
  },
  {
    name: "An Elephant Sitting Still",
    year: 2018,
    url: "https://boxd.it/i1EQ"
  },
  {
    name: "Aftershock",
    year: 2010,
    url: "https://boxd.it/REM"
  },
  {
    name: "A Touch of Sin",
    year: 2013,
    url: "https://boxd.it/5Fvo"
  },
  {
    name: "The King",
    year: 2017,
    url: "https://boxd.it/fqnk"
  },
  {
    name: "Back to Back, Face to Face",
    year: 1994,
    url: "https://boxd.it/9l0y"
  }
],
filmin:[
  {
    name: "Antichrist",
    year: 2009,
    url: "https://boxd.it/1Inu"
  },
  {
    name: "Jules and Jim",
    year: 1962,
    url: "https://boxd.it/28rM"
  },
  {
    name: "The Green Ray",
    year: 1986,
    url: "https://boxd.it/t8W"
  },
  {
    name: "A Woman Under the Influence",
    year: 1974,
    url: "https://boxd.it/1myg"
  },
  {
    name: "Les MisÃ©rables",
    year: 2019,
    url: "https://boxd.it/lAPA"
  },
  {
    name: "The Official Story",
    year: 1985,
    url: "https://boxd.it/1nS2"
  },
  {
    name: "Chinatown",
    year: 1974,
    url: "https://boxd.it/29vU"
  },
  {
    name: "First Cow",
    year: 2019,
    url: "https://boxd.it/krga"
  },
  {
    name: "Guess Who's Coming to Dinner",
    year: 1967,
    url: "https://boxd.it/27Xi"
  },
  {
    name: "Knife in the Water",
    year: 1962,
    url: "https://boxd.it/1THK"
  },
  {
    name: "The Sweet Hereafter",
    year: 1997,
    url: "https://boxd.it/1WNm"
  },
  {
    name: "Ararat",
    year: 2002,
    url: "https://boxd.it/1Ki2"
  },
  {
    name: "The Great Beauty",
    year: 2013,
    url: "https://boxd.it/5ty6"
  },
  {
    name: "Lullaby",
    year: 2022,
    url: "https://boxd.it/vvUA"
  },
  {
    name: "Dersu Uzala",
    year: 1975,
    url: "https://boxd.it/1XRO"
  },
  {
    name: "God's Own Country",
    year: 2017,
    url: "https://boxd.it/faZM"
  },
  {
    name: "Tokyo Story",
    year: 1953,
    url: "https://boxd.it/1HuY"
  },
  {
    name: "Persepolis",
    year: 2007,
    url: "https://boxd.it/27DC"
  },
  {
    name: "Scarlet Street",
    year: 1945,
    url: "https://boxd.it/1JgE"
  },
  {
    name: "The Elephant Man",
    year: 1980,
    url: "https://boxd.it/27LQ"
  },
  {
    name: 1985,
    year: 2018,
    url: "https://boxd.it/i8ke"
  },
  {
    name: "Nights of Cabiria",
    year: 1957,
    url: "https://boxd.it/1F7e"
  },
  {
    name: "The Front Page",
    year: 1974,
    url: "https://boxd.it/299a"
  },
  {
    name: "The Children's Hour",
    year: 1961,
    url: "https://boxd.it/1DZI"
  },
  {
    name: "Mississippi Burning",
    year: 1988,
    url: "https://boxd.it/28r8"
  },
  {
    name: "Mustang",
    year: 2015,
    url: "https://boxd.it/baaw"
  },
  {
    name: "Fried Green Tomatoes",
    year: 1991,
    url: "https://boxd.it/28qY"
  },
  {
    name: "Ida",
    year: 2013,
    url: "https://boxd.it/6fRg"
  },
  {
    name: "Sweet Bean",
    year: 2015,
    url: "https://boxd.it/alaK"
  },
  {
    name: "The Rider",
    year: 2017,
    url: "https://boxd.it/gazw"
  },
  {
    name: "Au Revoir les Enfants",
    year: 1987,
    url: "https://boxd.it/288U"
  },
  {
    name: "A Special Day",
    year: 1977,
    url: "https://boxd.it/Xqc"
  },
  {
    name: "Sorry We Missed You",
    year: 2019,
    url: "https://boxd.it/iXBg"
  },
  {
    name: "Network",
    year: 1976,
    url: "https://boxd.it/1VqG"
  },
  {
    name: "Cat on a Hot Tin Roof",
    year: 1958,
    url: "https://boxd.it/2aK2"
  },
  {
    name: "Rome, Open City",
    year: 1945,
    url: "https://boxd.it/2aD6"
  },
  {
    name: "Sleuth",
    year: 1972,
    url: "https://boxd.it/298c"
  },
  {
    name: "Do the Right Thing",
    year: 1989,
    url: "https://boxd.it/29gA"
  },
  {
    name: "The Best Years of Our Lives",
    year: 1946,
    url: "https://boxd.it/29my"
  },
  {
    name: "Hannah and Her Sisters",
    year: 1986,
    url: "https://boxd.it/23jy"
  },
  {
    name: "The Passion of Joan of Arc",
    year: 1928,
    url: "https://boxd.it/29DO"
  },
  {
    name: "A Most Violent Year",
    year: 2014,
    url: "https://boxd.it/75Va"
  },
  {
    name: "The Bad and the Beautiful",
    year: 1952,
    url: "https://boxd.it/1h3M"
  },
  {
    name: "In Between",
    year: 2016,
    url: "https://boxd.it/ewKC"
  },
  {
    name: "It All Starts Today",
    year: 1999,
    url: "https://boxd.it/1hnM"
  },
  {
    name: "The Chase",
    year: 1966,
    url: "https://boxd.it/1iJu"
  },
  {
    name: "Loving Vincent",
    year: 2017,
    url: "https://boxd.it/biIQ"
  },
  {
    name: "Frantz",
    year: 2016,
    url: "https://boxd.it/d6Ym"
  },
  {
    name: "Weekend",
    year: 2011,
    url: "https://boxd.it/2Kzu"
  },
  {
    name: "Out of Africa",
    year: 1985,
    url: "https://boxd.it/2a0S"
  },
  {
    name: "Gaslight",
    year: 1944,
    url: "https://boxd.it/1PYs"
  },
  {
    name: "Tangerines",
    year: 2013,
    url: "https://boxd.it/71vM"
  },
  {
    name: "Fanny and Alexander",
    year: 1982,
    url: "https://boxd.it/22go"
  },
  {
    name: "Suffragette",
    year: 2015,
    url: "https://boxd.it/7cxY"
  },
  {
    name: "Wind River",
    year: 2017,
    url: "https://boxd.it/dR3i"
  },
  {
    name: "The Conversation",
    year: 1974,
    url: "https://boxd.it/2a38"
  },
  {
    name: "Avanti!",
    year: 1972,
    url: "https://boxd.it/1RMo"
  },
  {
    name: "In the Heat of the Night",
    year: 1967,
    url: "https://boxd.it/1VLY"
  },
  {
    name: "Secrets & Lies",
    year: 1996,
    url: "https://boxd.it/1UuC"
  },
  {
    name: "Too Late",
    year: 2015,
    url: "https://boxd.it/bpCU"
  },
  {
    name: "The Return",
    year: 2003,
    url: "https://boxd.it/1UpM"
  },
  {
    name: "Babyteeth",
    year: 2019,
    url: "https://boxd.it/iWDU"
  },
  {
    name: "Autumn Sonata",
    year: 1978,
    url: "https://boxd.it/1Rio"
  },
  {
    name: "La rÃ¨gle du jeu",
    year: 2017,
    url: "https://boxd.it/fEIc"
  },
  {
    name: "On the Waterfront",
    year: 1954,
    url: "https://boxd.it/29TC"
  },
  {
    name: "The Purple Rose of Cairo",
    year: 1985,
    url: "https://boxd.it/1VeU"
  },
  {
    name: "Rififi",
    year: 1955,
    url: "https://boxd.it/29f8"
  },
  {
    name: "Night on Earth",
    year: 1991,
    url: "https://boxd.it/2ayq"
  },
  {
    name: "I Wish",
    year: 2011,
    url: "https://boxd.it/2L3k"
  },
  {
    name: "Missing",
    year: 1982,
    url: "https://boxd.it/1LTI"
  },
  {
    name: "Three Colors: Red",
    year: 1994,
    url: "https://boxd.it/2b7q"
  },
  {
    name: "Three Colors: White",
    year: 1994,
    url: "https://boxd.it/2b7A"
  },
  {
    name: "The Little Foxes",
    year: 1941,
    url: "https://boxd.it/Tym"
  },
  {
    name: "Fahrenheit 451",
    year: 1966,
    url: "https://boxd.it/28fw"
  },
  {
    name: "Girl",
    year: 2018,
    url: "https://boxd.it/iGU6"
  },
  {
    name: "The Hours",
    year: 2002,
    url: "https://boxd.it/2a3s"
  },
  {
    name: "Jane Eyre",
    year: 2011,
    url: "https://boxd.it/15rs"
  },
  {
    name: "Wadjda",
    year: 2012,
    url: "https://boxd.it/4drw"
  },
  {
    name: "Day for Night",
    year: 1973,
    url: "https://boxd.it/28kG"
  },
  {
    name: "Kramer vs. Kramer",
    year: 1979,
    url: "https://boxd.it/h0w"
  },
  {
    name: "Virgin Mountain",
    year: 2015,
    url: "https://boxd.it/aorY"
  },
  {
    name: "The African Queen",
    year: 1951,
    url: "https://boxd.it/2ai8"
  },
  {
    name: "Two for the Road",
    year: 1967,
    url: "https://boxd.it/22AI"
  },
  {
    name: "Radio Days",
    year: 1987,
    url: "https://boxd.it/1kms"
  },
  {
    name: "Vivre Sa Vie",
    year: 1962,
    url: "https://boxd.it/28s6"
  },
  {
    name: "About Elly",
    year: 2009,
    url: "https://boxd.it/18Ry"
  },
  {
    name: "The Salesman",
    year: 2016,
    url: "https://boxd.it/d2we"
  },
  {
    name: "A Fish Called Wanda",
    year: 1988,
    url: "https://boxd.it/29YC"
  },
  {
    name: "So Long, My Son",
    year: 2019,
    url: "https://boxd.it/hNzi"
  },
  {
    name: "Hidden Agenda",
    year: 1990,
    url: "https://boxd.it/JGq"
  },
  {
    name: "The Square",
    year: 2017,
    url: "https://boxd.it/e5YW"
  },
  {
    name: "Detachment",
    year: 2011,
    url: "https://boxd.it/2BiY"
  },
  {
    name: "Turtles Can Fly",
    year: 2004,
    url: "https://boxd.it/20l2"
  },
  {
    name: "Under the Hawthorn Tree",
    year: 2010,
    url: "https://boxd.it/Dp4"
  },
  {
    name: "Barton Fink",
    year: 1991,
    url: "https://boxd.it/2aFQ"
  },
  {
    name: "Forbidden Games",
    year: 1952,
    url: "https://boxd.it/23ty"
  },
  {
    name: "Synecdoche, New York",
    year: 2008,
    url: "https://boxd.it/23zw"
  },
  {
    name: "An Elephant Sitting Still",
    year: 2018,
    url: "https://boxd.it/i1EQ"
  },
  {
    name: "Alice in the Cities",
    year: 1974,
    url: "https://boxd.it/27cG"
  },
  {
    name: "Bacurau",
    year: 2019,
    url: "https://boxd.it/fSUG"
  },
  {
    name: "On Golden Pond",
    year: 1981,
    url: "https://boxd.it/1T1u"
  },
  {
    name: "Winter's Bone",
    year: 2010,
    url: "https://boxd.it/14FI"
  },
  {
    name: "The Collector",
    year: 1965,
    url: "https://boxd.it/W8Q"
  },
  {
    name: "Crash",
    year: 1996,
    url: "https://boxd.it/29n2"
  },
  {
    name: "Wild at Heart",
    year: 1990,
    url: "https://boxd.it/2aii"
  },
  {
    name: "The Double Life of VÃ©ronique",
    year: 1991,
    url: "https://boxd.it/28va"
  },
  {
    name: "Ghost World",
    year: 2001,
    url: "https://boxd.it/28Dy"
  },
  {
    name: "Cyrano de Bergerac",
    year: 1990,
    url: "https://boxd.it/1TgY"
  },
  {
    name: "The Second Mother",
    year: 2015,
    url: "https://boxd.it/9Ydm"
  },
  {
    name: "Dead Ringers",
    year: 1988,
    url: "https://boxd.it/1Yqk"
  },
  {
    name: "My Dinner with Andre",
    year: 1981,
    url: "https://boxd.it/1vLe"
  },
  {
    name: "L'Avventura",
    year: 1960,
    url: "https://boxd.it/23hs"
  },
  {
    name: "Kabei: Our Mother",
    year: 2008,
    url: "https://boxd.it/1vcI"
  },
  {
    name: "Brother",
    year: 1997,
    url: "https://boxd.it/1CA8"
  },
  {
    name: "Street of Shame",
    year: 1956,
    url: "https://boxd.it/UWO"
  },
  {
    name: "Submarino",
    year: 2010,
    url: "https://boxd.it/Mk8"
  },
  {
    name: "Philomena",
    year: 2013,
    url: "https://boxd.it/69OA"
  },
  {
    name: "Drifting Clouds",
    year: 1996,
    url: "https://boxd.it/20tU"
  },
  {
    name: "The Trial",
    year: 1962,
    url: "https://boxd.it/25Xg"
  },
  {
    name: "Winter Sleep",
    year: 2014,
    url: "https://boxd.it/7Ua0"
  },
  {
    name: "The Wild Pear Tree",
    year: 2018,
    url: "https://boxd.it/eMtM"
  },
  {
    name: "Enter the Void",
    year: 2009,
    url: "https://boxd.it/1dy2"
  }
]
    }
  },
computed: {
    randomElementFilmin() {
      const index = Math.floor(Math.random() * (this.filmin.length))
      const randomElement = this.filmin[index];
      return randomElement;
    },
    randomElementCantina() {
      const index = Math.floor(Math.random() * (this.cantina.length))
      const randomElement = this.cantina[index];
      return randomElement;
    }
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
.title{
  font-size:1.5rem;
  
}

.year{
  margin-top:0px;
  padding-top: 0px;
  line-height:1.5rem;
  font-size:2rem;
  font-weight: 900;
  color:white;
}  

.banner{
  font-family: 'Roboto Slab', serif;
  font-size: 2rem;
  text-transform: uppercase;
  background-color: rgb(30, 30, 30);
  color:white; 
  padding: 0.25rem
}
.botton{
  width: 120px;
  height: 50px;
  margin: 0 auto;
  vertical-align: middle;
  font-weight: 800;
  border-radius: 0.6rem;
  font-size:1rem;
  color: rgb(30, 30, 30);
}
a{
  color:rgb(236, 236, 236)
}
.hello{
  background-color: rgb(34, 34, 34);
}
footer{
  font-size: 1rem;
}

@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@600&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Yaldevi:wght@400;600&display=swap');
body{
  margin: 0;
  padding: 0;
  font-family: 'Yaldevi', sans-serif;
}
span{
  color: #fc5c65;
  font-weight:900;
 
}
 
footer{
  padding: 10px 0;
}
 
.footer-container{
  max-width: 1800px;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap-reverse;
}
 
.logo{
  width: 180px;
}
 
.social-media{
  margin: 20px 0;
}
 
.social-media a{
  color: white;
  margin-right: 25px;
  font-size: 22px;
  text-decoration: none;
  transition: .3s linear;
}
 
.social-media a:hover{
  color: #fc5c65;
}
   .footer-container{
    max-width: 250px;
  }
 
  .left-col{
    width: 100%;
    text-align: center;
  }
.rights-text{
  color:white;
  font-size: 0.85rem;
}

.img{
  margin-top:1rem;
}
 
</style>
