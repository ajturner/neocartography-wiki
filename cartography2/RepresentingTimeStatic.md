
[Permalink](http://web.archive.org/web/20100204055532/http://cartography2.org/Chapters/page0/RepresentingTimeStatic.html "Permalink to Cartography 2.0 - Representing Time on Static Maps")

# Cartography 2.0 - Representing Time on Static Maps

by Mark Harrower
date: 09/02/09

Whoa! I know what you're thinking: Cartography 2.0 is all about animated and interactive maps, so why the section on static maps? Well...
You don't need to use animation to show geographic processes on maps. In fact, a carefully designed static map may make "seeing" time easier than watching an animation of the same data; it depends on the complexity of the dataset, the kind of geographic change being shown, and the facts you need from your map. One big advantage of static depictions of time is that they tend to be holistic and will depict all time periods at once, allowing the reader to examine and compare the moments (and the spatial patterns) at their leisure. By comparison, an animated map typically only presents a single moment fleetingly, and the user must watch and, more crucially,* remember* and then *synthesize* in their head each frame of the animation before they've seen all of the data. As I will show below, for some datasets, a static map might be preferable. 

Of course, temporally holistic static maps (that show all time periods at once in a single image) tend to only show **simple geographic processes**, usually of point or line features, such as the path of a hurricane over a one-week period (it is a single line and only one position per time period). By comparison, it would be nearly impossible to show the hourly air temperature and wind speed readings for that same week for the entire Caribbean: that's just a lot more data and it exists for every location on the map, not just a single point, and there are over a thousand time-slices (or layers) to the map. In other words, there are limits to how much data we can pack into a static map. Of course we often collapse large, complex datasets (e.g., thousands of hourly temperature readings) into a single static map by mapping averages or differencs from averages (see examples below), but the downside is that **the original data are lost and time has been eliminated** from those kinds of static maps. In that case, an animated map is an obvious solution.

Examine the great examples below and consider if your data could also work as a static graphic. Animated maps are harder and more expensive to make, more likely to break, harder to distribute, and can't really be printed. In short, if I have a choice between a static map and animated map and they both work equally well, I'll probably go with the static one. While I am a big fan of animated maps, I also know they don't work in many situations.

Folks who have inspired much of my thinking on this: [Alan MacEachren][1], [Mark Monmonier][2], [Sara Fabrikant][3]

* * *

  
Examples of Time on Static Maps
[![Minard][5]][5]  
(click to see big)  


  
**Example #1: **[Minard's map (1869) of Napoleon's doomed campaign to Moscow (1812-13)][5] is one of the all-time classics. It depicts space, time, and attribute—both deaths and temperature—all in a deceptively simple, two-color diagram. Tufte calls this the greatest info graphic of all time. It's certainly an efficient one, and the real stroke of genius was the addition of the daily temperatures endured by the soliders during that ill-fated winter campaign: The changes in the main line thickness are the "outcome" (a decimated army that was defeated by winter long before it ever got to Moscow) while the temperature graph at the bottom is the "explanatory variable" in the equation (a record-cold winter). Note some of the small details, such as the toll that river crossings took during the chaotic, desperate retreat (the black line). 

*What,* *why*, *where*, *when* and *how* are all answered with this 140-year-old graphic. You don't need a quad-core CPU to tell good stories or do brilliant design. 

* * *

**  
**
[![min_1a][7]][7]**  
**[![legend][8]][8]**  
**

Example #2: [Detected Groundwater Analyte from 1952 to 2002 in West Central Los Alamos and Pueblo Canyons][8]. Created by some of the staff at Los Alamos Lab, not only does this map help us to visualize a large amount of data about something we never get to see (movement of ground water) it also shows the differential impact—in both time and space—of pollutants from a mine. The map also includes relevant surface features like terrain and the location of buildings, roads which help explain the patterns seen undeground. The legend above explains how this maps works. I'm an especially big fan of the black for years with data and gray for years without (see how this makes scanning the full map that much faster). The circular time series graph creates a unique "signature" for each location, allowing us to extract specific facts for specific places (the numbers) and to appreciate the overall pattern across 50 years of data. The authors even included a way to use locations with different monitoring lifespans, without having to simply throw away newer monitoring sites or throwaway the oldest data. And all that fits in a few square inches. 

* * *

**  
**
[![smallNDVI][10]][10]**  
**

**  
Example #3: **Geography at Work: The NDVI. I made this map my first year of grad school as a way to show 14 years of daily satellite data (e.g., a truly massive amount of data) in a single map that showed the relative timing of photosynthetic activity across North and Central America. Unlike the two examples above, everywhere on the map has data (it's not a few sample locations) and so I couldn't use map symbols like the ones above to cover any portion of the map. Instead, I based the map around our remarkable ability to perceive hue, saturation and lightness as a way to encode different dimensions of the data. The hue is determined by the relative strength of the RGB components: If a location has lots of green vegetation covering the landscape in September, but little or none in May and July, a location will be blue (Sept data was shown using the blue channel, green is July and red is May). That's why in the middle of North america the map fades to blue: the growing season is later and later the further north you go. If the reflectance signal is very strong in all three months (e.g. lots of vegetation in all 3 months, like in the jungles of the Yucatan) a location will look white, since combining full strength rbg creates white. While the **hue tells you the *****timing*** of maximum greening, the **intensity/saturation of those individual hues tells you *****how much***** total vegetation exists **at that location. Two places may have the same hue (e.g., blue) telling you they 'peak at the same time', but the one with a more saturated version of that specific hue tells you it has more total biomass on the ground than the other location. That overall lack of vegetation is why the deserts of the US southwest are dark(ish), as are the polar regions.

* * *

  
A Classification of Temporal Static Maps
Monmonier (1990) proposed strategies for the visualization of geographic time-series data on static maps. He distinguished:

TYPE #1: Dance Maps show multiple time states on a single (static) representation, like foot-position diagrams used in ballroom dancing. Dance maps have the advantage of being easy to read because they directly and explicitly show a sequence of events and, thus, are a great choice for showing movement of discrete objects (like airplanes or animal migrations), especially if you only have a few objects. And unlike Chess Maps and Changes Maps (below), they can also show many time periods on a single map: for example, the map of the shift in the population center of the US over 200%2B years.   


![cruzleft][10]  


  
They also explicitly encode rates of change if they record data at regular intervals: You can see the shift of the US population has accelerated in recent decades.

[![centerPOP][12]][12]  


  
Dance maps, however, will not work if you're not showing movement. For example, you cannot use these to show change in attributes attached to location (like GPD of countries) or changes in geographic 'data fields' like air temperature. 

TYPE #2: Chess Maps show multiple time slices or “states,” and include popular methods such as the small multiple (small maps in a row or a grid). The advantage of the small multiple approach is that (1) you can show many time periods, and (2) the original data are shown and recoverable unlike Change Maps (below). Importantly, small multiple/chess maps can also show any kind of geographic change (change in *position*, *attribute*, or *existence*). However, these maps require a huge amount of mental work on the part of the map reader since 'change' is not actually encoded anywhere - it has to be deduced by the reader who does this by rapidly scanning back and forth among the images trying to discern what, exactly, has changed and where. 

![chessBoard][12]

In fact, this change-detection task is so hard it is a classic puzzle you might find in something like *Games Magazine*: the "find what is different between these two complex images'" challenge. Not convinced? How long does it take you to find the differences above? Are you certain you found all of them? This mental workload is the single biggest disadvantage of chess maps.

TYPE #3: Change Maps display the change (or difference) between two time periods, such as the percent increase in population over a 10-year period: The map doesn't show either time period, it shows the numerical difference between them. The advantage of these is that they "do the math for you" and directly show how much change has occurred. By adding color, like the example below, at a quick glance you can see the large patterns of change (areas that got colder and warmer). As mentioned above, on a chess map (above) seeing these changes requires much more work since you have to scan back and forth between the images to "uncover" what's be been changed, whereas a change map (here) exists to show you precisely what has changed (the "difference"). The problem is that change maps are really only good for showing two time periods, or one time period compared to an average—they're inherently binary—and unlike chess maps or dance maps cannot show more than two time periods.

[![tempChange][14]][14]

* * *

Isochronic Maps and Temporal Cartograms

Isochronic maps and temporal cartograms are pretty cool, to be honest. They've also been around for over 150 years and use space/distance on the map to encode time. 

Traditional area cartograms (aka "area-by-value maps") are well-known maps that distort space to achieve some desireable outcome like a uniform population density. By comparison, a temporal cartogram distorts or re-projects space to create outcomes like equal travel times. Distance on these maps is used as a way to represent travel times from an origin city or subway station. Vasiliev (1997) identifies "time as distance" maps where physical space is held constant and time is transformed, aka "isochronic maps"; and "space as clock" maps where time is held constant and space is transformed. 

![isochronicMap][14]  


  
Isochronic Map #1: Created by [Erwin Raisz][15] (1948) this map plots lines of equal travel time to fit 'normal' geography - the base map of the USA is readily recognized. Lines of equal travel time are called isochrons. Note how the Appalachian Mountains create a noticeable ripple in the pattern - even today they are are a major barrier for east-west travel. Note also that ships were faster than land travel in 1800, creating a bias toward the coasts.

[![tsunami][17]][17]  


  
Isochronic Map #2: This recent map made by NOAA of the [travel time of the Indian Ocean tsunami][17] is the same concept as the Raisz map above, just made with more powerful tools. Indeed, GIS now allows for some [very impressive travel analysis][18] (isochron = line of equal travel time).

[![CardenTube][20]][20]  


  
Temporal Cartogram #1: This [very cool interactive map of the London Tube][20] map (be sure to click on one of the lines/stations) distorts geographic space in order to create uniform travel times: The subway stations re-arrange themselves based on how far they are from each other in travel time not in geographic space. Created by the the very talented [Tom Carden][21].

![huffman_airfare][22]  


  
Price Cartogram #1: This beautiful and innovative map created by [Daniel Huffman][23], compiled thousands of airline searches to create a "topography" of airline prices from London's Heathrow airport to anywhere in the world. As a first year MS student, Daniel won a prize in the [2008 CaGIS map competition][24] for this effort.

* * *

Except where otherwise noted, content on this site available under a [Creative Commons 3.0 License][25]   
.

 [1]: http://web.archive.org/web/20100204055532/http%3A/www.geovista.psu.edu/members/maceachren/
 [2]: http://web.archive.org/web/20100204055532/http%3A/www.markmonmonier.com/
 [3]: http://web.archive.org/web/20100204055532/http%3A/www.geo.uzh.ch/en/units/giva/about-us/staff/sara-fabrikant/
 []: http://web.archive.org/web/20100204055532/http%3A/strangemaps.files.wordpress.com/2007/12/minardmap.jpg
 [5]: http://web.archive.org/web/20100204055532/http%3A/strangemaps.wordpress.com/2007/12/31/229-vital-statistics-of-a-deadly-campaign-the-minard-map/
 []: http://web.archive.org/web/20100204055532/http%3A/www.esri.com/mapmuseum/mapbook_gallery/volume19/mining1.html
 []: http://web.archive.org/web/20100204055532/http%3A/www.esri.com/mapmuseum/mapbook_gallery/volume19/mining1.html
 [8]: http://web.archive.org/web/20100204055532/http%3A/www.esri.com/mapmuseum/mapbook_gallery/volume19/mining1.html
 []: http://web.archive.org/web/20100204055532/http%3A/cartography2.com/my_images/NDVI-full.jpg
 [10]: http://web.archive.org/web/20100204055532im_/http%3A/cartography2.org/Chapters/page0/files/cruzleft-2.jpg
 []: http://web.archive.org/web/20100204055532/http%3A/www.census.gov/geo/www/cenpop/meanctr.pdf
 [12]: http://web.archive.org/web/20100204055532im_/http%3A/cartography2.org/Chapters/page0/files/chessboard.jpg
 []: http://web.archive.org/web/20100204055532/http%3A/www.weather.com/
 [14]: http://web.archive.org/web/20100204055532im_/http%3A/cartography2.org/Chapters/page0/files/isochronicmap.jpg
 [15]: http://web.archive.org/web/20100204055532/http%3A/en.wikipedia.org/wiki/Erwin_Raisz
 []: http://web.archive.org/web/20100204055532/http%3A/celebrating200years.noaa.gov/magazine/tsunami_database/traveltimemap.html
 [17]: http://web.archive.org/web/20100204055532/http%3A/celebrating200years.noaa.gov/magazine/tsunami_database/traveltimemap.html
 [18]: http://web.archive.org/web/20100204055532/http%3A/www.mysociety.org/2006/travel-time-maps/
 []: http://web.archive.org/web/20100204055532/http%3A/www.tom-carden.co.uk/p5/tube_map_travel_times/applet/
 [20]: http://web.archive.org/web/20100204055532/http%3A/www.tom-carden.co.uk/p5/tube_map_travel_times/applet/
 [21]: http://web.archive.org/web/20100204055532/http%3A/www.tom-carden.co.uk/
 [22]: http://web.archive.org/web/20100204055532im_/http%3A/cartography2.org/Chapters/page0/files/huffman_airfare.jpg
 [23]: http://web.archive.org/web/20100204055532/http%3A/cartastrophe.wordpress.com/
 [24]: http://web.archive.org/web/20100204055532/http%3A/www.cartogis.org/awards/acsm-cagis-annual-map-design-competition/mapdesign
 [25]: http://web.archive.org/web/20100204055532/http%3A/creativecommons.org/licenses/by-nc-sa/3.0/us/  