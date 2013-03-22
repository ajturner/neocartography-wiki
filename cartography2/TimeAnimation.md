
[Permalink](http://web.archive.org/web/20110711100607/http://cartography2.org/Chapters/page11/TimeAnimation.html "Permalink to Cartography 2.0 - Representing Time on Animated Maps")

# Cartography 2.0 - Representing Time on Animated Maps

by Mark Harrower
date: 09/12/09


One of the primary reasons we make animated maps is to show how things change over time. Animated maps are appealing becuase we live in an animated world. The world isn't "frozen" like a static map, it is a very dynamic place and when we map things like unemployment or climate change we're really mapping complex processes that occur in both space and time. It makes sense, then, that we would want to use map animation to capture and communicate the nature of these dynamic processes by explicitly incorporating time into our maps. For example, the movement of a object such as a boat can be show on a static map with a dashed line, which *infers* movment, or it can be shown *directly *on an animated map by having the boat move.
Static maps present all of their information simultaneously; animated maps present information over time. Thus, animated maps have an additional representational dimension that can be used to display information. While it obviously takes time for a reader to scan a paper map, such as retrieving specific rates, the overall or holistic impression of the static map happens at a glance. Moreover, the reader does not have to wait for the information to appear as they do with an animation. Increasing the running time of an animation increases the total amount of data that can be represented, but at a cost to the user. As the length of the animation increases so too does the difficulty of remembering each frame of the animation. Put another way, although the amount of data that can be represented within an animation is virtually unlimited, there is a finite amount of information the user can distill from the animation and store in their short-term visual memory. Overwhelming the map reader with information does more harm than good. As a result, most animated maps are short and few run longer than a minute.

Temporal Scale and Pace  


  
Just as static maps have a spatial scale (e.g., 1 inch = 1 mile), temporal animated maps have a temporal scale. This is the ratio between real-world time and movie time. For example, 5 years of data shown in a 10 second animation would have a temporal scale of 1:157 million. Although it is possible to vary the temporal scale of the map as it plays—to focus on important moments by slowing the map down, or blur-out others by speeding it up—most animated maps keep a constant temporal scale. 

Another important aspect an animated map is its temporal granularity / resolution (the finest temporal unit resolvable) and the pace (the amount of change per unit time). Pace should not to be confused with frames-per-second (fps): An animation can have a high frame rate (30 fps) and display little or no change (slow pace). Perceptually, true animation occurs when the individual frames of the map/movie no longer are discernable as discrete images. This occurs above roughly 24 fps—standard frame rate of celluloid film—although frames rates as low as 5 fps can generate a passable animation effect. Higher frame rates yield smoother looking animations, although modest computers may have trouble playing movies at high frame rates, especially if the map is a large raster file.

Designing Temporal Legends

![3legends][1]

Above are the three most common kinds of temporal legend – digital clock, cyclical, and bar. **A good temporal legend has to communicate three things**: 

1.  what is the *current moment* (e.g., June 10), 
2.  what is the *total length* of time in the animation (e.g., June 1-22), and 
3.  *where is this moment* in relation to the animation as a whole (e.g., about half way through). 

  
Both the cyclic and bar legend can communicate at a glance all of these facts and are generally good choices. The digital clock can only represent the first of these (what time is it) and is, in my opinion, not the best choice for most animations, although it partners well with the other two. Linear temporal legends emphasize a progression of events over time, while a cyclic temporal legend is a great choice when you have a strong cyclic/repeating nature to your data (e.g., a diurnal or seasonal emphasis). Because it is often assumed these kinds of legends supports different map reading tasks, designers often include more than one on a single map. 
Temporal legends should generally be included in any animated map of temporal data and if in doubt, add one. 

TIP #1: All other things being equal, I would recommend making a temporal legend interactive so that the reader can directly manipulate the playback direction and pace of the movie, sometimes called "scrubbing the timeline", or jump to a new moment in the animation, sometimes known as "non-linear navigation." These have become a common interface actions in digital music and video players and many map readers now expect to be able to directly interact with temporal legends to control the map. 

TIP #2: Temporal legends don't have to be too large on the screen; as drawn above they are 2-3x bigger than I'd use on a real map.

Reducing the Split Attention Effect  


  
One unresolved problem with legend design is *split attention*: Because animated maps, by their very nature change constantly, the moment the reader must focus on the temporal legend they are no longer focusing on the map and may miss important cues or information. If they pause the animation to look at the legend, they lose the animation effect. The more the reader must shift their attention between the map and the legend, the greater the potential for disorientation or misunderstanding.

The split attention effect is defined as “any impairment in learning that occurs when a leaner must mentally integrate disparate sources of information” (Mayer 2001, 92). This integration can happen across material separated by space (spatial contiguity effect) or across time (temporal contiguity effect). Split attention is a common problem with both static and animated graphics and can arise whenever a reader must look at two or more things at once in order to understand either, such as map and a map legend. If either element makes sense by itself, then split attention is not a problem—it only becomes a challenge when understanding requires processing both simultaneously. 

Experiments have shown that where multimedia elements are placed on the screen, and when they appear, will affect their pedagogic impac. Summarizing work in this area, Mayer states that multimedia is most effective when related material, such as images and text explanations, appear close to each other and relate to one another in meaningful ways. Testing has shown that when related material is placed far apart it requires additional cognitive resources to visually search for and integrate, reducing the amount of working memory available for learning (Chandler and Sweller 1991; Kalyuga and others 1999; Mayer and Moreno 2002). Split attention is thus seen as low-level busywork that distracts from the real business of learning. 

Proposed but untested solutions to the problem of split attention include (1) embedded audio cues that announce time (offloading some of the work to our ears) and (2) embedded visual cues that are superimposed onto the map itself allowing us (in theory) to keep our eyes on the map. Examples of an audio temporal legend would be the use of an announcer speaking ("Tuesday"), although the work that I have done with sonification of animated maps runs it to a basic problem: The map runs much faster than the announcer can talk (or the reader can hear), as indeed, our maps can run at 30 frames per second but few people can speakor comprehend 30 words per second (we tried using digital audio tools to speed-up the speaker and it became both unintelligible and hilarious).

![Day_Night_Shadow][2]

EMBEDDED VISUAL CUES: [Matt Bloch's flight map][3] is an example (from the [Overview Section][4]) how we can use obvious visual cues within our animated maps to** convey the passing of time**, in this case, the transition from day to night (shown as a shadow that sweeps from east to west across the map). Google Earth also allows users to add a day/night shadow to their maps. Although I've not seen any examples myself, it would be possible to use similar **seasonal cues for the passage of years** as the map or color scheme transitioned from winter colors and the formation of ice in the corners of the map, through spring, summer and fall. Of course, such artistic flourishes are somewhat cultural and only have meaning in places with pronounced seasons, but I suspect these might make for attractive—if somewhat informal—presentations.

![Midtbo][5]

AUDIO CUES: [Midtbø (2001)][6] suggests at least a dozen ways to minimize split attention in animated maps and has proposed a number of highly innovative map designs including maps that indicate the current time by their position on the screen or by wrapping the map inside of the temporal legend (see example above), and the use of sound in various ways to off-load some of the work from our eyes to our ears. One such example uses a four-channel system to create immersive audio cues to “move sound around the user” simulating a clock or yearly cycle. It is unclear how effective such techniques would be, but the idea of offloading some of the work from our eyes to our ears is both practical and supported by research in multimedia instructional design.

Temporal Re-Expression  


  
Although the most obvious way to animate spatio-temporal data is to simply play the data in the same sequence as it was collected (e.g., day 1 = frame 1, day 2 = frame 2, and so on) this is not always very insightful because (1) the data may be very complex and contain multiple meaningful patterns, (2) and/or because the data may be very noisy. To really explore a dataset you need more powerful tools than simply playing back raw, disaggregate data back in the order it was collected. One of these tools kits is called temporal re-expression.

Temporal re-expression is one of the most powerful cartographic transformations we can apply to better understand spatio-temporal data. The term was coined by [David DiBiase][7] in the early 1990s, although early examples appeared in the 1970s, including [Moellering's][8] famous Detroit Traffic Accident animated map. Temporal re-expression is displaying the same dataset using different temporal units in which the data are aggregated to create composite frames (or moments) in the animation. 

[![550alcohol][10]][10]

The map above presents [365 days of drinking related incidents for the University of Wisconsin-Madison][10] campus (data were recorded hourly). With this, for example, we can add together the 365 individual days into a single 'composite day' to show how these incidents might differ according to time of day. This allows us to answer questions such as “do more incidents occur at 8am than 8pm?” (yes!). Because the data are mapped, the spatial patterns of accidents and where those accidents occur, and by what cause factor, can be investigated allowing the reader, for example, to ask “even if the number of incidents are the same, does where they occur differ between 8am and 8pm?” (yes, again). The map also depicts the incident data as a composite week (e.g., “Do more incidents occur on Mondays than Fridays?”), and composite month (e.g., December versus May). This kind of control over the data allows many important space time patterns to emerge from the data that were otherwise hard to see or simply obscured. 

A great example of this relates to the football stadium (in the lower right): On most of these maps (and the with the raw data) it looks like there is constant and somewhat random activity near the football stadium. However, when the data are shown as a composite week a very clear pattern emerges: all of these incidents occurred on Saturdays, which is when games are played. That obvious and commonsense pattern gets 'buried' in the data if the data are presented in other ways. This underscores why there is no obvious single best way to present geographic data and giving users this kind of control over the map is both useful and ethical.

Temporal Granularity and Interpolation  
  


Aggregating our data together can be used to change how much time each frame of the animation represents, also known as temporal granularity. Doing this allows viewers to create temporal slices of different thickness so that the smallest/finest moment that can be seen in the animation could be changed from hours to days or months. The example of BallotBank shows financial campaign contributions in the United States. Initially these political donations are displayed monthly (the finest temporal unit available), although the viewer can aggregate and average the data on-the-fly over long intervals: In the image below, the temporal granularity of the map has been increased from 6 months to 12 months (each frame now shows a 12 month period). Because campaign contributions are closely tied with tax season, as well as election cycles (both 2 and 4 year) this flexibility can help to uncover subtle behaviors in political participation that the most temporally disaggregate data obscures. BallotBank.com also incorporates temporal focusing which lets the map reader set the start and end dates of the animation.

![550BallotBank][11]

Many animated maps employ temporal interpolation to “fill-in” missing time periods or to create a smoother looking animation. It is not uncommon to see maps in which the interpolated data outnumbers the “real” data 10 to 1. While interpolation is a robust science, when we map complex geographic processes it is hard to get it right and without ground truthing (usually an impossibility since without first developing a time machine) it can be very difficult to know if our estimates values reflect the reality on the ground. 

From a visual perspective, many authors over the years have encouraged the use of temporal interpolation to create smoother animations, that it is assumed, will be more attractive and more legible. However popular temporal interpolation is, the cognitive effectiveness of temporal interpolation has only been partially studied (one of my graduate students did her thesis on this topic) and results suggest subjects prefer maps with interpolation, although do not perform any better on map reading tasks. Various [linear and non-linear algorithms and techniques][12] have been developed for creating quality interpolated temporal data, some of which are quite sophisticated mathematically. 

Final Thoughts

I worry that excessive temporal interpolation can create false and highly misleading patterns, such as an abrupt change in the location of a feature incorrectly shown as a gradual spatial transition from point A to point B. This is especially likely to happen if we don't possess a deep understanding of how processes unfold and the kinds of spatial and temporal patterns we should expect to see. Of course, this is something of a catch-22: If we nudge our algorithms to conform with what we expect to see, how do we learn new insights? Do our maps simply become an echo-chamber showing us what we think we already know about the world? How do we know if we have found something new or unusual, versus, simply mapping bad data or mapping good data badly? There are no easy answers to those questions, but I remind myself to fight the urge to map data I barely understand using tools that I can't explain (most software is a black box to me, and I suspect, most people). Good science demands better of us. It also generally requires a team, which is why most of my work has been a collaboration with experts who collect the data and experts who know how to analyze it.

* * *

Except where otherwise noted, content on this site available under a [Creative Commons 3.0 License][13].

 [1]: http://web.archive.org/web/20110711100607im_/http%3A/cartography2.org/Chapters/page11/files/3legends.jpg
 [2]: http://web.archive.org/web/20110711100607im_/http%3A/cartography2.org/Chapters/page11/files/day_night_shadow.jpg
 [3]: http://web.archive.org/web/20110711100607/http%3A/maps.grammata.com/evening_flights.html
 [4]: http://web.archive.org/web/20110711100607/http%3A/cartography2.org/Chapters/page6/OverviewAnimated.html "Overview of Animated Maps"
 [5]: http://web.archive.org/web/20110711100607im_/http%3A/cartography2.org/Chapters/page11/files/midtbo.jpg
 [6]: http://web.archive.org/web/20110711100607/http%3A/statisk.umb.no/conf/scangis2001/papers/33.pdf
 [7]: http://web.archive.org/web/20110711100607/https%3A/www.e-education.psu.edu/about/people/dibiase
 [8]: http://web.archive.org/web/20110711100607/http%3A/www.geography.ohio-state.edu/faculty/moellering/
 []: http://web.archive.org/web/20110711100607/http%3A/www.geography.wisc.edu/%7Eharrower/Geog575/finalProjects03/drinking.swf
 [10]: http://web.archive.org/web/20110711100607/http%3A/www.geography.wisc.edu/%7Eharrower/Geog575/finalProjects03/drinking.swf
 [11]: http://web.archive.org/web/20110711100607im_/http%3A/cartography2.org/Chapters/page11/files/550ballotbank.jpg
 [12]: http://web.archive.org/web/20110711100607/http%3A/www1.elsevier.com/homepage/sad/cageo/cgvis/acevedo/acevedo.htm
 [13]: http://web.archive.org/web/20110711100607/http%3A/creativecommons.org/licenses/by-nc-sa/3.0/us/  