
[Permalink](http://web.archive.org/web/20110831135802/http://cartography2.org/Chapters/page6/OverviewAnimated.html "Permalink to Cartography 2.0 - Overview of Animated Maps")

# Cartography 2.0 - Overview of Animated Maps

by Mark Harrower
date: 09/01/09


SynopsisAnimated maps are an intuitive and appealing way to represent geographic processes because they allow us to represent time directly. Animated maps aren't just about showing change over time, and non-temporal animated maps (see below) are interesting alternatives to more traditional static maps. The chapters in this section on animated maps outline the historical origins of animated maps, the various kinds of animated maps that have been created, general insights from user testing, unanswered research questions in this field, and how we can get the most out of our animated and dynamic maps. 
Throughout this article and the rest of Cartography 2.0, discussion is woven around numerous examples. It is definitely worth spending some time viewing these maps, interacting with them (when possible), and trying to 

develop a critical eye for this kind of work. I will present a full range of examples—some successful, some not (including some of my own misfires)—since we can learn from past mistakes and equally be inspired by great work.&nbsp;Keywords  
animated maps, interactivity, time, change, geographic process, visualization, spatio-temporal data, user testing, movies, computers, web.  
&nbsp;  
Glossary  
*   interactive / interactivity: any manipulation of the display evoked by user input
*   pace: the amount of change per unit time
*   spatio-temporal data: geographic data that has both spatial and temporal coordinates or components
*   temporal granularity / resolution: the finest temporal unit resolvable
*   temporal interpolation: the creation of intermediate or missing data between moments for which data are known

  
Introduction
Animated maps, sometimes called movie maps or change maps, are primarily used to depict geographic change and processes. Cartographers have long been interested in the potential of map animation because representing complex geographic processes on static maps is difficult. 

Put simply, animated maps are appealing because we live in an animated world. Humans also possess an eye-brain system that is finely tuned to seeing (perceptually) and understanding (cognitively) motion and change. Static paper maps do not permit the direct representation of time because they do not change, which limits how much temporal information we can show on a static map; however, static maps can be used to represent time indirectly using either a single map (e.g., lines of equal travel time) or a series of maps (e.g., small multiples). By comparison, cartographic animations use display time to represent time allowing us to depict dynamic phenomena directly on our maps. Thus, there is a strong conceptual congruence between dynamic phenomena and dynamic representations of those phenomena. Lastly, animated maps can be very visually engaging and, anecdotally, folks seem to like watching them (see examples below).Animation in cartography is relatively new and fewer rules (and insights from research) have been established for making great animated maps than great static maps. While some early examples of animated maps are rough, to be fair, animated maps have only been around for 70 years while static (print/paper) maps have been around for at least 5000 years. Nonetheless, as we see below, animated maps are evolving at a rapid pace and on-going research is helping us to avoid design mistakes.
We know that map animation can be used to 

generate new insights into geographic processes that had been previously unrecognized using either static maps or statistical analysis.&nbsp; A good example of the power of animated maps to stimulate new knowledge is provided British cartographers [Danny Dorling][1] and [Stan Openshaw][2]. In their investigation of leukaemia rates in northern England, previously unrecognized hotspots (localized in both space and time) emerged only after these data were animated. The cancer hotspot in a specific area lasted only a few years and had been missed in previous static map analysis because the temporal component of the data had been collapsed, thus “grossly diluting situations such as these by amalgamating years of low incidence with a pocket of activity” (Dorling and Openshaw, 1992, 647). The animation also revealed a second unexpected process, which they described as a “peculiar oscillation” between leukemia cases in Manchester and Newcastle with an approximately five-year periodicity. Fresh insights such as these provide a useful starting point for more formal spatial analysis.&nbsp; 
The need for animated maps is further underscored by the recent and unparalleled explosion of digital geospatial data—

much of it time-series data. Fortunately, the simultaneous and rapid development of the World Wide Web and affordable, high-performance personal computers (and mobile devices) has made animated maps far easier to make, distribute, and view. As a result, animated maps have gone from being painstakingly crafted novelties to commonplace digital documents. Making animated maps interactive further extends their utility and allows the reader to “go into the map” and (in theory) change the map to suit their needs. The amount of interactivity, or control, the reader has over the animated map has steadily increased over time as technology permits (Figure 1), and ranges from none (e.g., weather map on TV) to near total (e.g., geovisualization system for epidemiologists).  
![Figure1][3]  
Figure 1: The history of animated maps and what users can do with them is in large part dictated by the storage medium / technology available at the time: celluloid film, VCR, CD-ROM, and Web. Like many other areas of GIScience, the move to computers in the 1980s allowed for much more interactive and versatile animated maps, while a decade later the migration to Web-based systems potentially gives users the ability to make animated maps on-demand (from distributed and/or real-time data).

  
Almost any kind of map can be animated: weather maps of air temperature, choropleth maps of population density, graduate symbols maps of income, and so on. Major research topics within map animation over the last 20 years include (1) methods for animating time-series data, (2) methods for animating across attributes of data, (3) methods for representing uncertainty and data quality in animated maps, (4) the design of effective temporal legends and controls, (5) the identification of the visual variables of animation, and (6) methods for temporal interpolation and smoothing of sparse datasets.

Learning from Others: Some animated maps from the past 40 years

Below is a selection of classic and contemporary animated maps. Not all of them are brilliant or beautiful, but we can learn something from each of them. In most cases these maps are selected to demonstrate some kind of pioneering technique or approach to representing geographic data, a clever user interface (UI), or sometimes what not to do.&nbsp;I don't mean for this to be the definitive list, but it does highlight much of the work done in animated mapmaking in the past two decades. 

As a historical note, some of these maps have been eclipsed by time, which is inevitable but also sad since they paved the way for many of today's great maps. The early maps on the list are also noteworthy (and perhaps a bit rough to our eyes today) since there were few expectations of what an animated map ought to be like. 

As a historical-technical note, some of these maps are frozen in technological time and sometimes require software and hardware from their eras that few folks have anymore. Cartography 2.0, thus, is a small attempt to preserve these early maps and bring them to a larger audience who have only recently jumped into digital cartography and may not have known these maps the first time around.

Related Material

1. For a deeper look at pioneering animated maps and the authors behind those maps, be sure to read the [History of Animated Maps][4] article that offers more early examples.

2. For a more academic overview of animated maps--and a summary of the important research behind many of the ideas here--have a look at [The Role of Map Animation in Geographic Visualization][5] (PDF) written by [Sara Fabrikant][6] and myself.  
  


* * *

  
[![dreadful][8]][8]  
[United States Precipitation Anomalies: 1900-1988][8]  


  
This map shows exactly what not to do with an animated map. It depicts climate model data (precipitation variations) and runs so comically fast it is completely illegible: Just try remembering something from this map. How does 1932 compare to 1971? How does Florida compare to California? I'm not sure what the author was hoping for, but this map tells us something important: Often we have to generalize/aggregate our data, and presenting too much "raw" disaggregate data, too quickly, in crazy bursts of color does little for your audience.&nbsp;

The Solution: (1) Slow down the pace of the map, (2) aggregate the data into longer (more stable) signals, possibly with a moving average approach, and (3) use a logical diverging color scheme (red = dry, through white, to blue = wet). Right now the map uses an inherently un-orderable qualitative color scheme (which is bad for ordinal data, which is, well, ordered).

Source:&nbsp;NASA&nbsp;Goddard Space Flight Center [Scientific Visualization Studio][9]&nbsp;(1998)  


* * *

  
[![sst][11]][11]  
[MODIS Sea Surface Temperature Highlighting the Gulf Stream (2002 to 2006)][11]&nbsp;  


  
The first and second map on this list are produced by the same folks but demonstrate just how far the technology has evolved in less than a decade, as well as how much better we understand things like pace and viewing perspective. Although hefty in size, this new breed of glossy, high-definition animated maps (in 720p or 1080p HD) offers astonishing detail and the potential for insights into massive geo-datasets.&nbsp;

On this map you can watch 6 years of sea surface temperature data: See how large-scale structures in the temperature of the ocean clearly emerge including the general north-south gradient, the strength of the Gulf Stream, and seasonal pulsing of the oceans' temperatures. The colors are highly effective and really no legend is needed, which is a good thing because it reduces the need to divide our attention among multiple things on-screen at once (called the "[split attention effect][12]"). I like the subtle details that can be seen in these structures because of the good call to use a continuous (unclassed) color scheme. This map underscores how great an animated map can be when you "get it right."

Source: NASA&nbsp;Goddard Space Flight Center&nbsp;[Scientific Visualization Studio][13]&nbsp;(2006).  


* * *

  
![Tobler][14]  
Urban Growth Model and Animation, Waldo Tobler (1970)  


  
In 1970 [Waldo Tobler][15] created and published this oblique-perspective 3D animation showing both historic and anticipated population growth in Detroit: It's hard to overstate how far ahead of its time this animated digital map was. This was a major achievement given how rudimentary computers were then—Tobler had to write all of the code himself because mapping software didn't exist, nor did the modern graphic user interface, let alone animated mapping software. Even more remarkable was that Tobler’s map was not created to present known facts, but rather was a research tool to better understand the process itself, an exploratory activity that today would be recognized as [Geovisualization][16]. I know of no surviving versions of this map, which I believe was shot to celluloid film, but if anyone has a copy, please [let me know][17].

* * *

  
[![streamVIz][19]][19]  
Watch a [Narrated Introduction][19] &nbsp;  
Direct Link: [Flood! On the upper Missisippi and Missouri Rivers][20]  


  
This map was created by Matt Bloch of the New York Times when he was a graduate student at the University of Wisconsin. Built in Flash, it incorporates a number of innovative data filtering/processing tools allowing us to both see both raw and standardized data for easier comparisons. It is a very elegant interface. I'm a big fan of his hybrid legend%2Bdata classification tool (which supports both unclassed and classed color schemes). Another useful feature is the ability to hover over individual locations and "drill down" through the data, even while the animation is playing. Watch the narrated introduction to learn more about this map.

Source:&nbsp;[Matt Bloch][21]&nbsp;(2004)  


* * *

  
![BallotBank2][22]

  
Ballotbank is a very rare example of a map that allows users to adjust the "temporal granularity" of the animation so that the amount of time that each frame represents (the "thickness" of the temporal slices) is easily adjustable. Why is this a big deal? Because (1) there is no obvious best temporal granularity for most datasets—Do the data make more sense if we use 15-minute time slices or 60-minute? Or maybe we should look at it as weekly slices?—and (2) what we see in our animated maps is largely a product of how the data have been aggregated, both spatially and temporally. Unfortunately, for most animated maps the decision to use a single temporal granularity has enormous implications for what we see in these maps—how change is depicted—and, thus, what we think we know about the world. For example, if I had a noisy dataset that was drowning out a larger trend, I would use thicker temporal slices (or a moving average) for suppression of noise.&nbsp;

While the world of cartography has long been aware of the analogous spatial problem (e.g., what sized spatial units to use in a choropleth map—counties? states? countries?—and the well-studied Modifable Area Unit Problem), Ballotbank shows that a similarly difficult problem exists when trying to decide how to present temporal geographic data. In other words, the same data can be made to show very different "facts" based on both the choice of base geography and temporal granularity. I would love to see this kind of temporal aggregation control offered on many more animated maps, but, so far, I know of no others. This bothers me, as much as if GIS could only work with country-level data.

Source: [David Heyman][23] (2006)  


* * *

  
[![aids2][25]][25]  
[New AIDS Cases 1993-2000][25]  


  
This map uses *visual benchmarks* as a way to potentially help map readers better understand the data (and the changes depict therein). The user can show the max, min, and average rates of HIV infection to help answer questions such as "In what year did Spain reach it's max rates?" and "Is that the same year as Austria?". The dynamic visual benchmarks allow the user to display one time period with the green solid circles and another time period (ahead or back in time) with the black hollow circles: The size disparity between them captures rates of change and allows users to compare rates of change across the map at a glance.

The problem with this map, as I learned from extensive user testing, is that even with just a few circles changing at 5 frames per second, there is a lot of information to absorb here in very little time and, even with looping on, most users resort to stopping the map and manually advancing frame-by-frame to answer questions. The max, min, and average benchmarks were more helpful than the dynamic ones.

One thing I've learned from user testing (and reading about the work of others) is that users want and need some basic map controls, specifically stop, play, frame-by-frame, and looping. Looping allows users time to watch the animation several times, which is often required before patterns become obvious (in more technical terms: it gives users time to rehearse and integrate this new visual information, e.g., [working memory][26], into longer-term knowledge schemata).&nbsp;

Source:&nbsp;[Mark Harrower][27]&nbsp;(2001)  


* * *

  
[![Freedom_Atlas][29]][29]  
[World Freedom Atlas][29]  


  
Created by the very talented Zach Johnson as a geographic visualization tool for exploring socio-economic and political data, the World Freedom Atlas is more than just an animated map (it's really a full-fledged visualization demo app). Zach was motivated to include numerous powerful yet underused data probing, graphing, and mapping tools. For example, the ability to create highly interactive difference maps (e.g., the difference between 2000 and 2005 data) that allows the user to brush these difference maps through time is very useful, as is the ability to create linked bivariate, multi-temporal choropleth maps. Freedom Atlas is also noteworthy for its ability to handle both quantitative and qualitative datasets with equal aplomb: qualitative data are often the really interesting datasets, but few mapping systems can handle these data.

Source: [Zachary Forest Johnson][30]&nbsp;(2007)  


* * *

  
[![LakeMichiga][32]][32]  
[Lake Michigan Currents, 1998][32]  


  
This map is a great example of&nbsp;Tufte’s “Micro/Macro” Principle (Tufte 1990) that states an overall "macro" impression or message can be relayed through a great volume of tiny "micro" details. He notes that in many graphics, large volumes of actual data detail can reveal interesting overall patterns and, although it seems like a contradiction, a graphic can actually be made simpler and more coherent by adding more real data detail. So while this map of circulation patterns in Lake Michigan contains hundreds of individual symbols, the symbols perceptually merge to form larger circulation structures (gyres) that pulsate according to the prevailing wind direction and strength (note the very clever wind arrow symbol).&nbsp;

Letting the map loop a few times allows us to see all sorts of subtle space-time patterns (and the sequencing of those behaviors) that would be virtually impossible to notice on static maps, small multiples, or an Excel spreadsheet. The use of "comet tails" behind the particles also helps to convey relative speeds, even on the static image above. While the graphic design of this map is a bit rough, it is nonetheless a very effective presentation of the data.

Source:&nbsp;[D. Schwab and D. Beletsky][33] (NOAA)&nbsp;(1998)  


* * *

  
[![Acevedo_SFBay][35]][35]  
[Time-series Animation Techniques for Visualizing Urban Growth][35]  


  
William Acevedo and Penny Masuoka devloped this&nbsp;highly smoothed (through temporal interpolation) and&nbsp;generalized image of urban growth in the Bay Area over the past 200 years. The map is remarkable in part because of their careful extraction of an estimated urban footprint from disparate historic sources (something which wasn't systematically recorded during the early years of the animation). It's also noteworthy because, although this growth process is undoubtedly&nbsp;complex and heterogeneous, their map is still easy to understand and the trends are easily grasped. I suspect this is partially because they used hundreds of individual frames so&nbsp;that the amount of change between frames is small: In fact, over 90% of the frames of this animation were interpolated from known data points (a difficult and some would say over-leveraged position).&nbsp;

One of the things I like here is that their animated&nbsp;map consisted of only two classes—urban and non-urban—in order to more clearly show the rapid (and non-linear) urban growth rates of the last 200 years. No attempt is made to characterize differences within the&nbsp;urban class (e.g., retail, residential, industrial). By not&nbsp;depicting changes within the city, the reader is free to&nbsp;focus on the relationship between the city and the&nbsp;surrounding county and the shape of the urban expansion. Note as the map plays how rapid the urban footprint of these cities expands after the 1940s with the rise of a commuter culture and the concurrent development of the Interstate highway system.

Source: [William Acevedo and Penny Masuoka][36]&nbsp;(1997)  


* * *

  
![ESV][37]  
Watch a [Narrated Introduction][38] to the Earth Systems Visualizer (ESV)  


  
This map shows two forms of data filtering—temporal brushing and temporal focusing—which allow the user to select subsets of the data in order to more clearly show trends that operate on different time scales. I created this in my first year of grad school and wouldn't necessarily advocate either the overly clunky UI (I'd use pulldowns and proper radio buttons for example) or the intrusive music and sound effects that seem especially cheesy to me now (!!). Nonetheless, I'm still happy with brushing and filtering as core concepts of map animation. Be sure to watch the narrated tour.

Source:&nbsp;[Mark Harrower][39] (1998)&nbsp;  


* * *

  
[![Atlanta_FLight][41]][41]  
[Animated Air Traffic Atlas (Atlanta Hub)][41]  


  
This map shows 24 hours of air traffic in and out of Atlanta's airport. Like the map of Lake Michigan currents above, this map makes great use of many tiny details to allow larger coherent patterns to emerge. Note how animating this data clearly reveals corridors that planes follow, the lull in flights during the middle of the night (except for west coast red eyes that left late the night before), and the way in which the morning wave of flights breaks across the time zones. The map, unfortunately, also demonstrates the problem of split attention in which it is difficult to watch both Atlanta and the clock in the lower left, although the analog clock face is definitely the right choice since they can be read faster than a digital clock.

NOTE: A similar series of animated maps of air traffic have also been created by the super talented [Aaron Koblin][42]. To the best of my knowledge, each of these maps was developed without knowledge of the other. I present the Peterson map here simply because it pre-dates the Koblin maps.

Source: [Michael Peterson][43]&nbsp;(2004)  


* * *

  
[![HealthVIz2][45]][45]  
[Slideshow Introduction of HealthVis][45] (to run Healthviz, see link below)  


  
HealthVis was created in the early days of digital map animation, yet it incorporated advanced ideas that even now, 15 years later, are rarely seen. HealthViz was designed to help epidemiologists explore the spatial and temporal patterns in diseases among the entire population of the United States, as well as by specific groups (by gender and race), allowing for comparisons of the geography of mortality from various cancers and the risk factors associated with them.&nbsp;

The system also has a great implementation of data focusing of both univariate and bivariate maps, allowing researchers to explore potential causal relationships between, for example, poverty and lung cancer of the population as a whole and of the most at-risk subgroups. Healthviz allows users to answer questions like *"Are there regional geographic differences between cancers and risk factors, and do those patterns/relationships change over time?"&nbsp;*

Source: [MacEachren, Howard, Boscoe][46]&nbsp;(1996)  


* * *

  
[![airlineDisasters][48]][48]  
Watch a [Narrated Introduction][48]  
Direct Link: [Commerical Air Disasters 1950-2003][49]  


  
Continuing with the airline theme, this animation created in 2004 by three undergrads at UW-Madison allows us to view 53 years of airline accident data and is a great example of an underused technique called "temporal re-expression." This map shows the data sliced/aggregated by different intervals of time, specifically accidents by year, by month, by day or by hour. Sometimes coherent patterns can be hard to pick out. However, by creating temporal composites wherein all of the accidents that occured on Mondays are shown at once, followed by all of the data for Tuesdays, and so on, you can start to ask interesting questions and see patterns emerge from the data. For example, you could ask "Are there more mechanical-related accidents on Mondays than on Fridays?" or "Are there more weather-related accidents in December than in June, generally speaking?"

I'm also a big fan of the introduction, the audio track, the "investigative folder" graphic design, and the arching, elegant temporal legend along the bottom of the map.&nbsp;Watch the narrated introduction to learn more about this map.

Source: [Bratz, Stephenson, and Nienow][50]&nbsp;(2004)  


* * *

  
[![SeaIce][52]][52]  
[A Tour of the Cryosphere][52]  


  
There is a lot to like about this beautiful, professional look at the frozen parts of our planet and the science that is fueled by our new wealth of digital data collected by NOAA satellites. Let me highlight the things that I think work really well here:

1. Labels and narration: Both direct the viewer's attention to the important aspects of the data, and despite the terrabytes of satellite data here, one never feels overwhelmed because what we're looking at is explained for us. This underscores [Mayer's insights][53] from cognitive testing that audio and visual stimuli should reinforce each other, not duplicate.

2. Careful Use of Different Map Scales:&nbsp;The use of scale transitions is a nice way to show how global trends are connected in a cause-and-effect cycle with processes at a local level: The zoom into one area of Greenland and the explanation of why this is troubling helps to add salience to science.

3. Change % Isoline:&nbsp;The use of percent change isolines here shows how much smaller the sea ice is from longer term averages: This is a killer feature since people would otherwise be overwhelmed by the busy, complex data. By using these isolines the take home message is really clear: Sea ice is shrinking.&nbsp;

4. Soundtrack:&nbsp;Normally I'm not a fan of music in animations, but in this case I think it really works and helps to elevate this to the level of a science documentary. Ending the map with a series of questions or unknowns helps to heighten the tension in this and explain the need for further research (e.g., funding). This is pro stuff.

Source:&nbsp;NASA&nbsp;Goddard Space Flight Center&nbsp;[Scientific Visualization Studio][54]&nbsp;(2005)  


* * *

  
[![Bloch_Lab1][56]][56]  
Watch a [Narrated Introduction][56]  
Direct Link: [Evening flights from Madison, Wisconsin][57]  


  
Rounding out our look at animated maps about airline traffic (this wasn't planned), this map shows departures from the airport at Madison, Wisconsin, and has a polished feel and innovative "magnetic" controls&nbsp;which allow for both coarse and fine motor control from the same UI element with a intuitive motion (watch the demo for an example). This map also underscores the point that we should never, ever build more buttons, bells, and whistles than the mapping task at hand needs. While we can load our maps up with extra controls, they are more likely to confuse the user, which is why I believe we do our best work when we build just as much map as is needed, and no more.

Source:&nbsp;[Matt Bloch][21]&nbsp;(2004)  


* * *

  
[![Flyover_Labels][59]][59]  
[Flyover Map with 3D Labeling][59]  


  
Ben Sheesley and I created a series of 3D fly-over maps designed to combat user disorientation and to help make the generic fly-over map more memorable and useful as a general reference map (e.g., What are you looking at? Where have you been?). This map doesn't depict a real location; it is completely synthetic and created by us in a few hours. Indeed, the latest 3D landscape modeling software is truly astonishing in the detail, realism, and degree of control it gives the designer: we played with fluid-dynamic controls over the water bodies, gas-diffusion settings for the atmosphere, and advanced lighting engines (it's a lot of fun!).

Although we initially had high hopes for the addition of labels to the scene based on solid theoretical insights about how people learn and navigate, we found through a series of experiments that these labels didn't help users and in fact added "just one more thing for me to look at" as one test subject put it. Fortunately, the other three orientation cues we designed did significantly improve spatial orientation and spatial recall for the subjects who watched these maps. I am also hopeful that perhaps with a better implementation or a slower movie, labels could be useful, much as they are on 2D maps. Have a deeper look at this research, and the new design issues involved in creating 3D Fly-Over Maps.&nbsp; 

One design note: When possible we tried to have the labels mimic the 3D the shape or position of the feature (e.g., stairstep "Tucker's Cliff"), much as cartographers have long tried to use labels that mimic/suggest geography on 2D maps. We're not sure if this is quantifiably helpful (it might be) but in any case we liked the way it looked.

Source: [Harrower and Sheesley][60] (PDF 2007)  


* * *

  
[![IIPS_lowres][62]][62]  
[IBM's DeepThunder: 3D meteorological animation][62]  


  
This animation was state-of-the-art for the mid 1990s, especially considering it was using real time weather data. What makes this map interesting is also what makes it really hard to understand: There's just too much data for a small, low-res display, at least for a non-expert user like me (meteorologists have more experience interpreting very complex maps). The biggest concern I have is that the clouds, although semi-transparent, still obscure too much of the map and are rendered with far, far too much vertical exaggeration—they'd been hundreds of miles high according to this map. So what's the solution? I'd say show just precipitation (colored isoline blobs) and windspeed (colored arrows) in one map, and show the 3D clouds in another. I know this will kill the potential for seeing how cloud structure related to winds and precipitation, but to be honest, that relationship isn't really made clear here anyway, again, at least not to my eyes.

Source: [Christidis and Treinish][63]&nbsp;(1996)  


* * *

  
[![Monmonier][65]][65]  
[US Daily Newspaper Production in the 20th Century][65]  


  
Now almost 20 years old, this example of the "Atlas Touring" concept by Mark Monmonier was a pioneering effort that showed how the user’s attention can be directed through complex data presentations with the use of flashing and sequencing to draw connections between maps and graphs. At 20 minutes in length, and because the user has no control over the pace of the map (nor can they interact with it), this map is in many ways more like a traditional documentary or television show than an interactive map of today, albeit one that proceeds at a very slow pace. Nonetheless, this map (and the companion map "Elect Women in the USA") work hard to break the "single best map" paradigm that previously had so dominated traditional cartography: By showing the same data multiple ways, as both maps and graphs, in different groupings and arrangements, Monmonier reminds us that there is no single best way to map data and that a fuller understanding is possible when we take the time to really explore a series of related datasets.

Source: [Mark Monmonier][66]&nbsp;(1990)  


* * *

  
![boston][67]  
[Microsoft's Virtual Earth][68] (click '3D' tab once it loads, won't work in the Mac OS)  


  
As a result of the wonderful arms race between the mapping titans Google and Microsoft, we have seen an astonishing amount of development in the world of geographic animation and 3D mapping. Although MSN's Virtual Earth is "animated" in the sense that it provides the ability to fly over a landscape, it is much, much more than just an animated map. What is so special about these virtual globes is that we now have (1) this kind of data (2) distributed for free (3) over networks that are now fast enough&nbsp;(4) to play on computers fast enough to (5) allow users an unrestricted ability to explore and interact with&nbsp;(6) distributed, linked, heterogenous content (most of which was never collected in the first place for this kind of application, but has been harvested/recruited into service here), so that&nbsp;(7) the user themselves can become part of the chain of data creation and sharing.&nbsp;

That all of this runs in a standard web browser on a low-end laptop is (I can't stress this enough) truly mind-blowing. If you're too young to remember [command line Arc Info][69] or 2400 baud modems, trust me, it's better than any of us could have hoped for merely 10 years ago. For a deeper discussion (it's not all roses) see the section on 3D Virtual Globes.&nbsp;

Bottom line: Flying around richly-detailed (and ever-growing) virtual cities like Superman has yet to get boring.

* * *

Except where otherwise noted, content on this site available under a [Creative Commons 3.0 License][70]   
.

 [1]: http://web.archive.org/web/20110831135802/http%3A/www.shef.ac.uk/geography/staff/dorling_danny/
 [2]: http://web.archive.org/web/20110831135802/http%3A/www.ccg.leeds.ac.uk/people/s.openshaw/
 [3]: http://web.archive.org/web/20110831135802im_/http%3A/cartography2.org/Chapters/page6/files/figure1.jpg
 [4]: http://web.archive.org/web/20110831135802/http%3A/cartography2.org/Chapters/page12/HistoryMapAnimation.html "History of Animated Maps"
 [5]: /web/20110831135802/http://www.google.com/url?q=http%3A%2F%2Fwww.geography.wisc.edu%2F~harrower%2Fpdf%2FHarrower_Fabrikant.pdf&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzckqeycQTuLtqvQcPgX5Rqkoe_lDw
 [6]: http://web.archive.org/web/20110831135802/http%3A/www.geo.uzh.ch/en/units/giva/about-us/staff/sara-fabrikant/
 []: http://web.archive.org/web/20110831135802/http%3A/svs.gsfc.nasa.gov/vis/a000000/a000100/a000178/a000178.mpg
 [8]: http://web.archive.org/web/20110831135802/http%3A/svs.gsfc.nasa.gov/vis/a000000/a000100/a000178/a000178.mpg
 [9]: http://web.archive.org/web/20110831135802/http%3A/svs.gsfc.nasa.gov/vis/a000000/a000100/a000178/
 []: http://web.archive.org/web/20110831135802/http%3A/svs.gsfc.nasa.gov/vis/a000000/a003300/a003389/a003389_H264_1280x720.mp4
 [11]: http://web.archive.org/web/20110831135802/http%3A/svs.gsfc.nasa.gov/vis/a000000/a003300/a003389/a003389_H264_1280x720.mp4
 [12]: http://web.archive.org/web/20110831135802/http%3A/en.wikipedia.org/wiki/Split_attention_effect
 [13]: http://web.archive.org/web/20110831135802/http%3A/svs.gsfc.nasa.gov/index.html
 [14]: http://web.archive.org/web/20110831135802im_/http%3A/cartography2.org/Chapters/page6/files/tobler.jpg
 [15]: http://web.archive.org/web/20110831135802/http%3A/en.wikipedia.org/wiki/Waldo_R._Tobler
 [16]: http://web.archive.org/web/20110831135802/http%3A/www.elsevier.com/wps/find/bookdescription.cws_home/703524/description#description
 [17]: mailto:mark%40axismaps.com
 []: http://web.archive.org/web/20110831135802/http%3A/maps.grammata.com/flood.html
 [19]: http://web.archive.org/web/20110831135802/http%3A/cartography2.org/movies/Flood.mov
 [20]: http://web.archive.org/web/20110831135802/http%3A/maps.grammata.com/flood.html
 [21]: http://web.archive.org/web/20110831135802/http%3A/maps.grammata.com/
 [22]: http://web.archive.org/web/20110831135802im_/http%3A/cartography2.org/Chapters/page6/files/ballotbank2.jpg
 [23]: http://web.archive.org/web/20110831135802/http%3A/www.axismaps.com/
 []: http://web.archive.org/web/20110831135802/http%3A/www.geography.wisc.edu/%7Eharrower/dissertation/files/Europe41_AIDS.html
 [25]: http://web.archive.org/web/20110831135802/http%3A/www.geography.wisc.edu/%7Eharrower/dissertation/files/Europe41_AIDS.html
 [26]: http://web.archive.org/web/20110831135802/http%3A/en.wikipedia.org/wiki/Working_memory
 [27]: http://web.archive.org/web/20110831135802/http%3A/www.geography.wisc.edu/%7Eharrower/dissertation/
 []: http://web.archive.org/web/20110831135802/http%3A/freedom.indiemaps.com/
 [29]: http://web.archive.org/web/20110831135802/http%3A/freedom.indiemaps.com/
 [30]: http://web.archive.org/web/20110831135802/http%3A/indiemaps.com/
 []: http://web.archive.org/web/20110831135802/http%3A/cartography2.org/movies/LkMichcurrents.avi
 [32]: http://web.archive.org/web/20110831135802/http%3A/cartography2.org/movies/LkMichcurrents.avi
 [33]: http://web.archive.org/web/20110831135802/http%3A/www.glerl.noaa.gov/eegle/projects/p05/p05.html
 []: http://web.archive.org/web/20110831135802/http%3A/landcover.usgs.gov/urban/umap/movies/sf_bay450.mpeg
 [35]: http://web.archive.org/web/20110831135802/http%3A/landcover.usgs.gov/urban/umap/movies/sf_bay450.mpeg
 [36]: http://web.archive.org/web/20110831135802/http%3A/landcover.usgs.gov/urban/umap/pubs/asprs_wma.php
 [37]: http://web.archive.org/web/20110831135802im_/http%3A/cartography2.org/Chapters/page6/files/esv.jpg
 [38]: http://web.archive.org/web/20110831135802/http%3A/cartography2.org/movies/ESV_introduction.mov
 [39]: http://web.archive.org/web/20110831135802/http%3A/www.geography.wisc.edu/%7Eharrower/
 []: http://web.archive.org/web/20110831135802/http%3A/maps.unomaha.edu/AnimatedFlightAtlas/atl.avi
 [41]: http://web.archive.org/web/20110831135802/http%3A/maps.unomaha.edu/AnimatedFlightAtlas/atl.avi
 [42]: http://web.archive.org/web/20110831135802/http%3A/www.aaronkoblin.com/work/flightpatterns/
 [43]: http://web.archive.org/web/20110831135802/http%3A/maps.unomaha.edu/AnimatedFlightAtlas/ExampleAnimation.html
 []: http://web.archive.org/web/20110831135802/http%3A/www.geovista.psu.edu/grants/nchs/graphics/tester3.gif
 [45]: http://web.archive.org/web/20110831135802/http%3A/www.geovista.psu.edu/grants/nchs/graphics/tester3.gif
 [46]: http://web.archive.org/web/20110831135802/http%3A/www.geovista.psu.edu/grants/nchs/healthvis1.htm
 []: http://web.archive.org/web/20110831135802/http%3A/www.geography.wisc.edu/%7Eharrower/Geog575/AirDisasters2.swf
 [48]: http://web.archive.org/web/20110831135802/http%3A/cartography2.org/movies/Commercial_Airline_Disasters.mov
 [49]: http://web.archive.org/web/20110831135802/http%3A/www.geography.wisc.edu/%7Eharrower/Geog575/AirDisasters2.swf
 [50]: http://web.archive.org/web/20110831135802/http%3A/www.geography.wisc.edu/%7Eharrower/Geog575/AirDisasters2.swf
 []: http://web.archive.org/web/20110831135802/http%3A/svs.gsfc.nasa.gov/vis/a000000/a003100/a003181/a003181_720x404_vo.mpg
 [52]: http://web.archive.org/web/20110831135802/http%3A/svs.gsfc.nasa.gov/vis/a000000/a003100/a003181/a003181_720x404_vo.mpg
 [53]: http://web.archive.org/web/20110831135802/http%3A/www.psych.ucsb.edu/people/faculty/mayer/index.php
 [54]: http://web.archive.org/web/20110831135802/http%3A/svs.gsfc.nasa.gov/vis/a000000/a003100/a003181/index.html
 []: http://web.archive.org/web/20110831135802/http%3A/maps.grammata.com/evening_flights.html
 [56]: http://web.archive.org/web/20110831135802/http%3A/cartography2.org/movies/evening_flights.mov
 [57]: http://web.archive.org/web/20110831135802/http%3A/maps.grammata.com/evening_flights.html
 []: http://web.archive.org/web/20110831135802/http%3A/cartography2.com/movies/flyover_labels.mov
 [59]: http://web.archive.org/web/20110831135802/http%3A/cartography2.org/movies/flyover_labels.mov
 [60]: http://web.archive.org/web/20110831135802/http%3A/www.geography.wisc.edu/%7Eharrower/pdf/Harrower_Sheesley_CaGIS_2007.pdf
 []: http://web.archive.org/web/20110831135802/http%3A/www.research.ibm.com/weather/Olympics/OlympicsWeather.html
 [62]: http://web.archive.org/web/20110831135802/http%3A/www.research.ibm.com/weather/Olympics/OlympicsWeather.html
 [63]: http://web.archive.org/web/20110831135802/http%3A/services.alphaworks.ibm.com/deepthunder/faq.html
 []: http://web.archive.org/web/20110831135802/http%3A/cartography2.org/movies/DailyNewpapers.mov
 [65]: http://web.archive.org/web/20110831135802/http%3A/cartography2.org/movies/DailyNewspapers.mov
 [66]: http://web.archive.org/web/20110831135802/http%3A/www.markmonmonier.com/
 [67]: http://web.archive.org/web/20110831135802im_/http%3A/cartography2.org/Chapters/page6/files/boston.jpg
 [68]: http://web.archive.org/web/20110831135802/http%3A/www.bing.com/maps/
 [69]: http://web.archive.org/web/20110831135802/http%3A/en.wikipedia.org/wiki/Command_line_interface
 [70]: http://web.archive.org/web/20110831135802/http%3A/creativecommons.org/licenses/by-nc-sa/3.0/us/  