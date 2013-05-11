
[Permalink](http://web.archive.org/web/20110711100046/http://cartography2.org/Chapters/page12/HistoryMapAnimation.html "Permalink to Cartography 2.0 - A History of Animated Maps")

# Cartography 2.0 - A History of Animated Maps

by Mark Harrower
9/20/09

Overview  


  
Compared to static maps, animated maps have always been difficult to make, distribute, and access. The PC and Internet revolutions have greatly improved opportunities for animated maps, and a new era of on-demand animated maps has emerged in the past decade. To help make sense these rapid changes, I present a three-tier historical framework that identifies the key conceptual and technological developments of animated cartography related to the means of production, methods of distribution, and modes of use. Such a historical overview is largely missing from the cartographic literature and helps us to situate current developments and issues within a broader social and technological context. 

*Why do we need to know our history?* An in-depth look at the history of animated maps is useful for three reasons:

*   First, given the rapid technological changes of the last 20 years, it would be useful to take stock of recent developments within animated cartography and ask how did we get here. 
*   The future development and direction of animated maps can be informed by identifying the pivotal ideas and technologies of the last 60 years. 
*   Surprisingly few individuals shaped the development of map animation from the 1950s to the mid-1980s. The reach of the ideas proposed by key thinkers such as Thrower, Tobler, and Moellering often far exceeded the grasp of the available technology. It is, therefore, worth revisiting these foundational ideas now that the computational power exits to implement many of them.

  
This history of animated maps is very much tied to the history of computers. Early examples of animated maps were produced in the 1930s using hand-drawn, cel-based techniques borrowed from cartoon animation. Because this manual technique was exceptionally time-consuming, academic cartographers and computer scientists started experimenting with the potential of computer-assisted animation surprisingly early (late 1950s), and by 1970 [Waldo Tobler][1] had created a path-breaking oblique-perspective 3D animation of anticipated population growth in Detroit. Even more remarkable was that Tobler’s map was not created to present known facts, but rather was a research tool to better understand the process itself—an exploratory activity that today would be recognized as [Geovisualization][2].
In the 1970s, the advent of VCR technology meant that animated maps could now be copied and distributed easily and cheaply (compared to celluloid film). This technology also allowed map viewers rudimentary control over playback. However, it was not until the PC revolution of the late 1980s that animated maps finally came into their own: The desktop PC—with its graphical user interface, real-time interactivity, standardized file formats, and off-the-shelf software—finally armed cartographers with a powerful tool for making animated maps and viewers a means for watching and interacting with them. The last piece of the puzzle, product distribution, was solved by the rise of the Internet in the 1990s. No longer tied to physical media, Web-based animated maps can now be “made” on-demand and sent around the world in a blink of an eye at minimal cost to either the producer or the consumer. The drive to automate the production of maps (including animated maps) has been a significant topic of research in GIScience in the last decade and promises to compress the gap between raw geographic data and interesting animated maps of those data.

Although cartographers have been interested in the potential of animated maps for decades, until recently animated maps were relatively scarce because they were difficult to make, difficult to distribute, and difficult to view. It is only in the last few years that barriers to the widespread creation, distribution, and use of animated maps have been addressed. The PC revolution has given cartographers the means to more easily create animated maps, and map users a way to view animated maps. However, the reason why animated mapping is finally coming of age—a full 20 years after the PC revolution began—is the World Wide Web. Unlike paper maps, before the Web there was no practical or inexpensive way to allow millions of users to access animated maps on demand. Without easy access to an audience, animated maps are little more than a technological curiosity.

There are numerous examples of animated maps and I apologize if this history does not include specific (or beloved) examples. Rather, we'll use a framework for thinking about the history of animated maps as falling into four distinct eras of map functionality. Tthese historic periods are defined by what users can do with the animated maps of their day: Early on, users cold only “watch” (Era 1), then in the 1970s they could “control playback” (Era 2), followed by “control depictions” starting in the late 80s (Era 3), and finally map users could “author” their own animations (Era 4, today). Examples of specific animated maps are used to illustrate those developments. 

[![TimeLine550][4]](cartography2/images/HistoryMapAnimation/TimeLine550][4].jpg)  
(click to see large)

Making Animated Maps – Means of Production

Compared to static maps, animated maps have always been difficult to produce. The history of animated map production fits into three (overlapping) eras: (1) manual, (2) computer-assisted, and (3) computer-based production. With manual production, each frame of the animation (e.g., map) is drawn by hand. In computer-assisted production (from the late 1960s through the mid-1980s), computers are typically used to create the individual frames of the animation, but the process of assembling and filming these map frames is done using traditional (i.e., mechanical) cinematography. By contrast, in computer-based production the entire process, from creation to distribution, occurs digitally. Completely digital animation first appeared in the mid-1980s as both the software and hardware permitted.

Era #1: Manual Production

The first animated maps were produced by hand, drawn one frame at a time using techniques developed for cartoon animation. One of the earliest examples of an animated map is a 30-second black-and-white newsreel produced by the Walt Disney Company in 1940 (Peterson 1999). This map involved a massive expenditure of time and money because it required making thousands of drawings by hand. The Disney animation depicts the invasion of Warsaw by the Nazis in 1939 and is remarkable as much for its artistic quality as for its rhetorical value. Using a combination of oblique and map-view perspectives above a highly stylized (and largely inaccurate) map of Warsaw, this animation suggests how the Nazi army advanced and encircled the city. Figure 2 is a series of screen captures from this newsreel. The map does not strive for realism in either the spatial or temporal dimensions, rather it succeeds at communicating the concept of invasion and thus provoking strong emotions in the audience. The specifics of the invasion are not as important as the fact that an act of war took place. Today, such emotive graphics are still popular with the news media—animations that are thin on details but thick with meaning.

![Figure2](cartography2/images/HistoryMapAnimation/Figure2.jpg)  
***Figure 2: **** Screen captures of a 1940 newsreel produced by Disney depicting the Nazi invasion of Warsaw.*  


Thrower (1959) encouraged cartographers to make use of animated techniques to popularize their work. “For illustrating the dynamic nature of certain areal relationships this technique [animation] is unexcelled…Animated maps are not a substitute for conventional, static cartography, but for certain purposes they have possibilities which have not yet been adequately explored by cartographers” (Thrower 1961, p. 28). This statement has lost little relevance in the 40 years since it was written. Thrower is suggesting that time-series data can be effectively communicated with animation—a sentiment that forms the basis for much of the work in map animation and geovisualization. A second theme in Thrower’s writing is the role of animation as an educational device to which the public has become accustomed (re: Walt Disney). In short, geographers should exploit the popularity of animation to reach a wider audience. Animated maps remained marginalized until the mid-1980s because few cartographers had either the skill or resources to create such maps manually.

Era #2: Computer-Assisted Production

The first computer-generated animation was produced in 1963 by Edward Zajac working at Bell Laboratories in New Jersey (Figure 3). Zajac’s wireframe animation shows the orbital path and position of a satellite around a planet and represented an enormous achievement at the time. Cornwall and Robinson (1966) published the first article addressing the potential of computer-assisted animation. Although a computer was used to create and display the animation created by Cornwall and Robinson (1966), the images were transferred to conventional film by placing a 16mm film camera directly in front of the computer screen. This clumsy transfer process underscores the problems faced by these early pioneers both in the storage and the distribution of computer animations.

![zajac](cartography2/images/HistoryMapAnimation/zajac.jpg)  
***Figure 3: ****Output from the first computer-generated animation, circa 1963, depicts the orbital path of a satellite.*

  
In order to represent simulated urban growth in the Detroit region, Waldo Tobler (1970) used a computer to create individual frames in an animated sequence that was shot to film (Figure 4). Tobler’s work is remarkable for two reasons: It was the first computer-assisted animated map to be discussed in an academic publication and his motivation for creating it was to “…provide insights, mostly of an intuitive rather than formal nature, into the dynamics of urban growth” (Tobler 1970, p. 239). In other words, Tobler used animation to generate new insights into a complex process, rather than to communicate known facts about that process. As he very succinctly states, “Because a process appears complicated is no reason to assume that it is the result of complicated rules” (p. 234). Thirty years later, his hopes for the role of animation in the process of knowledge construction are finally coming to fruition and have been adopted as one of the central motivations of geographic visualization.

![Tobler](cartography2/images/HistoryMapAnimation/Tobler.jpg)  
***Figure 4: ****Screen captures from Tobler’s 2.5D mesh population surface animation, produced in 1970, show historic growth patterns in Detroit. A second animation revealed anticipated growth over the next 4 decades as part of an early computer-based urban simulation model. This map (and the research behind it) was years ahead of its time.*

Moellering’s subsequent map animation work (1976) represents a rethinking of how to use map time to represent real-world time, and in the process, demonstrates the power of map animation to facilitate understanding of cyclic space-time phenomena. Moellering generated two animations based on three years of traffic-accident data for Detroit. In the first animation, three years of data are depicted in a few minutes and the accident patterns appear to be random. In the second, three years of data are used to create a single weekly composite that is divided into 15-minute averages. For example, all accidents over the three years that occurred at a given intersection on a Wednesday between 4:30pm and 4:45pm are collapsed into one frame. This creates an animated map that depicts long-term prevalence of accidents at various locations at certain points in the day, and on certain days of the week. What emerged from this temporal composite was a clear pattern of peak accident rates during rush hour, and the dramatic changes in where and when accidents occur from weekday to weekend. Moellering’s work is an excellent example of the use of map animation to better understand geographic processes, and not merely plot geographic patterns.

Another example of Moellering’s work with animated maps (1980) is a depiction of the growth of the population of the United States from 1850 to 1970 in which the viewer’s perspective periodically rotates through 360 degrees. Although these changes in perspective have been criticized as cognitively disruptive (Campbell and Egbert 1990), there is little more than anecdotal evidence to suggest whether they impair or help map reading. Moellering’s population map is an early example of an animation that incorporates two kinds of display time: the changes on the map correspond to real-world time (e.g., years) while the changes in viewing perspective do not and are simply used to help the viewer see the map from all sides. 

Moellering’s population map is noteworthy because it demonstrates how animation can be applied to solve a long-standing problem with static three-dimensional map displays, namely, the visual obstruction of portions of the map surface. The predetermined rotation of the map also serves to remind the viewer that there are multiple possible perspectives of a single dataset (Monmonier 1991). Subsequent visualization systems (e.g., Fuhrmann and MacEachren 2001) have successively extended the idea of a changeable viewpoint into user-driven virtual map-navigation systems in which the user is free to “fly around” a 2.5D or 3D map rendering. Such real-time navigational capabilities are designed to facilitate exploration of large or complex datasets, in both spatial and statistical spaces (Gahegan 1996).

Era #3: Computer-Based Production

The arrival of the affordable desktop computer in the early 1980s meant three things to cartographers in relation to map animation: a new tool for the creation of animated maps, a new method for storing and sharing animated maps, and a new device with which the public could view animated maps. The maturation of computer hardware and software capable of producing and displaying animated maps has taken 40 years, and is still ongoing. It would therefore be an oversimplification to divide the history of animated maps into pre- and post-computer eras.

Before the desktop-PC revolution, the costs of digital animation were astronomical. In the mid-1970s commercial digital animation typically required a Cray supercomputer which cost $3–$5 million. Compounding this expense was the need to hire a team of computer programmers capable of writing the in-house animation software and (often) a separate team of digital artists who could create the images. As a rule of thumb, six months of production were required to produce one 30-second movie.

The prospects of digital animation improved significantly with the arrival of Alias Wavefront in 1984. At the then-bargain cost of $100,000, Wavefront was the first off-the-shelf animation software capable of producing high-quality, three-dimensional computer animations. By the mid-1980s, computer generated animations had migrated from million-dollar machines to specialized workstations costing tens of thousands of dollars. Although by today’s standards these early computer workstations were crude, they represented a new era of affordable commercial animation. A milestone in digital animation was achieved by Lucasfilm in 1983 with their release of the short film *Road to Point Reyes* (Figure 5) which depicted a virtual “road trip” complete with fog banks and atmospheric light scattering. Not long after this, digital animation began to appear in Hollywood films to create special effects such as the liquid morphing sequences in *The Abyss* (1989, 20th Century Fox). Along with the gaming industry and the military, Hollywood remains a principal driving force behind technological developments in computer animation today.

![pt-reyes.JPG](cartography2/images/HistoryMapAnimation/pt-reyes.JPG.jpg)***  
Figure 5: ****The ground-breaking, all-digital animation Road to Point Reyes produced by Lucasfilm in 1983. While there were a number of important breakthroughs in the 1980s in computer-based animation (and seen by its appearance in major motion pictures), distribution of animated maps was still a problem in that users had to "go to the content" it didn't "come to them" (on-demand).*  


In the early-to-mid 1990s, SGI and Sun workstations had come to dominate computer animation. With dedicated video-rendering hardware and a host of high-performance capabilities, including dual-processors and RAID storage, these computers provided real-time video editing and animation rendering for digital artists at a cost of $20,000–$40,000. By the late 1990s, average desktop computers costing less than $3,000 became sufficiently fast for the needs of digital animation and largely replaced more expensive workstations. The current availability of affordable animation software such as Director, Flash and Bryce, coupled with cheap desktop machines means the ability to produce professional-quality animated maps is now within the financial means of most cartographers. Similar advances in digital remote sensing and GIS software have made it possible for users with only a modest budget to create visually impressive 3D terrain fly-by maps or 3D map animations. The problem of distributing and using animated maps will be discussed next.

Methods of Storage, Distribution, and Use  


  
Regardless of how an animated map is made, it will not be very successful if no one can view it. From a commercial perspective, getting the product into the hands of the consumer is a paramount concern. The relative obscurity of Tobler’s and Moellering’s pioneering work is due simply to problems of storage, distribution, and use.

The distribution of animated maps can be divided into four technological phases: celluloid film (1950s – 1970s), magnetic videotape (1970s – 1980s), computer diskette and CD-ROM (1980s – present), and online distribution (mid 1990s – present).

**Celluloid Film Era**  
The first animated maps were stored on 35mm celluloid film stock which made them both prohibitively expensive to own and awkward to distribute. Celluloid-based maps also meant that individuals had to “go to the map,” rather than have it “come to them.” In the 1930s and 40s, movie theaters were the only place to watch animated maps. The widespread adoption of television in the 1950s and 60s meant people had an opportunity to watch animated maps at home. However, distributing animated maps via television required access to television networks (which were, understandably, more interested in entertainment than academic cartography). Television was thus a satisfactory viewing device, but not a satisfactory distribution mechanism for animated maps. Television broadcasting of animated maps also forced viewers to watch the map as it was broadcast and in the 1950s and 60s there was no practical way for the viewer to store or re-watch the map.

**Magnetic Videotape Era**  
The “VCR boom” of the late 1970s and early 1980s and the arrival of the inexpensive and portable magnetic videocassette provided cartographers with the first viable public distribution and viewing mechanism for animated maps. By the early 1980s, videocassettes were inexpensive, VCRs were commonplace, and most importantly, the viewer could watch the map at their leisure and as many times as they liked. This also marked the introduction of rudimentary map interaction: the viewer could pause, rewind, and advance frame-by-frame through an animated sequence. During the 1970s and early 1980s a few animated maps were created by cartographers and shot to film one frame at a time, transferred to videocassette, and sent out to consumers. By the late 1980s, it was possible to directly transfer animated maps from computers to videotape, which streamlined this process. Unfortunately, VCR-based animated maps proved prohibitively expensive as a means of distribution for most academic cartographers and university cartography shops and only a few examples were ever created.

**Computer Storage Era**  
The arrival of the personal computer in the early 1980s changed production cartography forever. But computers were not only useful in creating animated maps, they could be used to store and view these maps. A variety of magnetic and optical storage media have been developed in the last 20 years, most notably the floppy disk and CD-ROM, which allow animated maps to be distributed with relative ease and minimal cost. The digital size of animated maps has always been a concern and the 1.2MB storage capacity of floppy disks is usually insufficient for raster-based animated maps. By 1995, the cost of a CD burner had dropped below $500 and cartographers finally had a storage medium that was large enough (650 MB) and stable enough (unlike magnetic media) for long-term storage and dissemination of animated maps.

In the 1990s there were three major obstacles that had to be overcome for the home use of digital animation on desktop computers: (1) standard file formats for digital video, (2) software that could read and playback digital video, and (3) hardware capable of decoding video at sufficient frame rates for animation.

On-Demand Mapping

Given that computers were prohibitively expensive in the early 1960s, J. C. R. Licklider proposed building a nationwide “Intergalatic Computer Network” where individuals would access computers via inexpensive terminals. The origins of the Internet can be traced to the development of Project MAC at MIT which was begun in 1962. Under the guidance of Licklider, by the mid-60s Project MAC had evolved into the world’s first online community, complete with bulletin boards, e-mail, “virtual” friendships, a “freeware” exchange—and even hackers (Waldrop 2001). This led to the development of Arpanet, which became the first operational nationwide digital network. Arpanet was designed to facilitate the sharing of information and resources among high-level research facilities. The switch to the robust (and still essential) TCP/IP communications protocol in 1983 is often cited as the moment of birth for the Internet. In 1990, Tim Bernes-Lee created the World Wide Web. The launching of Mosaic in 1993 (the first hypertext browser and predecessor of Netscape) made the Web user-friendly, and in the process, transformed the Internet from a tool largely restricted to university researchers and government scientists into a ubiquitous public phenomenon.

The importance of the Web for cartographers is four-fold. First, the Web provides cartographers with a new mechanism for map distribution. Second, the Web allows the public to find maps they might otherwise not be able to locate. Third, the Web has stimulated the public’s demand for maps. And fourth, the Web allows cartographers to make entirely new kinds of on-demand maps, for example, that compile information from multiple distributed sources simultaneously and that can be updated dynamically as data arrive. The development of on-demand mapping in the last eight years provides us with an example of how the medium of the Web has allowed cartographers to “think outside the box” and create new ways to share geospatial information (MacEachren 1998).

**On-demand mapping** differs from merely using the Internet to distribute digital maps because   


1.  the map does not pre-exist, that is, it is created “on-the-fly,” 
2.  the user can often interact with the map and change display parameters, and 
3.  the map can become a dynamic interface to services such as airline reservations. 

  
Although created for use by the public rather than scientific experts, on-demand mapping shares many of the characteristics of geovisualization systems in that they are both digital, ephemeral, and usually created for an audience of one. Crampton (1999) coined the phrase “distributed private mapping” to distinguish online geovisualization systems that are used to create new knowledge from “on-demand mapping systems” used to communicate known facts (e.g., MapQuest).
To date, the key ingredients in the success of existing on-demand mapping systems appears to be that they are free, easy to use (especially in comparison to a full GIS), require no special or commercial software, and are capable of responding almost instantly to user input. In other words, the “costs” incurred to the users—in both direct costs and latent costs of training and delivery time—are minimal. 

The animated maps produced by the [Weather Channel][8] and available to the public through their website, are good examples of the kinds of animated maps for which there is public interest. These maps also demonstrate how animated maps originally created for one medium (television) can be enhanced with new functionality when ported to another (the Web). Since these animations are time-sensitive (i.e., show the latest weather conditions), automated routines have been developed to serve constantly updated animated maps as information arrives. hese maps (see Figure 7) provide basic user control including stop, start, non-linear navigation, pace, and size (small and large). They also represent a first step away from manual production to automated production which, as will be argued more fully later, seems essential if animated maps are to truly move into the mainstream.

One More Hurdle: Bandwidth

By the late 1990s all of the major pieces needed for animated maps were in place:

1.  The Internet was a great mass-distribution mechanism (and way for users to find your maps in the first place),
2.  Commercial software now existed, costing only a few hundred dollars, allowing cartographers to make animated maps, 
3.  Affordable desktop computers were fast enough to both create and playback high quality animated maps, and 
4.  Standard formats for viewing maps had been established (e.g., MPEG, QuickTime, Flash). 

  
One of the last hurdles for animated maps is [bandwidth][9], or the amount of data that can be transferred over wired and wireless networks. This is important because all things being equal, animated maps tend to be very large files and in the early days of the Web could take hours to download before they can be seen or used (and most folks just won't wait that long). 
![north](cartography2/images/HistoryMapAnimation/north.jpg)  
***Figure 6:**** Postage-stamp sized content, typical of the early days of the Web*  


  
In the 1990s files sizes with digital animated maps were often prohibitively large for consumers and as a not-perfect work-around animated maps were often created to be very small files, aka "postage stamp" cartography. Note also the animated-GIF file format prevent any sort of interaction with the map (such as stopping or changing the pace), which testing has shown often frustrates users. Comparing this map with the ones that follow show just how much our Web technology has improved in 10 years.

While universities and scietific centers have enjoyed sufficient bandwidth for these kinds of files for almost two decades now, consumers have only more recently had access to the bandwidth speed needed for realtime animated maps with the widespread use of cable modems, DSL, and new Wi-fi standards. One clever solution was the development of "streaming" media in the late 1990s (Real Media and Quicktime 4%2B) which is still very much in use today: It doesn't make the files any smaller but they start playing sooner and users thus don't have to wait very long to access the content. For example, the newest generation of online movie rentals, despite truly massive files, are watchable after only a few minutes of download time because of "[streaming][11]".  


  
[![Trulia][13]](cartography2/images/HistoryMapAnimation/Trulia][13].jpg)  
***Figure 7: ****Animated mash-ups, like this one **[showing where homes have been built over the past 100 years][13]**, are one of the very latest developments in animated map technology. Created by the talented folks at **[Stamen Design][14]**, this kind of animated map mash-up is the very cutting edge of work today.  
*  
****

[![Koblin][16]](cartography2/images/HistoryMapAnimation/Koblin][16].jpg)****

***Figure 8: ****Aaron Koblin's **[beautiful maps of air traffic patterns][16]** show how people are are inventing creative new ways to visualize data. **[Watch the movie here][17]**: Look for the wave of flights from Europe and the way the eastern seaboard "lights-up" in the morning with the first wave of commuter flights. This is a very large and complex dataset that does in fact exhibit coherent behaviors. "Seeing" your data clearly is the raison d'etre for good design.  
*

* * *

  
References
Blok, C., B. Kobben, T. Cheng, and A. A. Kuterema 1999. “Visualization of relationships between spatial patterns in time by cartographic animation.” Cartography and Geographic Information Systems 26(2): 139-151.

Campbell, C. S. and S. L. Egbert 1990. “Animated cartography: Thirty years of scratching the surface.” Cartographica 27(2): 24-46.

Cornwall, B. and A. Robinson 1966. “Possibilities for computer animated films in cartography.” Cartographic Journal 3(2): 79-82.

Crampton, J. 1999. “Online Mapping: Theoretical Context and Practical Applications.” In W. Cartwright, M. Peterson, and G. Gartner (Eds.) Multimedia Cartography, Springer Verlag.

DiBiase, D., A. M. MacEachren, J. B. Krygier, and C. Reeves 1992. “Animation and the role of map design in scientific visualization.” Cartography and Geographic Information Science 27(4): 201-214.

Dorling, D. and S. Openshaw 1992. “Using computer animation to visualize space-time patterns.” Environment and Planning B: Planning and Design 19: 639-650.

Ehlschlaeger, C. R., A. M. Shortridge, and M. F. Goodchild 1997. “Visualizing spatial data uncertainty using animation.” Computers and Geosciences 23(4): 387-395.

Fuhrmann, S. and A. M. MacEachren 2001. “Navigation in Desktop Geovirtual Environments: Usability Assessment.” Proccedings of the 20th International Cartographic Conference, Beijing, China, August 6-10, 2001.

Gahegan, M. N. 1996. “Visualisation strategies for exploratory spatial analysis.” Paper presented at Third International Conference on GIS and Environmental Modelling, January 21 to January 25, 1996, Santa Fe, New Mexico.

Gersmehl, P. J. 1990. “Choosing tools: Nine metaphors for four-dimensional cartography.” Cartographic Perspectives, Spring: 3-17.

Harrower, M. 2002. “Visualizing change: Using cartographic animation to explore remotely-sensed data.” Cartographic Perspectives (39): 30-42.

Harrower, M., A. M. MacEachren, and A. Griffin 2000. “Developing a geographic visualization tool to support earth science learning.” Cartography and Geographic Information Science 27(4): 279-293.

McLuhan, M. 1967. The Medium is the Message. New York: Bantam.

MacEachren, A. M., F. P. Boscoe, D. Haug, L. W. Pickle 1998. “Geographic Visualization: Designing manipulable maps for exploring temporally varying georeferenced statistics.” Proceedings of the IEEE Information Visualization Symposium, Research Triangle Park, NC, Oct. 19-20, p. 87-94.

MacEachren, A. M. 1998. “Cartography, GIS and the World Wide Web.” Progress in Human Geography: 575-585. 

Mennis, J. L. and D. J. Peuquet 2000. “A conceptual framework for incorporating cognitive principles into geographic database representation.” International Journal of Geographic Information Science 14(6): 501-520.

Moellering, H. (1976). The potential uses of a computer animated film in the analysis of geographical patterns of traffic crashes. Accident Analysis &amp; Prevention 8: 215-227.  
Moellering, H. 1980. “The real-time animation of three-dimensional maps.” The American Cartographer, 7(1): 67-75.

Monmonier, M. 1991. “Ethics and Map Design: Six strategies for confronting the traditional one-map solution.” Cartographic Perspectives 10 (summer): 3-8.

Monmonier, M. 1992. “Authoring Graphics Scripts: Experiences and Principles.” Cartography and Geographic Information Systems 19(4): 247-260.

Openshaw, S., D. Waugh, and A. Cross 1994. “Some ideas about the use of map animation as a spatial analysis tool.” In Hilary M. Hearnshaw and David J. Unwin (Eds.) Visualization in Geographic Information Systems, Wiley: New York. p. 131-138.

Peterson, M. P. 1995. Interactive and Animated Cartography. Englewood Cliffs, NJ: Prentice Hall. 257 pp.

Slocum, T. A., C. Blok, B. Jiang, A. Koussoulakou, D. R. Montello, S. Fuhrmann, and N. R. Hedley 2001. “Cognitive and Usability Issues in Visualization.” Cartography and Geographic Information Science, 28(1): p.61-75.

Thrower, N. J. W. 1959. “Animated cartography.” The Professional Geographer 11(6): 9-12.

Thrower, N. J. W. 1961. “Animated cartography in the United States.” International Yearbook of Cartography 1: 20-30.

Tobler, W. R. 1970. “A computer movie simulating urban growth in the Detroit region.” Economic Geography 46: 234-240.

Waldrop, M. M. 2001. “Origins of personal computing.” Scientific American 285 (6): 84-91.

* * *

Except where otherwise noted, content on this site available under a [Creative Commons 3.0 License][18]

 [1]: http://web.archive.org/web/20110711100046/http%3A/en.wikipedia.org/wiki/Waldo_R._Tobler
 [2]: http://web.archive.org/web/20110711100046/http%3A/www.elsevier.com/wps/find/bookdescription.cws_home/703524/description#description
 []: http://web.archive.org/web/20110711100046/http%3A/cartography2.com/my_images/TimeLine.jpg
 [4]: http://web.archive.org/web/20110711100046im_/http%3A/cartography2.org/Chapters/page12/files/figure2.jpg
 [5]: http://web.archive.org/web/20110711100046im_/http%3A/cartography2.org/Chapters/page12/files/zajac.jpg
 [6]: http://web.archive.org/web/20110711100046im_/http%3A/cartography2.org/Chapters/page12/files/tobler.jpg
 [7]: http://web.archive.org/web/20110711100046im_/http%3A/cartography2.org/Chapters/page12/files/pt-reyes.jpg.jpg
 [8]: http://web.archive.org/web/20110711100046/http%3A/www.weather.com/
 [9]: /web/20110711100046/http://en.wikipedia.org/wiki/Bandwidth_(computing)
 [10]: http://web.archive.org/web/20110711100046im_/http%3A/cartography2.org/Chapters/page12/files/north.jpg
 [11]: http://web.archive.org/web/20110711100046/http%3A/en.wikipedia.org/wiki/Streaming_media
 []: http://web.archive.org/web/20110711100046/http%3A/hindsight.trulia.com/map/#lat%3D36.022%26amp%3Blon%3D-86.584%26amp%3Bzoom%3D11%26amp%3Bmix%3D0.500
 [13]: http://web.archive.org/web/20110711100046/http%3A/hindsight.trulia.com/map/#lat%3D36.022%26amp%3Blon%3D-86.584%26amp%3Bzoom%3D11%26amp%3Bmix%3D0.500
 [14]: http://web.archive.org/web/20110711100046/http%3A/stamen.com/clients/trulia
 []: http://web.archive.org/web/20110711100046/http%3A/www.aaronkoblin.com/work/flightpatterns/
 [16]: http://web.archive.org/web/20110711100046/http%3A/www.aaronkoblin.com/work/flightpatterns/
 [17]: http://web.archive.org/web/20110711100046/http%3A/www.aaronkoblin.com/work/flightpatterns/FPWeb_Final_3.mov
 [18]: http://web.archive.org/web/20110711100046/http%3A/creativecommons.org/licenses/by-nc-sa/3.0/us/  