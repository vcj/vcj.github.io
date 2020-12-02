### November 16: Islands

<img src="images/islands.jpg?raw=true" target="_blank"/>
Taking a looser interpretation of the prompt here, also one of the few times when I've gotten a clear easy answer to the question "is there data for this?" NASA's Socioeconomic Data and Applications Center (SEDAC) kindly maintains a set of satellite-derived environmental indicators like <a href="https://sedac.ciesin.columbia.edu/data/set/sdei-viirs-dmsp-dlight" target="_blank">change in nighttime lights</a>, <a href="https://sedac.ciesin.columbia.edu/data/set/sdei-trends-freshwater-availability-grace" target="_blank">availability of freshwater resources</a>, and <a href="https://sedac.ciesin.columbia.edu/data/set/sdei-global-uhi-2013" target="_blank">global urban heat islands</a>! This also meant I could give the map an incredibly stupid title with the perfect typeface to match.
<br><br>
Data from the <a href="https://sedac.ciesin.columbia.edu/" target="_blank">NASA SEDAC</a> and <a href="https://www.naturalearthdata.com/" target="_blank">Natural Earth</a>. Typeface is <a href="https://www.dafont.com/santana.font">Santana</a>, which luckily for me looks nice.

### November 15: Connections

<img src="images/connex.jpg?raw=true" target="_blank"/>
I love <a href="https://www.atlasobscura.com/articles/take-a-look-at-americas-least-convincing-cell-phone-tower-trees" target="_blank">fake tree cell towers</a>. They're so goofy looking. Structural bathos. A map of their locations seemed like a novel way to approach the theme of 'connections,' and surely the FCC tracks their location, right? Wrong! Though the FCC does maintain a database of cell tower locations as part of their publicly available Homeland Infrastructure Foundation-Level Data, sadly for me it doesn't include appearance. There are a number of other freely available databases of cell towers out there but none of them seem to include it, either. It took me honestly way too long to realize that if they were noted anywhere, it would be old reliable OpenStreetMap. Sure enough, the multitalented <a href="https://twitter.com/erictheise" target="_blank">Eric Theise</a> not only brought the OSM notation to life a year or so ago but wrote <a href="https://erictheise.com/blog/2020/01/06/fake-trees#.X8bpNc1KhPY" target="_blank">a delightful summary on the process</a> of adding the key 'mimics' to cell towers (which are as a whole classified as <a href="https://wiki.openstreetmap.org/wiki/Tag:man_made%3Dmast" target="_blank">man-made masts</a>, hence the title). As the tag is new and not terribly well known, it is not a very complete dataset. Many are mapped as communications towers without the specific mimics tag but with the fact that they're a fake tree noted elsewhere in the tags - the mimics tag serves the function of standardizing this (these are also included on the map, I am slowly adding the mimics tag to them in OSM). Eric's writeup also includes helpful instructions on how to add the tag when you're out mapping with the <a href="https://wiki.openstreetmap.org/wiki/Go_Map!!" target="_blank">Go Map!! app</a>.
<br><br>
Data from the <a href="https://www.openstreetmap.org/" target="_blank">OpenStreetMap</a> via <a href="https://overpass-turbo.eu/" target="_blank">Overpass Turbo<a/> and <a href="https://www.naturalearthdata.com/" target="_blank">Natural Earth</a>. Typeface is <a href="https://lauraworthingtondesign.com/products/collections/charcuterie">Charcuterie</a> and, for the code-y bits, Courier.

### November 14: Climate Change

<img src="images/14 climate.jpg?raw=true" onclick="window.open('14 climate.jpg', '_blank');" />
For the challenge's climate change day, I mapped the past 70 years of wildfires in California, five years at a time. Not much to say here. Bleak. This map is more detailed than it appears at first glance, clicking the image will open it larger in a new tab.
<br><br>
Data from the <a href="https://gis.data.ca.gov/datasets/f72ebe741e3b4f0db376b4e765728339_0" target="_blank">California State Geoportal</a> and <a href="https://www.naturalearthdata.com/" target="_blank">Natural Earth</a>. Typeface is <a href="https://www.sarahbellmaps.com/typography-for-topography-belltopo-sans-free-font/">BellTopo Sans</a>.

### November 13: Raster

<img src="images/kutu.gif?raw=true" target="_blank"/>
The growing beige blob upper left center of this gif is the Kutupalong refugee camp near Cox's Bazar in Bangladesh, just over the border with Myanmar. Though it's technically been there since 1991, it exploded in growth as the Rohingya population fled following a series of attacks in August 2017 and by 2018 it was (still is) the world's largest refugee camp. The gif was made with <a href="https://developers.google.com/earth-engine/datasets/catalog/LANDSAT_LE07_C01_T1_SR" target="_blank">Landsat imagery</a> in <a href="https://code.earthengine.google.com/" target="_blank">Google Earth Engine</a>, <a href="https://youtu.be/zqBahKeXn14" target="_blank">here is a slightly more nuanced (but label-less, I was tired) video</a>.

### November 12: Map Made Without GIS Software

<img src="images/IMG-2019.JPG?raw=true" target="_blank"/>
This is a <a href="https://cooking.nytimes.com/recipes/1019312-chocolate-chocolate-birthday-cake" target="_blank">chocolate layer cake</a> with <a href="https://veenaazmanov.com/best-cherry-filling/" target="_blank">cherry filling</a> in between the layers, decorated with the DC metro map. There are some errors, even though I was looking at a metro map while doing it. ¯\_(ツ)_/¯

### November 11: 3D

<img src="images/stpauls1.JPG?raw=true"/>
Not a lot of 3D maps in my current role so I took the opportunity to try out a new piece of software, <a href="https://ephtracy.github.io/index.html?page=aerialod">AerialOD</a>, after seeing it all over the Challenge hashtag. It's a neat program, very powerful, and somewhat Blenderesque. I grabbed some LIDAR from the <a href="https://environment.data.gov.uk/DefraDataDownload/?Mode=survey">UK Department of Environmental Food and Rural Affairs' website</a> and just sort of messed around until I got something that looked all right (Alisdar Rae's <a href="http://www.statsmapsnpix.com/2019/11/amazing-3d-rendering-with-aerialod.html">intro to the program</a> was KEY). 
 <br><br>
 The above image is looking east-ish over St Paul's Cathedral and the City, and below are two more, showing a view northnorthwestish over Regent's Park and northwestish over Heathrow, just so cool that the LIDAR is so detailed you can make out individual planes!
<br><img src="images/park1.JPG?raw=true"/>
<img src="images/heathrow1.JPG?raw=true"/>
Data from <a href="https://environment.data.gov.uk/DefraDataDownload/?Mode=survey">DEFRA</a>.

### November 10: Grid

<img src="images/gridiron.jpg?raw=true"/>
I had oral surgery this morning and just wasn't feeling the grid theme or putting much energy into anything other than crawling back into bed, so I went in another direction and did grid...iron orientations. I thought there might be some patterns or something evident here. Nope! Not really. Question marks are domes where orientation was unclear (the Las Vegas Raiders' dome wasn't built yet at the time google earth's image was taken, which is fine because that dome doesn't open).
<img src="images/grid blank.jpg?raw=true"/>
  unlabeled version, the lines are clearer. 
  <br><br>
 I also thought the Bills' stadium might stick out more. The stadium was built on land that includes a cemetery, 
   and the descendents of those interred there refused to allow the graves to be moved (this is not a Poltergeist situation, the headstones are still there). As a result, the stadium was not constructed North-South as originally planned but on a more East-West tilt, which allows for a vicious crosswind off Lake Erie (3.75 miles due west) to keep Bills fans' beers extra chilly. Also sometimes the wind affects the ball trajectory. And maybe the cemetery's proximity means the team is cursed. 
  <br>
<img src="images/cemetery1.JPG?raw=true"/>
<br><br>
  Images are screenshots from <a href="https://earth.google.com/"> Google Earth</a>, states from <a href="https://www.naturalearthdata.com/">Natural Earth</a>. Typeface is <a href="https://www.dafont.com/varsity-team.font/">Varsity Team from dafont</a>.

### November 9: Monochrome

Most of my maps for the challenge are pretty simple and straightforward, this one might need a bit more explanation. I'm not great at monochrome mapping, stylistically speaking (I love clashing colors, the more garish the better) so I thought it best to lean on terrain mapping, where a gradient hillshade can do most of the heavy lifting.
  <br><br>
  Deciding what landscape to map, then, I found myself wondering if the Erbil Citadel would show up as terrain. The Citadel is an 80- to 100-foot high tell in the center of Erbil, the capital of the Kurdish Autonomous Region of Iraq. It looks like this on Google Earth
  <img src="images/erbil_googleearth.JPG?raw=true"/>
  and like this from the ground. I can't speak for the entire country but this part of Iraq is a lot more green that it appears from above (or on cable news).  
  <img src="images/IMG-2709.jpg?raw=true"/>
  Tells are almost like artificial terrain - they're formed from centuries of people living, building and re-building, in the same spot. The tell at the center of Erbil is thought to be the longest continually occupied human settlement - people have lived there for over 6,000 years. Though it's mostly a tourist attraction these days (as well as <a href="https://whc.unesco.org/en/list/1437/">a UNESCO World Heritage site</a>), some folks do still live up there. 
  <br><br>
 So yeah I was wondering if this tallish, flat-topped, slope-sided hill would be distinct enough from the relatively flat terrain immediately surrounding it to show up in a Shuttle Radar Topography Mission (SRTM) 1 arc second digital elevation model hillshade.
  <img src="images/erb_2.gif?raw=true"/>
  It does!!!! Here's a closer look, zoomed way in. Our little friend, like a small out-of-place mesa.  
  <img src="images/closeup.jpg?raw=true"/> 
  Question: answered. I then made a little map around it to help give a sense of what's being shown. I feel like the geography of this area is not as familiar to most folks.
  <img src="images/9 mono.jpg?raw=true"/>
  Et voila. 
  <br><br>
  Data from <a href="https://search.earthdata.nasa.gov/search/granules/collection-details?p=C1000000240-LPDAAC_ECS&pg[0][gsk]=-start_date&q=SRTM&tl=1589303691!4!!">NASA SRTM</a> and <a href="https://data.humdata.org/organization/ocha-iraq">UNOCHA Iraq on Humanitarian Data Exchange</a>. Typeface is <a href="https://www.sarahbellmaps.com/typography-for-topography-belltopo-sans-free-font/">BellTopo Sans</a>.
  
### November 8: Yellow

<img src="images/8 yellow.jpg?raw=true"/>
When I saw <a href="https://moriartynaps.org/midnight-arrivial/">Dylan's gorgeous re-creation of flying into (or out of) a city at night</a>, I was immediately reminded of the story from a few years back around Col. Chris Hadfield's photo of Berlin from space and how, decades after reunification, the city's divide was literally visible from space in the streetlights. This was a quick one, so it's not so much a map as a georeferenced and labeled satellite image. Oh well. I still like it.
<br><br>
Data from <a href="https://daten.berlin.de/">Berlin Open Data</a> and <a href="https://www.openstreetmap.org/">OpenStreetMap</a>, image from <a href="https://twitter.com/cmdr_hadfield/status/324638635766980608?lang=en">Colonel Chris Hadfield on twitter</a>. Based on what I could translate, I am pretty sure Berlin Open Data has streetlight data, but my German is p much limited to basic conversation and not, like, technical terms. Typeface is back to <a href="https://www.sarahbellmaps.com/typography-for-topography-belltopo-sans-free-font/">BellTopo Sans</a>!

### November 7: Green

<img src="images/goatsnstoats.jpg?raw=true"/>
Today's map plan ground to a screeching halt once I saw that the New Zealand Department of Conservation (I almost typed Department of Conversation, which was a pretty good bar on K Rd like 12 years ago) Te Papa Atawhai collected data on FERAL GOATS AND STOATS.
<br><br>
Data from <a href="https://catalogue.data.govt.nz/organization/department-of-conservation"> New Zealand Department of Conservation Te Papa Atawhai</a> and <a href="https://www.naturalearthdata.com/">Natural Earth</a>. Typeface is <a href="https://www.dafont.com/franchise-2.font/">Franchise, also from dafont</a>.

### November 6: Red

<img src="images/bloodfield.jpg?raw=true"/>
I wasn't sure what to do for this one, so I asked Taylor for ideas, and he said, "I don't know, blood?" Which led me to finding this old map of DC neighborhoods and layering that with the current spread of (blood-)red maple trees. 
<br><br>
Data from <a href="https://opendata.dc.gov/">what I am now realizing is called Open Data DC and not DC GIS anymore</a> and <a href="https://ggwash.org/view/12595/meet-me-down-in-pipetown-dcs-neighborhoods-in-1877">Greater Greater Washington</a>. Both typefaces are from <a href="https://www.dafont.com/">dafont</a>'s warehouse of free for personal use fonts.</p>

### November 5: Blue 

<img src="images/blue.jpg?raw=true"/>
Above is what I posted to twitter, for legibility's sake. Below is the full map. Someone needs to tell these companies there are colors outside of North America and Europe....
<img src="images/5 blue full.jpg?raw=true"/>
<br><br>
Data from <a href="https://images.sherwin-williams.com/content_images/sw-pdf-sherwin-williams-color.pdf">Sherwin-Williams</a>, <a href="https://www.benjaminmoore.com/">Benjamin Moore</a>, <a href="https://encycolorpedia.com">Encycolorpedia</a>, and <a href="https://www.naturalearthdata.com/">Natural Earth</a>. Typeface is, you guessed it, <a href="https://www.sarahbellmaps.com/typography-for-topography-belltopo-sans-free-font/">BellTopo Sans</a>.

### November 4: Hexagons 

<img src="images/4 hexagons.jpg?raw=true"/>
This one started out as something else entirely but I am simply too committed to dumb and pointless mapping.
<br><br>
Data from <a href="https://geonames.nga.mil/gns/html/namefiles.html">GNS</a> and <a href="https://www.naturalearthdata.com/">Natural Earth</a>, typeface is <a href="https://lauraworthingtondesign.com/products/collections/charcuterie">Charcuterie</a>, which I actually purchased last year for another project and am determined to get my money's worth so I'm sure it'll end up on a lot more of these as the month progresses.

### November 3: Polygons 

<img src="images/3 polygons.jpg?raw=true"/>
<br><br>
Since it's election day, I figured it was only right to do a set of congressional district polygons. Data from <a href="http://cdmaps.polisci.ucla.edu/">http://cdmaps.polisci.ucla.edu/</a>, typeface is again <a href="https://www.sarahbellmaps.com/typography-for-topography-belltopo-sans-free-font/">BellTopo Sans</a>. 

### November 2: Lines 

<img src="images/2 lines.jpg?raw=true"/>
Rarely - only twelve times since 1953 - a storm will cross over from the Atlantic to the Pacific basin (or vice versa).
<br><br>
Data from <a href="https://www.ncdc.noaa.gov/ibtracs/index.php?name=ib-v4-access">NOAA's National Centers for Environmental Information</a>, <a href="https://www.naturalearthdata.com/">Natural Earth</a>, and <a href="https://en.wikipedia.org/wiki/List_of_Atlantic%E2%80%93Pacific_crossover_hurricanes">Wikipedia</a>. Typeface is of course <a href="https://www.sarahbellmaps.com/typography-for-topography-belltopo-sans-free-font/">BellTopo Sans</a>.


### November 1: Points 

<img src="images/1 - points v2.jpg?raw=true"/>
 I actually made this one on October 1st...too excited for the challenge I guess. 
 <br><br>
 Data from <a href="https://octo.dc.gov/service/dc-gis-services">DC GIS</a>. Typeface is <a href="https://www.sarahbellmaps.com/typography-for-topography-belltopo-sans-free-font/">BellTopo Sans</a>. 


---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute --> 
