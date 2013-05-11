[Permalink](http://web.archive.org/web/20110711100218/http://cartography2.org/Chapters/page7/ConceptualizingTime.html "Permalink to Cartography 2.0 - Conceptualizing Time and Process")

# Cartography 2.0 - Conceptualizing Time and Process

by Mark Harrower
date: 09/08/09

Given that much of geovisualization / animation / interactive cartography is concerned with representing time, change, and geographic process...it begs the question: 
*What are TIME, CHANGE, and PROCESS? *

Although this might seem like a pointless philosophical exercise, it is critical to stop and actually think about what these concepts mean to us, because **how we conceptualize (think about) them will inform and constrain how we operationalize (use) them on maps. **The problem is that "time" and "change" are such basic, everyday things that we often take them for granted; they are self-explanatory, aren't they? Perhaps not. Furthermore, we often lack an adequate vocabulary to talk about these concepts and tend to use these terms interchangeably. 

Folks who have inspired much of my thinking on this: [Donna Peuquet][1], [Sara Fabrikant][2], [Daniel Dorling][3], [Max Egenhoffer][4], [Nancy Yattaw][5], [Gail Langran][6]

Maps are Geographic Caricatures

My basic advice in cartography is "Know at least a little about the thing you are trying to represent." Why? Because maps are [caricatures][7] of geographic data in which we must decide (regardless of whether the map is static or animated) **what are the most salient features that need to be emphasized**? Caricatures, while often seen as silly or amusing, are in fact brilliant forms of data filtering and reduction: The artist sees that which makes someone unique and instantly recognizable and eliminates other non-distinguishing data or features so that at a glance (and usually with a chuckle), we recognize the person. What's even more remarkable is that this is often done with extreme economy of linework; a few strokes, as in the case of the famous Alfred Hitchcock silhouette below, are all that are needed. This is a remarkably efficient use of ink, and a hallmark of great design.

![alfred-hitchcock-silueta](cartography2/images/alfred-hitchcock-silueta.jpg)


  
Like this portrait of Hitchcock, mapping requires we know how to eliminate 99.99999...% of the detail of the real world—which is full of tennis balls, raccoons, and coffee shops—in order to tease out that which interests us. Cartography, in that sense, is not about drawing things, it's about learning what you can do without. It's about trying to understanding the essence of the thing. If it is a map of air temperature, you need to know what air temperature patterns look like in the real world. For example, although our sampling and our [isolining algorithms][9] may lead to blocky, right-angled isolines, this is an artifact of our data/work and would be a very misleading way to represent air temperature. Knowing that we don't find right-angles in the spatial character of air temperature leads the skillled cartographer/meterologist to [manually smooth such features][10]. 

***Why do we need to understand our understanding of time?*** Because just as you wouldn't want to represent air temperature data on a choropleth map (that's just crazy), you equally wouldn't want to to suggest that air temperature only changes on the hour, every hour, simply because that is when the data you have was collected. While the data may only be collected at hourly intervals, we know that the underlying process is much more complex and in a constant state of flux. To suggest otherwise with your map is simply bad form. Indeed, mapping geographic processes—in which time is explicitly represented—requires the same level of understanding as we'd bring to our much more familiar spatial representations (point, lines, area, etc.) and *not some blind adherence to "the data."* Never confuse data for the real thing. 

For example, if you assume all geographic processes are composed of **"states"** and **"events,"** you're making a deep philosophical assumption about the nature of reality, and this would lead you, unwittingly and falsely, to show continuous change as discrete, jumpy steps. We'll pick this discussion up in a bit and see how it relates to the well-trodden debates around raster versus vector approaches in GIS.

Reality? What Reality?

*The goal of cartography is neither to discover nor to represent all of reality; if that were so, cartographers would have found alternate employment soon after air photographs became widely available* (Langran 1992, p. 28)

Another insight that is somewhat shocking is that cartography is not about realism. Thematic mapping, and even reference mapping, isn't the same a photograph. If you want to take photos to cover a news story on energy consumption, you might capture an image of cars on a highway. But on a map we might use giant colored circles covering the land and viewed from far off in space (e.g., looking staight down). Below is a [map of energy consumption and federal funding][11], and despite the fact that the world isn't actually, literally covered with giant colored circles, this map nonetheless is a succinct summary of a complex social phenomenon.

![](cartography2/images/arra_fundingmap1-1024x682.jpg)


  
Even icons used in referencing mapping are rarely as literal as a photograph; A popular way to indicate a park on a tourist map is a tepee tent although perhaps only a handful of parks actually have tepees, and of course, parks are much more than just tepees (semioticiains call these "associative map symbols"). Moreover, this tepee is extremely stylized and uses only 3 solid lines: As a result it can be shrunk way down in size and remain legible—a key requirement of references maps.  
  
![](cartography2/images/parkIcons.jpg)
  
**TAKE-HOME MESSAGE: **This means that our job as cartographers is not to simply photograph the world or to blindly mimic it. Rather, it is to create a visual abstraction that efficiently, and as accurately as possible, represents some aspect of the world. In order to do that, we need to know what it is that we're trying to capture in that representation in the first place. Hence our brief detour through an [ontological][14] discussion of the nature of time and geographic process. I know my description of the map-making process isn't a very [Brian Harley][15]-esque or [Denis Wood][16]-esque definition of mapping (red flags: "accurate", "real world") but it's where I'm coming from (i.e., a place with paying clients). Your mileage may vary.

Making Space for Time on our Maps

Maps have always shown time. The problem was that time often wasn't explicit nor central to the maps purpose. As a result, cartographers have tended to treat time as an attribute rather than as a field. In other words, many static maps if they make mention of time add it simply as a date (e.g., "Data collected in 2009") or as a simple time-stamp of events (e.g., a battle occured here in this year). The important thing is that time is not a structuring dimension, on par with space, but is rather an attribute attached to locations. As a result, fewer methods have been developed for depicting time than space and fewer “rules” have been generated to guide cartographers in their use of temporal information. 

![](cartography2/images/lakeshore_Animation.png)


  
Fortunately, with the advent of Geographic Visualization and computer-based animated maps (and more recently interactive web-based maps), time has become both easier to represent and more central to the map-making process. For example, the "time machine" function of the [UW Lakeshore Preserve Map][18] (above) allows us to peer into the past using successively older air photos to **peel back the layers of time** and answer the question, "What used to be here before they built this?" 

Kinds of Geographic Time 

Cartographers recognize that there are different kinds of geographic primatives: points, lines, areas, and volumes. We also know there are different levels of measurement in our data: nominal, ordinal, interval, and ratio. For example, the weather can be "warm" (a qualitative, categorical assessment) or it can also be described as 35C (a quantitative, numercial assessment). Folks have also realized that there are different kinds of time, analogous to these spatial and measurement distinctions. Below are some of the taxonomies devised so far:

Isard (1970) characterized four types of time: 

*   "universe time" which is absolute and linear, 
*   "cyclic time" such as diurnal patterns, 
*   "ordinal time" which records the relative ordering of events, and
*   "time as distance" in which the spatial dimension is used to represent time. 

  
Haggett (1990) describes four types of temporal change in geography: 
*   constants
*   trends 
*   cycles 
*   shifts 

  
Constants (i.e., long periods of no change) and trends (i.e., linear change) are long-term changes. Cycles describe recurring patterns and shifts describe sudden changes (not necessarily recurring). 
Stinton (1978): basic components of all geographic information **(1) time, (2) location, and (3) attribute.** 

Building on this, Peuquet (1994) presents a representational framework called TRIAD that represents geographic entities using **what, when, and where**. 

Events and States vs. Continuous Change 

Consider the following questions the next time you make an animated map: 

*When does something change? *

How much does it need to change to be considered "different"? 

Do you think of change as an ongoing, continuous process (e.g., changes in wind speeds) or as a series of defined states punctuated by discrete events (e.g., a recession)?

How you answer those questions will not just make a big difference in how you depict change and time on your maps, it'll also frame how you go about collecting your data in the first place. This distinction in your mind will inform **how often you sample** and **what degree of precision you need**. Clearly, your answer to these questions is driven in part by the nature of the thing you are studying (e.g., election results versus air temperature), but the point I'm trying to make is to step back and think carefully about how you think about the things you study.

This thinking is also driven in a sense by how close you are to your subject: We can all agree that there was fog at the airport today (an event), but we'd be hard pressed to claim we know the exact moment, to the second, when the fog event happened (that's a process). For me the fundamental distinction I make is can I draw a meaningful, crisp boundary around chunks of time (to create "states") or is there just so much going on in the data, or are the boundaires so fuzzy, that any such temporal boundaries would be artificial and misleading, in which case I'm dealing with a continuous process. 

All other things being equal, I require more time slices (a greater number of samples over time) to accurately represent continuous geographic processes on an animated map, although there are clever ways to do fancy space-time interpolation to fill in missing gaps if I only have a sparse data set to work with. Be warned though: interpolation is really just a "fancy guess" and is never as useful as actual, real data.

**So How Should I Depict Time on My Maps?** In the next two sections I cover how we can turn these concepts of time into useful maps—both static and animated—in the sections Representing Time on Animated Maps and [Representing Time on Static Maps][19].

* * *

Except where otherwise noted, content on this site available under a [Creative Commons 3.0 License][20]   
.

 [1]: http://web.archive.org/web/20110711100218/http%3A/www.geog.psu.edu/people/peuquet/
 [2]: http://web.archive.org/web/20110711100218/http%3A/www.geo.uzh.ch/en/units/giva/about-us/staff/sara-fabrikant/
 [3]: http://web.archive.org/web/20110711100218/http%3A/www.shef.ac.uk/geography/staff/dorling_danny/
 [4]: http://web.archive.org/web/20110711100218/http%3A/www.spatial.maine.edu/%7Emax/
 [5]: /web/20110711100218/http://www.questia.com/googleScholar.qst?docId=5001894510
 [6]: /web/20110711100218/http://books.google.com/books?id=2wVB8mU5CJkC&amp;dq=Gail%2BLangran&amp;printsec=frontcover&amp;source=bl&amp;ots=a6lwdLX2_5&amp;sig=TnHFJT4UhfRqw0_EulKYr2eer8E&amp;hl=en&amp;ei=QbXoSdqvFovGMtnWme4F&amp;sa=X&amp;oi=book_result&amp;ct=result&amp;resnum=1#v=onepage&amp;q=&amp;f=false
 [7]: http://web.archive.org/web/20110711100218/http%3A/en.wikipedia.org/wiki/Caricature
 [8]: http://web.archive.org/web/20110711100218im_/http%3A/cartography2.org/Chapters/page7/files/alfred-hitchcock-silueta.jpg
 [9]: http://web.archive.org/web/20110711100218/http%3A/indiemaps.com/blog/2008/06/isolining-package-for-actionscript-3/
 [10]: http://web.archive.org/web/20110711100218/http%3A/www.personal.psu.edu/cab38/GEOG321/08_isolines02/smooth.gif
 [11]: http://web.archive.org/web/20110711100218/http%3A/www.axismaps.com/blog/2009/04/arra-funding-map/
 []: http://web.archive.org/web/20110711100218/http%3A/www.axismaps.com/blog/2009/04/arra-funding-map/
 [13]: http://web.archive.org/web/20110711100218im_/http%3A/cartography2.org/Chapters/page7/files/parkicons.jpg
 [14]: http://web.archive.org/web/20110711100218/http%3A/en.wikipedia.org/wiki/Ontology
 [15]: http://web.archive.org/web/20110711100218/http%3A/en.wikipedia.org/wiki/John_Brian_Harley
 [16]: http://web.archive.org/web/20110711100218/http%3A/en.wikipedia.org/wiki/Denis_Wood
 []: http://web.archive.org/web/20110711100218/http%3A/lakeshorepreserve.wisc.edu/
 [18]: http://web.archive.org/web/20110711100218/http%3A/lakeshorepreserve.wisc.edu/
 [19]: http://web.archive.org/web/20110711100218/http%3A/cartography2.org/Chapters/page0/RepresentingTimeStatic.html "Representing Time on Static Maps"
 [20]: http://web.archive.org/web/20110711100218/http%3A/creativecommons.org/licenses/by-nc-sa/3.0/us/  