<template>
  <div class="hello">
    <div class="banner">¿Qué veo hoy?</div>
    <p class="title">{{randomElement.name}}</p>
    <p class="year">{{randomElement.year}}</p>
    <button class="botton" @click="reloadPage">Actualiza</button>


  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  methods: {
    reloadPage() {
      window.location.reload();
    }
  },
data() {
    return {
      data: [       {name: '13 Assassins', year: '2010'},
  {
   name: '13 Hours: The Secret Soldiers of Benghazi',
    year: '2016'
  },
  {
   name: '2/Duo',
    year: '1997'
  },
  {
   name: '2037',
    year: '2022'
  },
  {
   name: '20th Century Nostalgia',
    year: '1997'
  },
  {
   name: '20th Century Women',
    year: '2016'
  },
  {
   name: '25th Hour',
    year: '2002'
  },
  {
   name: '3 Women',
    year: '1977'
  },
  {
   name: '35 Shots of Rum',
    year: '2008'
  },
  {
   name: '37 Seconds',
    year: '2019'
  },
  {
   name: '06/45',
    year: '2022'
  },
  {
   name: '9 Souls',
    year: '2003'
  },
  {
   name: 'A Ball Shot by a Midget',
    year: '1981'
  },
  {
   name: 'A Boy and Sungreen',
    year: '2018'
  },
  {
   name: 'A Chinese Ghost Story',
    year: '1987'
  },
  {
   name: 'A Colt Is My Passport',
    year: '1967'
  },
  {
   name: 'A Day Off',
    year: '1968'
  },
  {
   name: 'A Distant Cry from Spring',
    year: '1980'
  },
  {
   name: 'A Distant Place',
    year: '2020'
  },
  {
   name: 'A Dog`s Will',
    year: '2000'
  },
  {
   name: 'A Family',
    year: '2020'
  },
  {
   name: 'A Family Affair',
    year: '1984'
  },
  {
   name: 'A Frozen Flower',
    year: '2008'
  },
  {
   name: 'A Geisha',
    year: '1953'
  },
  {
   name: 'A Gentle Breeze in the Village',
    year: '2007'
  },
  {
   name: 'A Girl Walks Home Alone at Night',
    year: '2014'
  },
  {
   name: 'A Hen in the Wind',
    year: '1948'
  },
  {
   name: 'A History of Violence',
    year: '2005'
  },
  {
   name: 'A Hometown in Heart',
    year: '1949'
  },
  {
   name: 'A Hot Roof',
    year: '1995'
  },
  {
   name: 'A Midsummer`s Fantasia',
    year: '2014'
  },
  {
   name: 'A New Leaf',
    year: '1971'
  },
  {
   name: 'A Night in Nude',
    year: '1993'
  },
  {
   name: 'A Perfect World',
    year: '1993'
  },
  {
   name: 'A Petal',
    year: '1996'
  },
  {
   name: 'A Petty Middle Manager',
    year: '1961'
  },
  {
   name: 'A Pool Without Water',
    year: '1982'
  },
  {
   name: 'A Quiet Dream',
    year: '2016'
  },
  {
   name: 'A Resistance',
    year: '2019'
  },
  {
   name: 'A Season of Good Rain',
    year: '2009'
  },
  {
   name: 'A Short Love Affair',
    year: '1990'
  },
  {
   name: 'A Single Spark',
    year: '1995'
  },
  {
   name: 'A Special Day',
    year: '1977'
  },
  {
   name: 'The Story of Yonosuke',
    year: '2013'
  },
  {
   name: 'A Summer at Grandpa`s',
    year: '1984'
  },
  {
   name: 'A Summer`s Tale',
    year: '1996'
  },
  {
   name: 'A Taxing Woman',
    year: '1987'
  },
  {
   name: 'A Touch of Sin',
    year: '2013'
  },
  {
   name: 'A Werewolf Boy',
    year: '2012'
  },
  {
   name: 'A Woman After a Killer Butterfly',
    year: '1978'
  },
  {
   name: 'A Woman Under the Influence',
    year: '1974'
  },
  {
   name: 'The Wiser Age',
    year: '1962'
  },
  {
   name: 'A Year-End Medley',
    year: '2021'
  },
  {
   name: 'About the Pink Sky',
    year: '2011'
  },
  {
   name: 'Ad Lib Night',
    year: '2006'
  },
  {
   name: 'Adventures of Zatoichi',
    year: '1964'
  },
  {
   name: 'After the Storm',
    year: '2016'
  },
  {
   name: 'Aftershock',
    year: '2010'
  },
  {
   name: 'Aftersun',
    year: '2022'
  },
  {
   name: 'Tales of a Golden Geisha',
    year: '1990'
  },
  {
   name: 'Aimless Bullet',
    year: '1961'
  },
  {
   name: 'Alambrista!',
    year: '1977'
  },
  {
   name: 'AlcarrÃ s',
    year: '2022'
  },
  {
   name: 'Ali: Fear Eats the Soul',
    year: '1974'
  },
  {
   name: 'Alice in the Cities',
    year: '1974'
  },
  {
   name: 'All Around Us',
    year: '2008'
  },
  {
   name: 'All Quiet on the Western Front',
    year: '1930'
  },
  {
   name: 'Along with the Gods: The Last 49 Days',
    year: '2018'
  },
  {
   name: 'Along with the Gods: The Two Worlds',
    year: '2017'
  },
  {
   name: 'Alphaville',
    year: '1965'
  },
  {
   name: 'Amarcord',
    year: '1973'
  },
  {
   name: 'Amateur',
    year: '1994'
  },
  {
   name: 'Amen',
    year: '2011'
  },
  {
   name: 'An Actor`s Revenge',
    year: '1963'
  },
  {
   name: 'An American Crime',
    year: '2007'
  },
  {
   name: 'An Angel at My Table',
    year: '1990'
  },
  {
   name: 'An Autumn Afternoon',
    year: '1962'
  },
  {
   name: 'An Elephant Sitting Still',
    year: '2018'
  },
  {
   name: 'An Inn at Osaka',
    year: '1954'
  },
  {
   name: 'Andrei Rublev',
    year: '1966'
  },
  {
   name: 'Angel Dust',
    year: '1994'
  },
  {
   name: 'Angel Guts: Red Vertigo',
    year: '1988'
  },
  {
   name: 'Animal Factory',
    year: '2000'
  },
  {
   name: 'Anomalisa',
    year: '2015'
  },
  {
   name: 'Another Child',
    year: '2019'
  },
  {
   name: 'Anthropoid',
    year: '2016'
  },
  {
   name: 'Antichrist',
    year: '2009'
  },
  {
   name: 'Apart from You',
    year: '1933'
  },
  {
   name: 'April Snow',
    year: '2005'
  },
  {
   name: 'April Story',
    year: '1998'
  },
  {
   name: 'Archive',
    year: '2020'
  },
  {
   name: 'Are You Lonesome Tonight?',
    year: '2021'
  },
  {
   name: 'Art Museum by the Zoo',
    year: '1998'
  },
  {
   name: 'Asako I & II',
    year: '2018'
  },
  {
   name: 'Ash Is Purest White',
    year: '2018'
  },
  {
   name: 'Ashes of Time',
    year: '1994'
  },
  {
   name: 'At Eternity`s Gate',
    year: '2018'
  },
  {
   name: 'Au Revoir les Enfants',
    year: '1987'
  },
  {
   name: 'August in the Water',
    year: '1995'
  },
  {
   name: 'August: Osage County',
    year: '2013'
  },
  {
   name: 'Autumn Days',
    year: '1963'
  },
  {
   name: 'Autumn Sonata',
    year: '1978'
  },
  {
   name: 'Babette`s Feast',
    year: '1987'
  },
  {
   name: 'Babyteeth',
    year: '2019'
  },
  {
   name: 'Bacurau',
    year: '2019'
  },
  {
   name: 'Bad Taste',
    year: '1987'
  },
  {
   name: 'Ballad of Orin',
    year: '1977'
  },
  {
   name: 'Barry Lyndon',
    year: '1975'
  },
  {
   name: 'Basic Instinct',
    year: '1992'
  },
  {
   name: 'Beau Travail',
    year: '1999'
  },
  {
   name: 'Beginners',
    year: '2010'
  },
  {
   name: 'Beginning',
    year: '2020'
  },
  {
   name: 'Behind the Sun',
    year: '2001'
  },
  {
   name: 'Belfast',
    year: '2021'
  },
  {
   name: 'Belladonna of Sadness',
    year: '1973'
  },
  {
   name: 'Belle de Jour',
    year: '1967'
  },
  {
   name: 'Beyond the Dream',
    year: '2019'
  },
  {
   name: 'Big Bullet',
    year: '1996'
  },
  {
   name: 'Big Time Adolescence',
    year: '2019'
  },
  {
   name: 'Birdcage Inn',
    year: '1998'
  },
  {
   name: 'Birth',
    year: '2004'
  },
  {
   name: 'Birthday',
    year: '2019'
  },
  {
   name: 'Bitch on the Beach',
    year: '2016'
  },
  {
   name: 'Black Bear',
    year: '2020'
  },
  {
   name: 'Black Girl',
    year: '1966'
  },
  {
   name: 'Black Hair',
    year: '1964'
  },
  {
   name: 'Black Hawk Down',
    year: '2001'
  },
  {
   name: 'Black River',
    year: '1957'
  },
  {
   name: 'Black Sun',
    year: '1964'
  },
  {
   name: 'Blood Diamond',
    year: '2006'
  },
  {
   name: 'Bloody Muscle Body Builder in Hell',
    year: '1995'
  },
  {
   name: 'Blow-Up',
    year: '1966'
  },
  {
   name: 'Blue',
    year: '2002'
  },
  {
   name: 'Blue Bayou',
    year: '2021'
  },
  {
   name: 'Bluebeard',
    year: '2017'
  },
  {
   name: 'Bo Burnham: Inside',
    year: '2021'
  },
  {
   name: 'Boat People',
    year: '1982'
  },
  {
   name: 'Boiling Point',
    year: '1990'
  },
  {
   name: 'Boiling Point',
    year: '2021'
  },
  {
   name: 'Bones and All',
    year: '2022'
  },
  {
   name: 'Bori',
    year: '2018'
  },
  {
   name: 'Bounce Ko Gals',
    year: '1997'
  },
  {
   name: 'Bound for the Fields, the Mountains, and the Seacoast',
    year: '1986'
  },
  {
   name: 'Boy',
    year: '2010'
  },
  {
   name: 'Boyfriends and Girlfriends',
    year: '1987'
  },
  {
   name: 'Branded to Kill',
    year: '1967'
  },
  {
   name: 'Breaker Morant',
    year: '1980'
  },
  {
   name: 'Breakfast on Pluto',
    year: '2005'
  },
  {
   name: 'Breathless',
    year: '1960'
  },
  {
   name: 'Brick',
    year: '2005'
  },
  {
   name: 'Broken Flowers',
    year: '2005'
  },
  {
   name: 'Bullet Ballet',
    year: '1998'
  },
  {
   name: 'Bullet Train',
    year: '2022'
  },
  {
   name: 'Bullets Over Summer',
    year: '1999'
  },
  {
   name: 'Bumpkin Soup',
    year: '1985'
  },
  {
   name: 'Bungee Jumping of Their Own',
    year: '2001'
  },
  {
   name: 'Bunny Drop',
    year: '2011'
  },
  {
   name: 'Bunt',
    year: '2007'
  },
  {
   name: 'By the Time It Gets Dark',
    year: '2016'
  },
  {
   name: 'CafÃ© LumiÃ¨re',
    year: '2003'
  },
  {
   name: 'Cafe Noir',
    year: '2009'
  },
  {
   name: 'Canoa: A Shameful Memory',
    year: '1976'
  },
  {
   name: 'Caro Diario',
    year: '1993'
  },
  {
   name: 'Cart',
    year: '2014'
  },
  {
   name: 'Cashback',
    year: '2006'
  },
  {
   name: 'Casting Blossoms to the Sky',
    year: '2012'
  },
  {
   name: 'Castle in the Sky',
    year: '1986'
  },
  {
   name: 'Cemetery of Splendor',
    year: '2015'
  },
  {
   name: 'Center Stage',
    year: '1991'
  },
  {
   name: 'Cha Cha Real Smooth',
    year: '2022'
  },
  {
   name: 'Chang-ok`s Letter',
    year: '2017'
  },
  {
   name: 'Charisma',
    year: '1999'
  },
  {
   name: 'Chasing Amy',
    year: '1997'
  },
  {
   name: 'Children of Heaven',
    year: '1997'
  },
  {
   name: 'Children of the Beehive',
    year: '1948'
  },
  {
   name: 'Chilsu and Mansu',
    year: '1988'
  },
  {
   name: 'Chinatown',
    year: '1974'
  },
  {
   name: 'Chizuko`s Younger Sister',
    year: '1991'
  },
  {
   name: 'Chocolat',
    year: '1988'
  },
  {
   name: 'Chunhyang',
    year: '2000'
  },
  {
   name: 'City of Life and Death',
    year: '2009'
  },
  {
   name: 'City of the Rising Sun',
    year: '1999'
  },
  {
   name: 'Cliff Walkers',
    year: '2021'
  },
  {
   name: 'Close',
    year: '2022'
  },
  {
   name: 'Clouds of May',
    year: '1999'
  },
  {
   name: 'Clouds of Sils Maria',
    year: '2014'
  },
  {
   name: 'C`mon C`mon',
    year: '2021'
  },
  {
   name: 'Cold Eyes',
    year: '2013'
  },
  {
   name: 'Come True',
    year: '2020'
  },
  {
   name: 'Contempt',
    year: '1963'
  },
  {
   name: 'Crazed Fruit',
    year: '1956'
  },
  {
   name: 'Crazy Thunder Road',
    year: '1980'
  },
  {
   name: 'Creepy',
    year: '2016'
  },
  {
   name: 'Cries and Whispers',
    year: '1972'
  },
  {
   name: 'Crocodile',
    year: '1996'
  },
  {
   name: 'Crosscurrent',
    year: '2016'
  },
  {
   name: 'Crossroads of Youth',
    year: '1934'
  },
  {
   name: 'Cruel Gun Story',
    year: '1964'
  },
  {
   name: 'Crush and Blush',
    year: '2008'
  },
  {
   name: 'Crying Out Love in the Center of the World',
    year: '2004'
  },
  {
   name: 'Custody',
    year: '2017'
  },
  {
   name: 'Cyrano de Bergerac',
    year: '1990'
  },
  {
   name: 'Da 5 Bloods',
    year: '2020'
  },
  {
   name: 'Daisies',
    year: '1966'
  },
  {
   name: 'Dantza',
    year: '2018'
  },
  {
   name: 'Dangerous Encounters of the First Kind',
    year: '1980'
  },
  {
   name: 'Dark Figure of Crime',
    year: '2018'
  },
  {
   name: 'Darkest Hour',
    year: '2017'
  },
  {
   name: 'Daughter of the Nile',
    year: '1987'
  },
  {
   name: 'Days',
    year: '2020'
  },
  {
   name: 'Dazed and Confused',
    year: '1993'
  },
  {
   name: 'Dead Ringers',
    year: '1988'
  },
  {
   name: 'Dead Snow 2: Red vs. Dead',
    year: '2014'
  },
  {
   name: 'Dear Etranger',
    year: '2017'
  },
  {
   name: 'Dearest',
    year: '2014'
  },
  {
   name: 'Death by Hanging',
    year: '1968'
  },
  {
   name: 'Declaration of Fools',
    year: '1984'
  },
  {
   name: 'Deep Blue Night',
    year: '1985'
  },
  {
   name: 'Deerskin',
    year: '2019'
  },
  {
   name: 'Deliver Us from Evil',
    year: '2020'
  },
  {
   name: 'Dersu Uzala',
    year: '1975'
  },
  {
   name: 'Destroy All Monsters',
    year: '1968'
  },
  {
   name: 'Detroit',
    year: '2017'
  },
  {
   name: 'Diamonds of the Night',
    year: '1964'
  },
  {
   name: 'Die Bad',
    year: '2000'
  },
  {
   name: 'Distant',
    year: '2002'
  },
  {
   name: 'Do the Right Thing',
    year: '1989'
  },
  {
   name: 'Dodes`ka-den',
    year: '1970'
  },
  {
   name: 'Dog',
    year: '2022'
  },
  {
   name: 'Dog Soldiers',
    year: '2002'
  },
  {
   name: 'Dogfight',
    year: '1991'
  },
  {
   name: 'Dolls',
    year: '2002'
  },
  {
   name: 'Dongju: The Portrait of a Poet',
    year: '2016'
  },
  {
   name: 'Don`t Go Breaking My Heart',
    year: '2011'
  },
  {
   name: 'Dooman River',
    year: '2010'
  },
  {
   name: 'Door Lock',
    year: '2018'
  },
  {
   name: 'Double Suicide',
    year: '1969'
  },
  {
   name: 'Doubt',
    year: '2008'
  },
  {
   name: 'Dragged Across Concrete',
    year: '2018'
  },
  {
   name: 'Dragnet Girl',
    year: '1933'
  },
  {
   name: 'Dragons Forever',
    year: '1988'
  },
  {
   name: 'Dream',
    year: '2008'
  },
  {
   name: 'Dreams',
    year: '1990'
  },
  {
   name: 'Dreamy Eyes',
    year: '2019'
  },
  {
   name: 'Drifting',
    year: '2021'
  },
  {
   name: 'Drunken Angel',
    year: '1948'
  },
  {
   name: 'Dual',
    year: '2022'
  },
  {
   name: 'Dwelling in the Fuchun Mountains',
    year: '2019'
  },
  {
   name: 'Dying at a Hospital',
    year: '1993'
  },
  {
   name: 'Early Spring',
    year: '1956'
  },
  {
   name: 'Eating Raoul',
    year: '1982'
  },
  {
   name: 'El Infierno',
    year: '2010'
  },
  {
   name: 'Election',
    year: '1999'
  },
  {
   name: 'Election 2',
    year: '2006'
  },
  {
   name: 'Embrace of the Serpent',
    year: '2015'
  },
  {
   name: 'Enclosed Pain',
    year: '2000'
  },
  {
   name: 'Endless Rain',
    year: '2021'
  },
  {
   name: 'Enter the Void',
    year: '2009'
  },
  {
   name: 'Equilibrium',
    year: '2002'
  },
  {
   name: 'Equinox Flower',
    year: '1958'
  },
  {
   name: 'Eraserhead',
    year: '1977'
  },
  {
   name: 'Eros',
    year: '2004'
  },
  {
   name: 'Eros + Massacre',
    year: '1969'
  },
  {
   name: 'Escape from Mogadishu',
    year: '2021'
  },
  {
   name: 'Eternity and a Day',
    year: '1998'
  },
  {
   name: 'Europe `51',
    year: '1952'
  },
  {
   name: 'Everglow',
    year: '2020'
  },
  {
   name: 'Everybody Wants Some!!',
    year: '2016'
  },
  {
   name: 'Face/Off',
    year: '1997'
  },
  {
   name: 'Family Ties',
    year: '2006'
  },
  {
   name: 'Fanny and Alexander',
    year: '1982'
  },
  {
   name: 'Far from Heaven',
    year: '2002'
  },
  {
   name: 'Fearless',
    year: '2006'
  },
  {
   name: 'February',
    year: '2017'
  },
  {
   name: 'Fences',
    year: '2016'
  },
  {
   name: 'Ferris Bueller`s Day Off',
    year: '1986'
  },
  {
   name: 'Festival',
    year: '1996'
  },
  {
   name: 'First child',
    year: '2021'
  },
  {
   name: 'First Cow',
    year: '2019'
  },
  {
   name: 'First Love',
    year: '2019'
  },
  {
   name: 'First Love',
    year: '2022'
  },
  {
   name: 'First They Killed My Father',
    year: '2017'
  },
  {
   name: 'Fish Story',
    year: '2009'
  },
  {
   name: 'Flame in Valley',
    year: '1967'
  },
  {
   name: 'Fleeing by Night',
    year: '2000'
  },
  {
   name: 'Flickering Lights',
    year: '2000'
  },
  {
   name: 'Flirting Scholar',
    year: '1993'
  },
  {
   name: 'Floating Clouds',
    year: '1955'
  },
  {
   name: 'Floating Weeds',
    year: '1959'
  },
  {
   name: 'Flowers of Shanghai',
    year: '1998'
  },
  {
   name: 'Flowing',
    year: '1956'
  },
  {
   name: 'Fly Me to Polaris',
    year: '1999'
  },
  {
   name: 'Forbidden Dream',
    year: '2019'
  },
  {
   name: 'Forbidden Games',
    year: '1952'
  },
  {
   name: 'Force Majeure',
    year: '2014'
  },
  {
   name: 'Foreign Land',
    year: '1995'
  },
  {
   name: 'Forever the Moment',
    year: '2008'
  },
  {
   name: 'Four Lions',
    year: '2010'
  },
  {
   name: 'Fracture',
    year: '2007'
  },
  {
   name: 'Frank',
    year: '2014'
  },
  {
   name: 'Fresh',
    year: '2022'
  },
  {
   name: 'Friend',
    year: '2001'
  },
  {
   name: 'Friend Zone',
    year: '2019'
  },
  {
   name: 'Friendship`s Death',
    year: '1987'
  },
  {
   name: 'Fruitvale Station',
    year: '2013'
  },
  {
   name: 'Funeral Parade of Roses',
    year: '1969'
  },
  {
   name: 'Gagman',
    year: '1989'
  },
  {
   name: 'Gangubai Kathiawadi',
    year: '2022'
  },
  {
   name: 'Garden State',
    year: '2004'
  },
  {
   name: 'Ghost in the Shell',
    year: '1995'
  },
  {
   name: 'Ghost World',
    year: '2001'
  },
  {
   name: 'Gilsoddeum',
    year: '1986'
  },
  {
   name: 'Ginza Cosmetics',
    year: '1951'
  },
  {
   name: 'Girl',
    year: '2018'
  },
  {
   name: 'Girlhood',
    year: '2014'
  },
  {
   name: 'Girls of the Night',
    year: '1961'
  },
  {
   name: 'Glory to the Filmmaker!',
    year: '2007'
  },
  {
   name: 'Go Go Tales',
    year: '2007'
  },
  {
   name: 'God`s Own Country',
    year: '2017'
  },
  {
   name: 'Going by the Book',
    year: '2007'
  },
  {
   name: 'Gone Baby Gone',
    year: '2007'
  },
  {
   name: 'GONIN',
    year: '1995'
  },
  {
   name: 'Good Bye Lenin!',
    year: '2003'
  },
  {
   name: 'Good Person',
    year: '2020'
  },
  {
   name: 'Good Windy Days',
    year: '1980'
  },
  {
   name: 'Goodnight Mommy',
    year: '2014'
  },
  {
   name: 'Gozu',
    year: '2003'
  },
  {
   name: 'Grass',
    year: '2018'
  },
  {
   name: 'Grave Encounters',
    year: '2011'
  },
  {
   name: 'Graveyard of Honor',
    year: '1975'
  },
  {
   name: 'Graveyard of Honor',
    year: '2002'
  },
  {
   name: 'Great Freedom',
    year: '2021'
  },
  {
   name: 'Green Snake',
    year: '1993'
  },
  {
   name: 'Growing Up',
    year: '1983'
  },
  {
   name: 'Guillermo del Toro`s Pinocchio',
    year: '2022'
  },
  {
   name: 'Gummo',
    year: '1997'
  },
  {
   name: 'Gyeong-ah`s Daughter',
    year: '2022'
  },
  {
   name: 'Gyeongju',
    year: '2014'
  },
  {
   name: 'Ha Ha Ha',
    year: '2010'
  },
  {
   name: 'Hamlet',
    year: '1964'
  },
  {
   name: 'Hana & Alice',
    year: '2004'
  },
  {
   name: 'Hanagatami',
    year: '2017'
  },
  {
   name: 'Hand Rolled Cigarette',
    year: '2020'
  },
  {
   name: 'Hansan: Rising Dragon',
    year: '2022'
  },
  {
   name: 'Happy End',
    year: '1999'
  },
  {
   name: 'Happy Hour',
    year: '2015'
  },
  {
   name: 'Hard Eight',
    year: '1996'
  },
  {
   name: 'Harmful Insect',
    year: '2001'
  },
  {
   name: 'Haru',
    year: '1996'
  },
  {
   name: 'Confession',
    year: '1968'
  },
  {
   name: 'Heaven: To The Land of Happiness',
    year: '2021'
  },
  {
   name: 'Heavenly Creatures',
    year: '1994'
  },
  {
   name: 'Heavenly Forest',
    year: '2006'
  },
  {
   name: 'Heavenly Homecoming to Stars',
    year: '1974'
  },
  {
   name: 'Hello Brother',
    year: '2005'
  },
  {
   name: 'Help',
    year: '2021'
  },
  {
   name: 'Helpless',
    year: '2012'
  },
  {
   name: 'Helter Skelter',
    year: '2012'
  },
  {
   name: 'Her Love Boils Bathwater',
    year: '2016'
  },
  {
   name: 'Hero',
    year: '2002'
  },
  {
   name: 'Hi, Mom!',
    year: '1970'
  },
  {
   name: 'Hi, Mom',
    year: '2021'
  },
  {
   name: 'Hill of Freedom',
    year: '2014'
  },
  {
   name: 'Secret',
    year: '1999'
  },
  {
   name: 'his',
    year: '2020'
  },
  {
   name: 'His Motorbike, Her Island',
    year: '1986'
  },
  {
   name: 'History of the Occult',
    year: '2020'
  },
  {
   name: 'Holiday',
    year: '1938'
  },
  {
   name: 'Holy Spider',
    year: '2022'
  },
  {
   name: 'Home from the Sea',
    year: '1972'
  },
  {
   name: 'Homebound',
    year: '1967'
  },
  {
   name: 'Homeless',
    year: '2020'
  },
  {
   name: 'Hommage',
    year: '2021'
  },
  {
   name: 'Honey Boy',
    year: '2019'
  },
  {
   name: 'Honokaa Boy',
    year: '2009'
  },
  {
   name: 'Horrors of Malformed Men',
    year: '1969'
  },
  {
   name: 'Hotel by the River',
    year: '2018'
  },
  {
   name: 'House of Flying Daggers',
    year: '2004'
  },
  {
   name: 'House of Tolerance',
    year: '2011'
  },
  {
   name: 'Howl`s Moving Castle',
    year: '2004'
  },
  {
   name: 'Hukkle',
    year: '2002'
  },
  {
   name: 'Hunt',
    year: '2022'
  },
  {
   name: 'Hush!',
    year: '2001'
  },
  {
   name: 'Hymn of Death',
    year: '2018'
  },
  {
   name: 'I Am a Hero',
    year: '2015'
  },
  {
   name: 'I Am Home',
    year: '2019'
  },
  {
   name: 'A Beautiful Day in the Neighborhood',
    year: '2019'
  },
  {
   name: 'I Donâ€™t Fire Myself',
    year: '2020'
  },
  {
   name: 'I Just Didn`t Do It',
    year: '2007'
  },
  {
   name: 'I Killed My Mother',
    year: '2009'
  },
  {
   name: 'I Knew Her Well',
    year: '1965'
  },
  {
   name: 'I Origins',
    year: '2014'
  },
  {
   name: 'I Want to Know Your Parents',
    year: '2022'
  },
  {
   name: 'The Day I Was Not Born',
    year: '2010'
  },
  {
   name: 'I Wish',
    year: '2011'
  },
  {
   name: 'I Wish I Knew',
    year: '2010'
  },
  {
   name: 'Il Posto',
    year: '1961'
  },
  {
   name: 'I`m Thinking of Ending Things',
    year: '2020'
  },
  {
   name: 'Imagine Me & You',
    year: '2005'
  },
  {
   name: 'Impetigore',
    year: '2019'
  },
  {
   name: 'In Our Prime',
    year: '2022'
  },
  {
   name: 'In Our Time',
    year: '1982'
  },
  {
   name: 'In the Heat of the Sun',
    year: '1994'
  },
  {
   name: 'In the Mouth of the Wolf',
    year: '1988'
  },
  {
   name: 'Lightning',
    year: '1952'
  },
  {
   name: 'Indiana Jones and the Last Crusade',
    year: '1989'
  },
  {
   name: 'Infernal Affairs II',
    year: '2003'
  },
  {
   name: 'Infernal Affairs III',
    year: '2003'
  },
  {
   name: 'Inherent Vice',
    year: '2014'
  },
  {
   name: 'Inland Empire',
    year: '2006'
  },
  {
   name: 'Inseparable Bros',
    year: '2019'
  },
  {
   name: 'Insiang',
    year: '1976'
  },
  {
   name: 'Inside Men',
    year: '2015'
  },
  {
   name: 'Intimacies',
    year: '2012'
  },
  {
   name: 'Introduction',
    year: '2021'
  },
  {
   name: 'Io Island',
    year: '1977'
  },
  {
   name: 'Ip Man',
    year: '2008'
  },
  {
   name: 'Irezumi',
    year: '1966'
  },
  {
   name: 'Isle of Dogs',
    year: '2018'
  },
  {
   name: 'Isolation',
    year: '2005'
  },
  {
   name: 'It`s a Summer Film!',
    year: '2020'
  },
  {
   name: 'It All Starts Today',
    year: '1999'
  },
  {
   name: 'It Comes at Night',
    year: '2017'
  },
  {
   name: 'It`s Boring Here, Pick Me Up',
    year: '2018'
  },
  {
   name: 'Jacquot',
    year: '1991'
  },
  {
   name: 'Jagko',
    year: '1980'
  },
  {
   name: 'Jerry Maguire',
    year: '1996'
  },
  {
   name: 'Jesse James',
    year: '1939'
  },
  {
   name: 'Jigarthanda',
    year: '2014'
  },
  {
   name: 'Jiseul',
    year: '2012'
  },
  {
   name: 'John Q',
    year: '2002'
  },
  {
   name: 'Journey From the Fall',
    year: '2006'
  },
  {
   name: 'Journey to Italy',
    year: '1954'
  },
  {
   name: 'Jules and Jim',
    year: '1962'
  },
  {
   name: 'July Rhapsody',
    year: '2002'
  },
  {
   name: 'Ju-on: The Grudge',
    year: '2002'
  },
  {
   name: 'Kadhalum Kadanthu Pogum',
    year: '2016'
  },
  {
   name: 'Kagemusha',
    year: '1980'
  },
  {
   name: 'Kaithi',
    year: '2019'
  },
  {
   name: 'Kajillionaire',
    year: '2020'
  },
  {
   name: 'Kamikaze Taxi',
    year: '1995'
  },
  {
   name: 'Keys to the Heart',
    year: '2018'
  },
  {
   name: 'Kids',
    year: '1995'
  },
  {
   name: 'Kids Return',
    year: '1996'
  },
  {
   name: 'Kill Your Darlings',
    year: '2013'
  },
  {
   name: 'Kim Min-young of the Report Card',
    year: '2021'
  },
  {
   name: 'Kim-Gun',
    year: '2018'
  },
  {
   name: 'King and the Clown',
    year: '2005'
  },
  {
   name: 'King of Comedy',
    year: '1999'
  },
  {
   name: 'King of New York',
    year: '1990'
  },
  {
   name: 'Kingmaker',
    year: '2022'
  },
  {
   name: 'Kinship',
    year: '1963'
  },
  {
   name: 'Kiss Kiss Bang Bang',
    year: '2005'
  },
  {
   name: 'Knife in the Water',
    year: '1962'
  },
  {
   name: 'Knock at the Cabin',
    year: '2023'
  },
  {
   name: 'Kramer vs. Kramer',
    year: '1979'
  },
  {
   name: 'La Belle Noiseuse',
    year: '1991'
  },
  {
   name: 'La CiÃ©naga',
    year: '2001'
  },
  {
   name: 'La Collectionneuse',
    year: '1967'
  },
  {
   name: 'La Dolce Vita',
    year: '1960'
  },
  {
   name: 'La Notte',
    year: '1961'
  },
  {
   name: 'Labyrinth of Cinema',
    year: '2019'
  },
  {
   name: 'Labyrinth of Dreams',
    year: '1997'
  },
  {
   name: 'Lady Macbeth',
    year: '2016'
  },
  {
   name: 'Lady Snowblood',
    year: '1973'
  },
  {
   name: 'Landscape in the Mist',
    year: '1988'
  },
  {
   name: 'L`Argent',
    year: '1983'
  },
  {
   name: 'Last Child',
    year: '2017'
  },
  {
   name: 'Last Letter',
    year: '2020'
  },
  {
   name: 'Late Autumn',
    year: '1960'
  },
  {
   name: 'Late Autumn',
    year: '2010'
  },
  {
   name: 'Late Bloomer',
    year: '2004'
  },
  {
   name: 'Late Chrysanthemums',
    year: '1954'
  },
  {
   name: 'L`Avventura',
    year: '1960'
  },
  {
   name: 'Le Doulos',
    year: '1962'
  },
  {
   name: 'L`Eclisse',
    year: '1962'
  },
  {
   name: 'Left Luggage',
    year: '1998'
  },
  {
   name: 'Letters from Kanai Nirai',
    year: '2005'
  },
  {
   name: 'License to Live',
    year: '1998'
  },
  {
   name: 'Life Is Beautiful',
    year: '2022'
  },
  {
   name: 'Life of Hae-oak',
    year: '2021'
  },
  {
   name: 'Lighting Up the Stars',
    year: '2022'
  },
  {
   name: 'Like Someone in Love',
    year: '2012'
  },
  {
   name: 'Like You Know It All',
    year: '2009'
  },
  {
   name: 'Limbo',
    year: '2020'
  },
  {
   name: 'Little Fish',
    year: '2020'
  },
  {
   name: 'Loft',
    year: '2005'
  },
  {
   name: 'Miss Lonely',
    year: '1985'
  },
  {
   name: 'Long Arm of the Law',
    year: '1984'
  },
  {
   name: 'Long Day`s Journey Into Night',
    year: '2018'
  },
  {
   name: 'Lost and Found',
    year: '1996'
  },
  {
   name: 'Lost in the Mountains',
    year: '2009'
  },
  {
   name: 'Lost in Time',
    year: '2003'
  },
  {
   name: 'Love & Pop',
    year: '1998'
  },
  {
   name: 'Love',
    year: '2015'
  },
  {
   name: 'Love at the End of the World',
    year: '2015'
  },
  {
   name: 'Love for All Seasons',
    year: '2003'
  },
  {
   name: 'Love in the Afternoon',
    year: '1957'
  },
  {
   name: 'Love in the Afternoon',
    year: '1972'
  },
  {
   name: 'Love Letter',
    year: '1953'
  },
  {
   name: 'Love Liza',
    year: '2002'
  },
  {
   name: 'Love Me If You Dare',
    year: '2003'
  },
  {
   name: 'Love Me Once Again',
    year: '1968'
  },
  {
   name: 'Love of Siam',
    year: '2007'
  },
  {
   name: 'Love Stories From Fukuoka 14: Tenjin Love Song',
    year: '2019'
  },
  {
   name: 'Love Under the Crucifix',
    year: '1962'
  },
  {
   name: 'Love Unto Wastes',
    year: '1986'
  },
  {
   name: 'Love Will Tear Us Apart',
    year: '2021'
  },
  {
   name: 'Loving You',
    year: '1995'
  },
  {
   name: 'Lucky',
    year: '2017'
  },
  {
   name: 'Lunana: A Yak in the Classroom',
    year: '2019'
  },
  {
   name: 'Lupin the Third: The Castle of Cagliostro',
    year: '1979'
  },
  {
   name: 'M/Other',
    year: '1999'
  },
  {
   name: 'Ma Rainey`s Black Bottom',
    year: '2020'
  },
  {
   name: 'Mad God',
    year: '2021'
  },
  {
   name: 'Madame Freedom',
    year: '1956'
  },
  {
   name: 'Maheshinte Prathikaaram',
    year: '2016'
  },
  {
   name: 'Mammoth',
    year: '2009'
  },
  {
   name: 'Man in Love',
    year: '2021'
  },
  {
   name: 'Mandala',
    year: '1981'
  },
  {
   name: 'Manticore',
    year: '2022'
  },
  {
   name: 'March Comes in Like a Lion',
    year: '1991'
  },
  {
   name: 'Marriage Story',
    year: '1992'
  },
  {
   name: 'Martin',
    year: '1976'
  },
  {
   name: 'Mass',
    year: '2021'
  },
  {
   name: 'Matchstick Men',
    year: '2003'
  },
  {
   name: 'May God Save Us',
    year: '2016'
  },
  {
   name: 'may-18',
    year: '2007'
  },
  {
   name: 'Meet the Feebles',
    year: '1989'
  },
  {
   name: 'Memento Mori',
    year: '1999'
  },
  {
   name: 'Memoria',
    year: '2021'
  },
  {
   name: 'Memories of Matsuko',
    year: '2006'
  },
  {
   name: 'Merry Christmas Mr. Mo',
    year: '2016'
  },
  {
   name: 'Method',
    year: '2017'
  },
  {
   name: 'Micmacs',
    year: '2009'
  },
  {
   name: 'Midnight',
    year: '1939'
  },
  {
   name: 'Midnight Swan',
    year: '2020'
  },
  {
   name: 'Mikey and Nicky',
    year: '1976'
  },
  {
   name: 'Mirror',
    year: '1975'
  },
  {
   name: 'Mirrored Mind',
    year: '2005'
  },
  {
   name: 'Miss Oyu',
    year: '1951'
  },
  {
   name: 'Missing You',
    year: '2016'
  },
  {
   name: 'Mist',
    year: '1967'
  },
  {
   name: 'Mistress America',
    year: '2015'
  },
  {
   name: 'Modern Family',
    year: '2012'
  },
  {
   name: 'Monday',
    year: '2000'
  },
  {
   name: 'Moneyball',
    year: '2011'
  },
  {
   name: 'Moneyboys',
    year: '2021'
  },
  {
   name: 'Montage',
    year: '2013'
  },
  {
   name: 'Moon of Avellaneda',
    year: '2004'
  },
  {
   name: 'Moonlight Whispers',
    year: '1999'
  },
  {
   name: 'Moonrise Kingdom',
    year: '2012'
  },
  {
   name: 'Mother',
    year: '1952'
  },
  {
   name: 'MOTHER',
    year: '2020'
  },
  {
   name: 'Mountain Patrol',
    year: '2004'
  },
  {
   name: 'Mr. Long',
    year: '2017'
  },
  {
   name: 'Mr. Park',
    year: '1960'
  },
  {
   name: 'Muddy River',
    year: '1981'
  },
  {
   name: 'Munich',
    year: '2005'
  },
  {
   name: 'Mustang',
    year: '2015'
  },
  {
   name: 'My Annoying Brother',
    year: '2016'
  },
  {
   name: 'My Beautiful Days',
    year: '2002'
  },
  {
   name: 'My Dear Enemy',
    year: '2008'
  },
  {
   name: 'My Fair Lady',
    year: '1964'
  },
  {
   name: 'My First Client',
    year: '2019'
  },
  {
   name: 'My Girl',
    year: '2003'
  },
  {
   name: 'My Life as a Zucchini',
    year: '2016'
  },
  {
   name: 'My Lovely Angel',
    year: '2021'
  },
  {
   name: 'My Mother and Her Guest',
    year: '1961'
  },
  {
   name: 'My Own Private Idaho',
    year: '1991'
  },
  {
   name: 'My Perfect Roommate',
    year: '2022'
  },
  {
   name: 'My Way',
    year: '2011'
  },
  {
   name: 'Mysterious Object at Noon',
    year: '2000'
  },
  {
   name: 'Mystery Train',
    year: '1989'
  },
  {
   name: 'Naked Paradise',
    year: '2002'
  },
  {
   name: 'Nameless Gangster',
    year: '2012'
  },
  {
   name: 'Napoleon Dynamite',
    year: '2004'
  },
  {
   name: 'Network',
    year: '1976'
  },
  {
   name: 'New Rose Hotel',
    year: '1998'
  },
  {
   name: 'Nice View',
    year: '2022'
  },
  {
   name: 'Night and Day',
    year: '2008'
  },
  {
   name: 'Night on Earth',
    year: '1991'
  },
  {
   name: 'Nine Days',
    year: '2020'
  },
  {
   name: 'No Sudden Move',
    year: '2021'
  },
  {
   name: 'No. 3',
    year: '1997'
  },
  {
   name: 'Nobody`s Daughter Haewon',
    year: '2013'
  },
  {
   name: 'Nocturama',
    year: '2016'
  },
  {
   name: 'Noroi: The Curse',
    year: '2005'
  },
  {
   name: 'North Korean Partisan in South Korea',
    year: '1990'
  },
  {
   name: 'Not One Less',
    year: '1999'
  },
  {
   name: 'NOT OUT',
    year: '2021'
  },
  {
   name: 'November',
    year: '2017'
  },
  {
   name: 'Nowhere',
    year: '1997'
  },
  {
   name: 'Nowhere to Hide',
    year: '1999'
  },
  {
   name: 'Nymphomaniac: Vol. I',
    year: '2013'
  },
  {
   name: 'Ode To My Father',
    year: '2014'
  },
  {
   name: 'Ode to the Goose',
    year: '2018'
  },
  {
   name: 'Office Space',
    year: '1999'
  },
  {
   name: 'Official Secrets',
    year: '2019'
  },
  {
   name: 'Oki`s Movie',
    year: '2010'
  },
  {
   name: 'Old Days',
    year: '2016'
  },
  {
   name: 'Brother and Sister',
    year: '1953'
  },
  {
   name: 'On Body and Soul',
    year: '2017'
  },
  {
   name: 'On the Run',
    year: '1988'
  },
  {
   name: 'On the Silver Globe',
    year: '1988'
  },
  {
   name: 'Once in a Summer',
    year: '2006'
  },
  {
   name: 'Once Upon a Time... This Morning',
    year: '1994'
  },
  {
   name: 'One Day We`ll Talk About Today',
    year: '2020'
  },
  {
   name: 'One for the Road',
    year: '2021'
  },
  {
   name: 'One Hour Photo',
    year: '2002'
  },
  {
   name: 'One Million Yen Girl',
    year: '2008'
  },
  {
   name: 'One Night in Miami...',
    year: '2020'
  },
  {
   name: 'One Nite in Mongkok',
    year: '2004'
  },
  {
   name: 'One Second',
    year: '2020'
  },
  {
   name: 'Only Angels Have Wings',
    year: '1939'
  },
  {
   name: 'Only Lovers Left Alive',
    year: '2013'
  },
  {
   name: 'Only Yesterday',
    year: '1991'
  },
  {
   name: 'Ordet',
    year: '1955'
  },
  {
   name: 'Our Body',
    year: '2018'
  },
  {
   name: 'Our Love Story',
    year: '2016'
  },
  {
   name: 'Our Sunhi',
    year: '2013'
  },
  {
   name: 'Our Twisted Hero',
    year: '1992'
  },
  {
   name: 'Over the Rainbow',
    year: '2002'
  },
  {
   name: 'Pacchigi!',
    year: '2005'
  },
  {
   name: 'Painted Fire',
    year: '2002'
  },
  {
   name: 'Paju',
    year: '2009'
  },
  {
   name: 'Pale Flower',
    year: '1964'
  },
  {
   name: 'Paradox',
    year: '2017'
  },
  {
   name: 'Pariah',
    year: '2011'
  },
  {
   name: 'Pastoral: To Die in the Country',
    year: '1974'
  },
  {
   name: 'Paths of Glory',
    year: '1957'
  },
  {
   name: 'Pauline at the Beach',
    year: '1983'
  },
  {
   name: 'Pearl',
    year: '2022'
  },
  {
   name: 'People in the Slum',
    year: '1982'
  },
  {
   name: 'Perfect Number',
    year: '2012'
  },
  {
   name: 'Persepolis',
    year: '2007'
  },
  {
   name: 'Persona',
    year: '2019'
  },
  {
   name: 'Petal Dance',
    year: '2013'
  },
  {
   name: 'Phoenix',
    year: '2014'
  },
  {
   name: 'Piagol',
    year: '1955'
  },
  {
   name: 'Pickpocket',
    year: '1997'
  },
  {
   name: 'Picnic',
    year: '1996'
  },
  {
   name: 'Pierrot le Fou',
    year: '1965'
  },
  {
   name: 'Pig',
    year: '2021'
  },
  {
   name: 'Pigs and Battleships',
    year: '1961'
  },
  {
   name: 'Pleasantville',
    year: '1998'
  },
  {
   name: 'Please Don`t Save Me',
    year: '2020'
  },
  {
   name: 'Police Story 3: Super Cop',
    year: '1992'
  },
  {
   name: 'Polyester',
    year: '1981'
  },
  {
   name: 'Ponette',
    year: '1996'
  },
  {
   name: 'Popstar: Never Stop Never Stopping',
    year: '2016'
  },
  {
   name: 'Populaire',
    year: '2012'
  },
  {
   name: 'Possessor',
    year: '2020'
  },
  {
   name: 'Possible Faces',
    year: '2017'
  },
  {
   name: 'Possum',
    year: '2018'
  },
  {
   name: 'Postman Blues',
    year: '1997'
  },
  {
   name: 'Princess Mononoke',
    year: '1997'
  },
  {
   name: 'Profound Desires of the Gods',
    year: '1968'
  },
  {
   name: 'ProtÃ©gÃ©',
    year: '2007'
  },
  {
   name: 'Psych 2: Lassie Come Home',
    year: '2020'
  },
  {
   name: 'Public Enemy',
    year: '2002'
  },
  {
   name: 'Pure',
    year: '2009'
  },
  {
   name: 'Pushing Hands',
    year: '1991'
  },
  {
   name: 'Puss in Boots: The Last Wish',
    year: '2022'
  },
  {
   name: 'Quartet for Two',
    year: '2001'
  },
  {
   name: 'R100',
    year: '2013'
  },
  {
   name: 'Rab Ne Bana Di Jodi',
    year: '2008'
  },
  {
   name: 'Rage',
    year: '2016'
  },
  {
   name: 'Raigyo',
    year: '1997'
  },
  {
   name: 'Rainy Days',
    year: '1979'
  },
  {
   name: 'Rashomon',
    year: '1950'
  },
  {
   name: 'Ratcatcher',
    year: '1999'
  },
  {
   name: 'Read My Lips',
    year: '2001'
  },
  {
   name: 'Real Life',
    year: '1979'
  },
  {
   name: 'Rebels of the Neon God',
    year: '1992'
  },
  {
   name: 'Recep Ivedik',
    year: '2008'
  },
  {
   name: 'Record of a Tenement Gentleman',
    year: '1947'
  },
  {
   name: 'Red Angel',
    year: '1966'
  },
  {
   name: 'Red Beard',
    year: '1965'
  },
  {
   name: 'Red Post on Escher Street',
    year: '2020'
  },
  {
   name: 'Redline',
    year: '2009'
  },
  {
   name: 'Remember',
    year: '2015'
  },
  {
   name: 'Repast',
    year: '1951'
  },
  {
   name: 'Repatriation',
    year: '2003'
  },
  {
   name: 'Repo Man',
    year: '1984'
  },
  {
   name: 'Rififi',
    year: '1955'
  },
  {
   name: 'Aziz Ansari: Right Now',
    year: '2019'
  },
  {
   name: 'Romance Papa',
    year: '1960'
  },
  {
   name: 'Rouge',
    year: '1987'
  },
  {
   name: 'Sad Movie',
    year: '2005'
  },
  {
   name: 'SalÃ², or the 120 Days of Sodom',
    year: '1975'
  },
  {
   name: 'Samurai Rebellion',
    year: '1967'
  },
  {
   name: 'Sansho the Bailiff',
    year: '1954'
  },
  {
   name: 'Satan`s Slaves',
    year: '2017'
  },
  {
   name: 'Saturday Fiction',
    year: '2019'
  },
  {
   name: 'Saving Face',
    year: '2004'
  },
  {
   name: 'Scarlet Street',
    year: '1945'
  },
  {
   name: 'Scattered Night',
    year: '2019'
  },
  {
   name: 'School on Fire',
    year: '1988'
  },
  {
   name: 'Seconds',
    year: '1966'
  },
  {
   name: 'Seong Chun-hyang',
    year: '1961'
  },
  {
   name: 'Seoul Station',
    year: '2016'
  },
  {
   name: 'Session 9',
    year: '2001'
  },
  {
   name: 'Seven Weeks',
    year: '2014'
  },
  {
   name: 'Sewing Sisters',
    year: '2020'
  },
  {
   name: 'Shades of the Heart',
    year: '2019'
  },
  {
   name: 'Shame',
    year: '1968'
  },
  {
   name: 'Shanghai Blues',
    year: '1984'
  },
  {
   name: 'Sharing',
    year: '2014'
  },
  {
   name: 'Shin Godzilla',
    year: '2016'
  },
  {
   name: 'Shiri',
    year: '1999'
  },
  {
   name: 'Shirley',
    year: '2020'
  },
  {
   name: 'Shooting Stars',
    year: '1928'
  },
  {
   name: 'Short Eyes',
    year: '1977'
  },
  {
   name: 'Short Vacation',
    year: '2020'
  },
  {
   name: 'Shotgun Stories',
    year: '2007'
  },
  {
   name: 'Show Me Love',
    year: '1998'
  },
  {
   name: 'Sideways',
    year: '2004'
  },
  {
   name: 'Silmido',
    year: '2003'
  },
  {
   name: 'Sinkhole',
    year: '2021'
  },
  {
   name: 'Skeletons in the Closet',
    year: '2007'
  },
  {
   name: 'Sleepless Night',
    year: '2012'
  },
  {
   name: 'Sleuth',
    year: '1972'
  },
  {
   name: 'Snowy Road',
    year: '2017'
  },
  {
   name: 'Someone Special',
    year: '2004'
  },
  {
   name: 'Song of the Exile',
    year: '1990'
  },
  {
   name: 'Song Without a Name',
    year: '2019'
  },
  {
   name: 'Sopyonje',
    year: '1993'
  },
  {
   name: 'Sorry Apple',
    year: '2005'
  },
  {
   name: 'Sorry to Bother You',
    year: '2018'
  },
  {
   name: 'Sorry We Missed You',
    year: '2019'
  },
  {
   name: 'Sorum',
    year: '2001'
  },
  {
   name: 'Sound of the Mountain',
    year: '1954'
  },
  {
   name: 'Southland Tales',
    year: '2006'
  },
  {
   name: 'Special Delivery',
    year: '2022'
  },
  {
   name: 'Spinning the Tales of Cruelty Towards Women',
    year: '1984'
  },
  {
   name: 'Spiritwalker',
    year: '2020'
  },
  {
   name: 'Spring',
    year: '2014'
  },
  {
   name: 'Stalag 17',
    year: '1953'
  },
  {
   name: 'Stand and Deliver',
    year: '1988'
  },
  {
   name: 'Still Life',
    year: '2006'
  },
  {
   name: 'Stingray Sam',
    year: '2009'
  },
  {
   name: 'Straight Outta Compton',
    year: '2015'
  },
  {
   name: 'Straw Dogs',
    year: '1971'
  },
  {
   name: 'Strawberry Shortcakes',
    year: '2006'
  },
  {
   name: 'Stray Dog',
    year: '1949'
  },
  {
   name: 'Stray Dogs',
    year: '2013'
  },
  {
   name: 'Street of Shame',
    year: '1956'
  },
  {
   name: 'Streets of Fire',
    year: '1984'
  },
  {
   name: 'Stromboli',
    year: '1950'
  },
  {
   name: 'Succession',
    year: '1992'
  },
  {
   name: 'Sudden Rain',
    year: '1956'
  },
  {
   name: 'Suddenly in the Dark',
    year: '1981'
  },
  {
   name: 'Suicide Club',
    year: '2001'
  },
  {
   name: 'Su-ki-da',
    year: '2005'
  },
  {
   name: 'Summer Snow',
    year: '1995'
  },
  {
   name: 'Summerland',
    year: '2020'
  },
  {
   name: 'Sunflower',
    year: '2006'
  },
  {
   name: 'Suntan',
    year: '2016'
  },
  {
   name: 'Super Citizen Ko',
    year: '1995'
  },
  {
   name: 'Surviving Desire',
    year: '1992'
  },
  {
   name: 'Suzaku',
    year: '1997'
  },
  {
   name: 'Suzhou River',
    year: '2000'
  },
  {
   name: 'Swallowtail Butterfly',
    year: '1996'
  },
  {
   name: 'Sweet Bean',
    year: '2015'
  },
  {
   name: 'Sweet Smell of Success',
    year: '1957'
  },
  {
   name: 'Swing Girls',
    year: '2004'
  },
  {
   name: 'Symbol',
    year: '2009'
  },
  {
   name: 'Sympathy for the Underdog',
    year: '1971'
  },
  {
   name: 'TÃR',
    year: '2022'
  },
  {
   name: 'Taipei Suicide Story',
    year: '2020'
  },
  {
   name: 'Take My Eyes',
    year: '2003'
  },
  {
   name: 'Take Out',
    year: '2004'
  },
  {
   name: 'Take Shelter',
    year: '2011'
  },
  {
   name: 'Tale of Cinema',
    year: '2005'
  },
  {
   name: 'Taxidermia',
    year: '2006'
  },
  {
   name: 'Tazza: The High Rollers',
    year: '2006'
  },
  {
   name: 'Tell Me Something',
    year: '1999'
  },
  {
   name: 'Tempting Heart',
    year: '1999'
  },
  {
   name: 'Ten Months',
    year: '2020'
  },
  {
   name: 'Terrifier 2',
    year: '2022'
  },
  {
   name: 'Terrorizers',
    year: '1986'
  },
  {
   name: 'That Day',
    year: '2003'
  },
  {
   name: 'That Thing You Do!',
    year: '1996'
  },
  {
   name: 'The 8 Diagram Pole Fighter',
    year: '1984'
  },
  {
   name: 'The Abyss',
    year: '1989'
  },
  {
   name: 'The Admiral: Roaring Currents',
    year: '2014'
  },
  {
   name: 'The African Queen',
    year: '1951'
  },
  {
   name: 'The Age of Adaline',
    year: '2015'
  },
  {
   name: 'The Age of Shadows',
    year: '2016'
  },
  {
   name: 'The American Astronaut',
    year: '2001'
  },
  {
   name: 'The Animatrix',
    year: '2003'
  },
  {
   name: 'The Apartment with Two Women',
    year: '2021'
  },
  {
   name: 'The Art of Self-Defense',
    year: '2019'
  },
  {
   name: 'The Ascent',
    year: '1977'
  },
  {
   name: 'The Assassination of Jesse James by the Coward Robert Ford',
    year: '2007'
  },
  {
   name: 'The Assistant',
    year: '2019'
  },
  {
   name: 'The Aura',
    year: '2005'
  },
  {
   name: 'The Aviator`s Wife',
    year: '1981'
  },
  {
   name: 'The Bacchus Lady',
    year: '2016'
  },
  {
   name: 'The Bad Sleep Well',
    year: '1960'
  },
  {
   name: 'The Ballad of Buster Scruggs',
    year: '2018'
  },
  {
   name: 'The Ballad of Narayama',
    year: '1958'
  },
  {
   name: 'The Ballad of Narayama',
    year: '1983'
  },
  {
   name: 'The Bare-Footed Kid',
    year: '1993'
  },
  {
   name: 'The Barefooted Young',
    year: '1964'
  },
  {
   name: 'The Beast',
    year: '2019'
  },
  {
   name: 'The Beasts',
    year: '2022'
  },
  {
   name: 'The Believer',
    year: '2001'
  },
  {
   name: 'The Bird People in China',
    year: '1998'
  },
  {
   name: 'The Black Republic',
    year: '1990'
  },
  {
   name: 'The Blue Sky Maiden',
    year: '1957'
  },
  {
   name: 'The Bone Collector',
    year: '1999'
  },
  {
   name: 'The Book of Fish',
    year: '2021'
  },
  {
   name: 'The Bridge',
    year: '1959'
  },
  {
   name: 'The Broken Circle Breakdown',
    year: '2012'
  },
  {
   name: 'The Burmese Harp',
    year: '1956'
  },
  {
   name: 'The Changeling',
    year: '1980'
  },
  {
   name: 'The Chase',
    year: '2017'
  },
  {
   name: 'The Cherry Orchard',
    year: '1990'
  },
  {
   name: 'The Child',
    year: '2005'
  },
  {
   name: 'The Children`s Hour',
    year: '1961'
  },
  {
   name: 'The Church',
    year: '1989'
  },
  {
   name: 'The City of Violence',
    year: '2006'
  },
  {
   name: 'The Cloud in Her Room',
    year: '2020'
  },
  {
   name: 'The Coachman',
    year: '1961'
  },
  {
   name: 'The Color of Pomegranates',
    year: '1969'
  },
  {
   name: 'The Company of Strangers',
    year: '1990'
  },
  {
   name: 'The Conformist',
    year: '1970'
  },
  {
   name: 'The Contact',
    year: '1997'
  },
  {
   name: 'The Conversation',
    year: '1974'
  },
  {
   name: 'Spun',
    year: '2002'
  },
  {
   name: 'The Crucified Lovers',
    year: '1954'
  },
  {
   name: 'The Daughters of Kim`s Pharmacy',
    year: '1963'
  },
  {
   name: 'The Day After',
    year: '2017'
  },
  {
   name: 'The Day the Earth Caught Fire',
    year: '1961'
  },
  {
   name: 'The Day Will Come',
    year: '2016'
  },
  {
   name: 'The Death of Mr. Lazarescu',
    year: '2005'
  },
  {
   name: 'The Devil`s Backbone',
    year: '2001'
  },
  {
   name: 'The Devil`s Stairway',
    year: '1964'
  },
  {
   name: 'The Discarnates',
    year: '1988'
  },
  {
   name: 'The Distinguished Citizen',
    year: '2016'
  },
  {
   name: 'The DMZ',
    year: '1965'
  },
  {
   name: 'The Double',
    year: '2013'
  },
  {
   name: 'The Double Life of VÃ©ronique',
    year: '1991'
  },
  {
   name: 'The Drug King',
    year: '2018'
  },
  {
   name: 'The Elephant Man',
    year: '1980'
  },
  {
   name: 'The Exorcist III',
    year: '1990'
  },
  {
   name: 'The Fabelmans',
    year: '2022'
  },
  {
   name: 'The Face of Another',
    year: '1966'
  },
  {
   name: 'The Face of Jizo',
    year: '2004'
  },
  {
   name: 'The Falls',
    year: '2021'
  },
  {
   name: 'The Fearless Vampire Killers',
    year: '1967'
  },
  {
   name: 'The First Lap',
    year: '2017'
  },
  {
   name: 'The Five',
    year: '2013'
  },
  {
   name: 'The Flavor of Green Tea Over Rice',
    year: '1952'
  },
  {
   name: 'The Flower in Hell',
    year: '1958'
  },
  {
   name: 'The Fog',
    year: '1980'
  },
  {
   name: 'The Forest of Love: Deep Cut',
    year: '2020'
  },
  {
   name: 'The Fortress',
    year: '2017'
  },
  {
   name: 'The Friends',
    year: '1994'
  },
  {
   name: 'The Front Line',
    year: '2011'
  },
  {
   name: 'The Front Page',
    year: '1974'
  },
  {
   name: 'The Funeral',
    year: '1996'
  },
  {
   name: 'The Fury of a Patient Man',
    year: '2016'
  },
  {
   name: 'The General`s Mustache',
    year: '1968'
  },
  {
   name: 'The Girl on a Bulldozer',
    year: '2022'
  },
  {
   name: 'The Great Buddha+',
    year: '2017'
  },
  {
   name: 'The Great Passage',
    year: '2013'
  },
  {
   name: 'The Green Ray',
    year: '1986'
  },
  {
   name: 'The Grifters',
    year: '1990'
  },
  {
   name: 'The Hand',
    year: '2020'
  },
  {
   name: 'The Hand of Destiny',
    year: '1954'
  },
  {
   name: 'The Hand of God',
    year: '2021'
  },
  {
   name: 'The Harmonium in My Memory',
    year: '1999'
  },
  {
   name: 'The Heartbreak Kid',
    year: '1972'
  },
  {
   name: 'The Hole',
    year: '1998'
  },
  {
   name: 'The Holy Inquisition',
    year: '1974'
  },
  {
   name: 'The House of Us',
    year: '2019'
  },
  {
   name: 'The Hudsucker Proxy',
    year: '1994'
  },
  {
   name: 'The Human Condition I: No Greater Love',
    year: '1959'
  },
  {
   name: 'The Human Condition II: Road to Eternity',
    year: '1959'
  },
  {
   name: 'The Human Condition III: A Soldier`s Prayer',
    year: '1961'
  },
  {
   name: 'The Hurt Locker',
    year: '2008'
  },
  {
   name: 'The Hut',
    year: '1981'
  },
  {
   name: 'The Idiot',
    year: '1951'
  },
  {
   name: 'The Innocents',
    year: '2021'
  },
  {
   name: 'The Insect Woman',
    year: '1963'
  },
  {
   name: 'The Island',
    year: '2006'
  },
  {
   name: 'The Kid Detective',
    year: '2020'
  },
  {
   name: 'The King',
    year: '2017'
  },
  {
   name: 'The King of Masks',
    year: '1995'
  },
  {
   name: 'The King of Staten Island',
    year: '2020'
  },
  {
   name: 'The Last Boy Scout',
    year: '1991'
  },
  {
   name: 'The Last Duel',
    year: '2021'
  },
  {
   name: 'The Last Princess',
    year: '2016'
  },
  {
   name: 'The Last Stage',
    year: '1948'
  },
  {
   name: 'The Last Witness',
    year: '1980'
  },
  {
   name: 'The Legend of Drunken Master',
    year: '1994'
  },
  {
   name: 'The Life of Oharu',
    year: '1952'
  },
  {
   name: 'The Long Excuse',
    year: '2016'
  },
  {
   name: 'The Longest Nite',
    year: '1998'
  },
  {
   name: 'The Lost Daughter',
    year: '2021'
  },
  {
   name: 'The Lost Weekend',
    year: '1945'
  },
  {
   name: 'The Magic Hour',
    year: '2008'
  },
  {
   name: 'The Maltese Falcon',
    year: '1941'
  },
  {
   name: 'The Man Standing Next',
    year: '2020'
  },
  {
   name: 'The Man with Three Coffins',
    year: '1987'
  },
  {
   name: 'The March of Fools',
    year: '1975'
  },
  {
   name: 'The Marines Who Never Returned',
    year: '1963'
  },
  {
   name: 'The Masseurs and a Woman',
    year: '1938'
  },
  {
   name: 'The Medium',
    year: '2021'
  },
  {
   name: 'The Merciless',
    year: '2017'
  },
  {
   name: 'The Money',
    year: '1958'
  },
  {
   name: 'The Most Terrible Time in My Life',
    year: '1994'
  },
  {
   name: 'The Murmuring',
    year: '1995'
  },
  {
   name: 'The Naked Island',
    year: '1960'
  },
  {
   name: 'The Night Before the Strike',
    year: '1990'
  },
  {
   name: 'The Nightmare',
    year: '2015'
  },
  {
   name: 'The Nightmare Before Christmas',
    year: '1993'
  },
  {
   name: 'The Novelist`s Film',
    year: '2022'
  },
  {
   name: 'The Official Story',
    year: '1985'
  },
  {
   name: 'The Ordeal',
    year: '2004'
  },
  {
   name: 'The Passenger',
    year: '1975'
  },
  {
   name: 'The Peanut Butter Falcon',
    year: '2019'
  },
  {
   name: 'The Personal History of David Copperfield',
    year: '2019'
  },
  {
   name: 'The Phantom Carriage',
    year: '1921'
  },
  {
   name: 'The Piano in a Factory',
    year: '2010'
  },
  {
   name: 'The Player',
    year: '1992'
  },
  {
   name: 'The Pollen of Flowers',
    year: '1972'
  },
  {
   name: 'The Pornographers',
    year: '1966'
  },
  {
   name: 'The Portuguese Woman',
    year: '2018'
  },
  {
   name: 'The Power of Kangwon Province',
    year: '1998'
  },
  {
   name: 'The President`s Last Bang',
    year: '2005'
  },
  {
   name: 'The Prodigal Son',
    year: '1981'
  },
  {
   name: 'The Promenade',
    year: '2000'
  },
  {
   name: 'The Quiet Girl',
    year: '2022'
  },
  {
   name: 'The Raid',
    year: '2011'
  },
  {
   name: 'The Raid 2',
    year: '2014'
  },
  {
   name: 'The Red Shoes',
    year: '1948'
  },
  {
   name: 'The Return',
    year: '2003'
  },
  {
   name: 'The Road to Sampo',
    year: '1975'
  },
  {
   name: 'The Road to the Racetrack',
    year: '1991'
  },
  {
   name: 'The Rock',
    year: '1996'
  },
  {
   name: 'The Rocking Horsemen',
    year: '1992'
  },
  {
   name: 'The Sacrifice',
    year: '1986'
  },
  {
   name: 'The Sandwich Man',
    year: '1983'
  },
  {
   name: 'The Scent of Green Papaya',
    year: '1993'
  },
  {
   name: 'The Seaside Village',
    year: '1965'
  },
  {
   name: 'The Servant',
    year: '1963'
  },
  {
   name: 'The Shepherd of the Hills',
    year: '1941'
  },
  {
   name: 'The Shop on Main Street',
    year: '1965'
  },
  {
   name: 'The Show Must Go On',
    year: '2007'
  },
  {
   name: 'The Silence',
    year: '1963'
  },
  {
   name: 'The Silenced',
    year: '2015'
  },
  {
   name: 'The Son',
    year: '2002'
  },
  {
   name: 'The Square',
    year: '2017'
  },
  {
   name: 'The Story of Nampu',
    year: '1984'
  },
  {
   name: 'The Story of Qiu Ju',
    year: '1992'
  },
  {
   name: 'The Story of the Last Chrysanthemum',
    year: '1939'
  },
  {
   name: 'The Surrogate Woman',
    year: '1987'
  },
  {
   name: 'The Sweet Hereafter',
    year: '1997'
  },
  {
   name: 'The Sword of Doom',
    year: '1966'
  },
  {
   name: 'The Tale',
    year: '2018'
  },
  {
   name: 'The Tale of Iya',
    year: '2013'
  },
  {
   name: 'The Tale of the Princess Kaguya',
    year: '2013'
  },
  {
   name: 'The Terror Live',
    year: '2013'
  },
  {
   name: 'The Tiger',
    year: '2015'
  },
  {
   name: 'The Tree of Life',
    year: '2011'
  },
  {
   name: 'The Trial',
    year: '1962'
  },
  {
   name: 'The Trouble with Harry',
    year: '1955'
  },
  {
   name: 'The Truth Beneath',
    year: '2016'
  },
  {
   name: 'The Turin Horse',
    year: '2011'
  },
  {
   name: 'The Twilight Samurai',
    year: '2002'
  },
  {
   name: 'The Umbrellas of Cherbourg',
    year: '1964'
  },
  {
   name: 'The Unforgiven',
    year: '2005'
  },
  {
   name: 'The Unjust',
    year: '2010'
  },
  {
   name: 'The Virgin Spring',
    year: '1960'
  },
  {
   name: 'The Virgin Suicides',
    year: '1999'
  },
  {
   name: 'The Visitors',
    year: '1993'
  },
  {
   name: 'Wandering',
    year: '2022'
  },
  {
   name: 'The Wandering Princess',
    year: '1960'
  },
  {
   name: 'The Warrior',
    year: '2001'
  },
  {
   name: 'The Watermelon Woman',
    year: '1996'
  },
  {
   name: 'The Way We Are',
    year: '2008'
  },
  {
   name: 'The Wedding Day',
    year: '1957'
  },
  {
   name: 'The Whale',
    year: '2022'
  },
  {
   name: 'The Whale Hunter',
    year: '1984'
  },
  {
   name: 'The White Meadows',
    year: '2009'
  },
  {
   name: 'The Wild Pear Tree',
    year: '2018'
  },
  {
   name: 'The Wind Rises',
    year: '2013'
  },
  {
   name: 'The Woman Who Ran',
    year: '2020'
  },
  {
   name: 'The World of Kanako',
    year: '2014'
  },
  {
   name: 'The Yellow Handkerchief',
    year: '1977'
  },
  {
   name: 'The Yen Family',
    year: '1988'
  },
  {
   name: 'Thief',
    year: '1981'
  },
  {
   name: 'Thirteen',
    year: '2003'
  },
  {
   name: 'Thread of Lies',
    year: '2014'
  },
  {
   name: 'Three Husbands',
    year: '2018'
  },
  {
   name: 'Three Sisters',
    year: '2020'
  },
  {
   name: 'Threeâ€¦ Extremes',
    year: '2004'
  },
  {
   name: 'Through a Glass Darkly',
    year: '1961'
  },
  {
   name: 'Throw Away Your Books, Rally in the Streets',
    year: '1971'
  },
  {
   name: 'Thunder Road',
    year: '2018'
  },
  {
   name: 'Ticket',
    year: '1986'
  },
  {
   name: 'Timeless Bottomless Bad Movie',
    year: '1997'
  },
  {
   name: 'To the Ends of the Earth',
    year: '2019'
  },
  {
   name: 'Together Together',
    year: '2021'
  },
  {
   name: 'Tokyo Drifter',
    year: '1966'
  },
  {
   name: 'Tokyo Marigold',
    year: '2001'
  },
  {
   name: 'Tokyo Story',
    year: '1953'
  },
  {
   name: 'Tokyo Twilight',
    year: '1957'
  },
  {
   name: 'Toni Erdmann',
    year: '2016'
  },
  {
   name: 'Tony Manero',
    year: '2008'
  },
  {
   name: 'Tony Takitani',
    year: '2004'
  },
  {
   name: 'Too Late',
    year: '2015'
  },
  {
   name: 'Top Gun: Maverick',
    year: '2022'
  },
  {
   name: 'Torment',
    year: '1994'
  },
  {
   name: 'Training Day',
    year: '2001'
  },
  {
   name: 'Treeless Mountain',
    year: '2008'
  },
  {
   name: 'Triangle of Sadness',
    year: '2022'
  },
  {
   name: 'Tricky Brains',
    year: '1991'
  },
  {
   name: 'Troll Hunter',
    year: '2010'
  },
  {
   name: 'True Mothers',
    year: '2020'
  },
  {
   name: 'Trust',
    year: '1990'
  },
  {
   name: 'Twelve Nights',
    year: '2000'
  },
  {
   name: 'Twenty-Four Eyes',
    year: '1954'
  },
  {
   name: 'Two in the Shadow',
    year: '1967'
  },
  {
   name: 'Two Lights: Relumino',
    year: '2017'
  },
  {
   name: 'Two-Lane Blacktop',
    year: '1971'
  },
  {
   name: 'U.S. Go Home',
    year: '1994'
  },
  {
   name: 'Umberto D.',
    year: '1952'
  },
  {
   name: 'Uncle Boonmee Who Can Recall His Past Lives',
    year: '2010'
  },
  {
   name: 'Uncle Frank',
    year: '2020'
  },
  {
   name: 'Under the Flag of the Rising Sun',
    year: '1972'
  },
  {
   name: 'Under the Open Sky',
    year: '2020'
  },
  {
   name: 'Under the Sky in Seoul',
    year: '1961'
  },
  {
   name: 'Underground',
    year: '1928'
  },
  {
   name: 'Underground',
    year: '1995'
  },
  {
   name: 'Unforgettable',
    year: '2016'
  },
  {
   name: 'Unforgiven',
    year: '1992'
  },
  {
   name: 'Upstream Color',
    year: '2013'
  },
  {
   name: 'Us and Them',
    year: '2018'
  },
  {
   name: 'Vagabond',
    year: '1985'
  },
  {
   name: 'Vanishing Time: A Boy Who Returned',
    year: '2016'
  },
  {
   name: 'Very Ordinary Couple',
    year: '2013'
  },
  {
   name: 'Veteran',
    year: '2015'
  },
  {
   name: 'Victoria',
    year: '2015'
  },
  {
   name: 'Violent Cop',
    year: '1989'
  },
  {
   name: 'Virgin Mountain',
    year: '2015'
  },
  {
   name: 'Virgin Stripped Bare by Her Bachelors',
    year: '2000'
  },
  {
   name: 'Visaranai',
    year: '2015'
  },
  {
   name: 'Vitalina Varela',
    year: '2019'
  },
  {
   name: 'Vivre Sa Vie',
    year: '1962'
  },
  {
   name: 'Voices in the Wind',
    year: '2020'
  },
  {
   name: 'Voices Through Time',
    year: '1996'
  },
  {
   name: 'Waiting Alone',
    year: '2005'
  },
  {
   name: 'Walk the Line',
    year: '2005'
  },
  {
   name: 'Walk Up',
    year: '2022'
  },
  {
   name: 'Wanee & Junah',
    year: '2001'
  },
  {
   name: 'Warm Water Under a Red Bridge',
    year: '2001'
  },
  {
   name: 'Water Lilies',
    year: '2007'
  },
  {
   name: 'Way Back Home',
    year: '2013'
  },
  {
   name: 'We Are Little Zombies',
    year: '2019'
  },
  {
   name: 'We Are the Best!',
    year: '2013'
  },
  {
   name: 'Wedding Dress',
    year: '2010'
  },
  {
   name: 'Welcome Home',
    year: '1995'
  },
  {
   name: 'West Beirut',
    year: '1998'
  },
  {
   name: 'What Did the Lady Forget?',
    year: '1937'
  },
  {
   name: 'What Do We See When We Look at the Sky?',
    year: '2021'
  },
  {
   name: 'What Happened Was...',
    year: '1994'
  },
  {
   name: 'When a Woman Ascends the Stairs',
    year: '1960'
  },
  {
   name: 'Where Chimneys Are Seen',
    year: '1953'
  },
  {
   name: 'Where Do We Go Now?',
    year: '2011'
  },
  {
   name: 'Whispering Corridors',
    year: '1998'
  },
  {
   name: 'White Badge',
    year: '1992'
  },
  {
   name: 'Why Has Bodhi-Dharma Left for the East?',
    year: '1989'
  },
  {
   name: 'Wife',
    year: '1953'
  },
  {
   name: 'Wife! Be Like a Rose!',
    year: '1935'
  },
  {
   name: 'Wife of a Spy',
    year: '2020'
  },
  {
   name: 'Willard',
    year: '2003'
  },
  {
   name: 'Winter Sleep',
    year: '2014'
  },
  {
   name: 'Winter Woman',
    year: '1977'
  },
  {
   name: 'Winter`s Bone',
    year: '2010'
  },
  {
   name: 'Wolfwalkers',
    year: '2020'
  },
  {
   name: 'Woman of the Lake',
    year: '1966'
  },
  {
   name: 'Woman on the Beach',
    year: '2006'
  },
  {
   name: 'Wood Job!',
    year: '2014'
  },
  {
   name: 'Wrath of Man',
    year: '2021'
  },
  {
   name: 'Yearning',
    year: '1964'
  },
  {
   name: 'Yellow Flowers On the Green Grass',
    year: '2015'
  },
  {
   name: 'Yeong-jaâ€™s Heydays',
    year: '1975'
  },
  {
   name: 'YMCA Baseball Team',
    year: '2002'
  },
  {
   name: 'Yojimbo',
    year: '1961'
  },
  {
   name: 'Young Thugs: Nostalgia',
    year: '1998'
  },
  {
   name: 'Your Name Engraved Herein',
    year: '2020'
  },
  {
   name: 'Your Name.',
    year: '2016'
  },
  {
   name: 'Yourself and Yours',
    year: '2016'
  },
  {
   name: 'Youth',
    year: '2015'
  },
  {
   name: 'Yuni',
    year: '2021'
  },
  {
   name: 'Zabriskie Point',
    year: '1970'
  },
  {
   name: 'Zatoichi',
    year: '2003'
  },
  {
   name: 'Crash',
    year: '1996'
  },
  {
   name: 'I Dream in Another Language',
    year: '2017'
  },
  {
   name: 'The Holy Girl',
    year: '2004'
  },
  {
   name: 'Oslo, August 31st',
    year: '2011'
  },
  {
   name: 'You, the Living',
    year: '2007'
  },
  {
   name: 'Back to Back, Face to Face',
    year: '1994'
  },
  {
   name: 'Before, Now & Then',
    year: '2022'
  },
  {
   name: 'Crazy, Stupid, Love.',
    year: '2011'
  },
  {
   name: 'Dance, Girl, Dance',
    year: '1940'
  },
  {
   name: 'Haruka, Nostalgia',
    year: '1993'
  },
  {
   name: 'I Are You, You Am Me',
    year: '1982'
  },
  {
   name: 'Lust, Caution',
    year: '2007'
  },
  {
   name: 'My Love, My Bride',
    year: '2014'
  },
  {
   name: 'My God, My God, Why Hast Thou Forsaken Me?',
    year: '2005'
  },
  {
   name: 'Quo Vadis, Aida?',
    year: '2020'
  },
  {
   name: 'Sex, Lies, and Videotape',
    year: '1989'
  },
  {
   name: 'Small, Slow But Steady',
    year: '2022'
  },
  {
   name: 'So Long, My Son',
    year: '2019'
  },
  {
   name: 'Suddenly, Last Summer',
    year: '1959'
  },
  {
   name: 'Synecdoche, New York',
    year: '2008'
  },
  {
   name: 'The Cook, the Thief, His Wife & Her Lover',
    year: '1989'
  },
  {
   name: 'The Devil, Probably',
    year: '1977'
  },
  {
   name: 'Wild Geese',
    year: '1953'
  },
  {
   name: 'Bringing Out the Dead',
    year: '1999'
  },
  {
   name: 'Himala',
    year: '1982'
  },
  {
   name: 'Hill of No Return',
    year: '1992'
  },
  {
   name: 'Silence',
    year: '2016'
  },
  {
   name: 'Nights of Cabiria',
    year: '1957'
  },
  {
   name: 'Nostalgia',
    year: '1983'
  },
  {
   name: 'Lilya 4-ever',
    year: '2002'
  },
  {
   name: 'Aguirre, the Wrath of God',
    year: '1972'
  },
  {
   name: 'Calvary',
    year: '2014'
  },
  {
   name: 'Secrets & Lies',
    year: '1996'
  },
  {
   name: 'Wings of Desire',
    year: '1987'
  },
  {
   name: 'Invisible Life',
    year: '2019'
  },
  {
   name: 'Three Colors: Red',
    year: '1994'
  },
  {
   name: 'Through the Olive Trees',
    year: '1994'
  },
  {
   name: 'Chain',
    year: '2004'
  },
  {
   name: 'Blindspotting',
    year: '2018'
  },
  {
   name: 'Real Women Have Curves',
    year: '2002'
  },
  {
   name: 'Inside Llewyn Davis',
    year: '2013'
  },
  {
   name: 'Bound',
    year: '1996'
  },
  {
   name: 'Son of Saul',
    year: '2015'
  },
  {
   name: 'Retablo',
    year: '2017'
  },
  {
   name: 'Black Rain',
    year: '1989'
  },
  {
   name: 'Bad Education',
    year: '2004'
  },
  {
   name: 'Leviathan',
    year: '2014'
  },
  {
   name: 'Chameleon Street',
    year: '1989'
  },
  {
   name: 'Working Girls',
    year: '1986'
  },
  {
   name: 'A Hidden Life',
    year: '2019'
  },
  {
   name: 'Rushmore',
    year: '1998'
  },
  {
   name: 'Unorthodox',
    year: '2020'
  },
  {
   name: 'Deep Cover',
    year: '1992'
  },
  {
   name: 'Exotica',
    year: '1994'
  },
  {
   name: 'In the Family',
    year: '2011'
  },
  {
   name: 'Women Talking',
    year: '2022'
  },
  {
   name: 'Life Is Sweet',
    year: '1990'
  },
  {
   name: 'Dead Man',
    year: '1995'
  },
  {
   name: 'Spencer',
    year: '2021'
  },
  {
   name: 'Silvia Prieto',
    year: '1999'
  },
  {
   name: 'Time for Revenge',
    year: '1981'
  },
  {
   name: 'Roma',
    year: '2004'
  },
  {
   name: 'Felicidades',
    year: '2000'
  },
  {
   name: 'Intimate Stories',
    year: '2002'
  },
  {
   name: 'Sidewalls',
    year: '2011'
  },
  {
   name: 'Extraordinary Stories',
    year: '2008'
  },
  {
   name: 'The Magic Gloves',
    year: '2003'
  },
  {
   name: 'The Sleepwalkers',
    year: '2019'
  },
  {
   name: 'Pizza, Beer, and Cigarettes',
    year: '1998'
  },
  {
   name: 'The Man Next Door',
    year: '2010'
  },
  {
   name: 'An Argentinian in New York',
    year: '1998'
  }]
    }
  },
computed: {
    randomElement() {
      const index = Math.floor(Math.random() * (this.data.length))
      const randomElement = this.data[index];
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
a {
  color: #42b983;
}
.title{
  font-size:3rem;

}
.year{
  font-size:3rem;
  font-weight: 900;
}
.banner{
  font-size: 5rem;
  text-transform: uppercase;
  background-color: black;
  color:white;
}
.botton{
  width: 90%;
  height: 2rem;
  font-weight: 800;
  font-size:1rem;
}
</style>
