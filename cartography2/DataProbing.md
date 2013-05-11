
[Permalink](http://web.archive.org/web/20100609152251/http://cartography2.org/Chapters/page8/DataProbing.html "Permalink to Cartography 2.0 - Data Probing and Info Window Design")

# Cartography 2.0 - Data Probing and Info Window Design

Ben Sheesley, Axis Maps LLC
date: 09/01/09

Info windows are the familiar pop-up balloons that often appear when selecting features on a map. This activity is generally called data probing, or more specifically brushing without linking. For example, click on a&nbsp;[Google Maps marker][1]&nbsp;and up comes a little bubble with information about the place. The uses for data probing are seemingly limitless, ranging from the retrieval of map-based comments, annotations, and descriptions of ‘what’s here?’, to map stats and info graphics, to map use instructions (e.g., “get directions”), explanations (e.g., “group of 3 markers”), and controls (e.g., “zoom here”), to alternate map views (e.g., an historical map). All of this, of course, can come through in the form of text, photos, audio, and video.*Data probing is essential.*&nbsp;In one sense, it's needed because we’ve got tons of data about the world, but just small, low-resolution computer screens to view it all on. Like a drop-down list or an accordion menu on a Web page, data probing is a design compromise that can save space on maps. In another sense, however, data probing is an important design decision that can help direct map readers’ attention and understanding from the general to the specific by offering details on demand. Without data probing, we’d either have crazy-cluttered maps or watered-down maps not taking advantage of all of that rich data out there.
Of course, data probing is everywhere outside of mapping as well; on charts, graphs and all sorts of other info graphics. But here I focus on Web maps, specifically on info window design, and outline some major&nbsp;

*design considerations*&nbsp;and provide a *few&nbsp;examples*&nbsp;that could help inspire your next effort.Design Considerations  
  
1) Size  
Large footprint info windows hold lots of data but end up obscuring much of the map itself. Often, it’s the&nbsp;*geographical context*&nbsp;and the&nbsp;*distribution of data*&nbsp;around a probed location that’s helpful for a more complete understanding of a place. When an info window obscures the map, the missing section must be held temporarily in a user’s working memory until the window is closed. For this reason, it’s usually worth minimizing this kind of cognitive load and coming up with ways to make info windows more compact.*Compactness*&nbsp;depends a lot on the volume of data that will wind up in the info window. Tiny, “tool tip”-sized window are great for small amounts of data, like a summary statistic, geographical feature name or ID, or a line of text. Larger windows, holding multiline text, images, etc., typically range between 250-350px wide and 100-400px tall. On some maps, both sizes can be used in tandem to good effect, like in the&nbsp;[University of Wisconsin&nbsp;Campus Map][2]&nbsp;below:  
  
![uwCampusProbes](cartography2/images/DataProbing/uwcampusprobes.jpg)  
*University of Wisconsin Campus Map, showing large and small info windows.*

Instead of expanding much beyond the larger size mentioned, its worth considering ways of organizing info window content&nbsp;to keep the footprint compact. One solution we really like is the idea of using tabs to categorize content and/or mini-slideshows for previewing distinct chunks of material. EveryBlock’s&nbsp;[city maps][4]&nbsp;and Stamen Design’s&nbsp;[London 2012 map][5]&nbsp;are good examples:

![everyblock_probeSlideshow](cartography2/images/DataProbing/everyblock_probeSlideshow.jpg)  
*EveryBlock info window, showing mini-slideshow content.*

![stamen_probeTabs](cartography2/images/DataProbing/stamen_probetabs.jpg)  
*London 2012 info window, showing tabbed content.*  
  


We also like the idea of info windows that&nbsp;*re-size dynamically*&nbsp;(within limits) to best fit their content. When content is just a bit larger than a probe window, this can prevent the need for a scroll bar, which just creates extra work for the map user. Conversely, when content is small, the window shrinks to fit, avoiding big blank spaces that unnecessarily obscure the map. Really large amounts of content, like a full news article, are probably best presented on a new page or somewhere off the map and retrieved via hyperlinks (e.g., "more", or “full text”).  
  


![avoidProbe_blankSpace](cartography2/images/DataProbing/avoidprobe_blankspace.jpg)  
*Avoid too much empty space.*  


  
2) Position  
If we apply what we learn from&nbsp;[Eduard Imhof][9]’s work on label positioning, the preferred place for an info window attached to points and other small objects would be&nbsp;*to the right and somewhat above*. In contrast, left and in-line positioning would be less desirable, although Imhof acknowledges that any placement is permissible and sometimes even necessary. Compared to positioning map labels, however, info windows are somewhat of a unique challenge. This is partly because they tend to be larger in size and partly because of our interest in keeping them on screen when opened near the edges of a map or application window.

![avoidProbe_cutOff](cartography2/images/DataProbing/avoidprobe_cutoff.jpg)  
*Avoid cutting-off info windows.*  


  
Perhaps the most common approach to keeping info windows on the screen is to&nbsp;*auto-pan the map*. This works especially well if the map extent is limitless in all directions, because there’s no concern about auto-panning off the edge. Too much auto panning, however, can be *disorienting*, especially when the action itself is unexpected or the distance and speed of panning are too great. Auto panning can also be *disrupting* to users, due to a change in the map extent, which can alter the location or visibility of markers and data layers previously in view.

One ‘smart’ info window that I really like repositions itself left/right/top/bottom around a probed location to stay on screen AND minimize the amount of auto-panning. There’s a [working example][11]&nbsp;and&nbsp;[source code][12]&nbsp;for this by Dmitir Abramov.&nbsp;Maybe, a ‘super-smart’ info window would also be aware of related geo-data (e.g., map markers) and reposition itself to minimize contact with that, as well?  
  
3) Stem  
The info window stem is the visual link that connects it to a probed location. The problem of obscuring map context&nbsp;*in the immediate spatial neighborhood*&nbsp;can be solved by lengthening and/or shifting the stem along the window’s edge. It’s often the immediate geographical context that we’re most interested in, anyway. The question, ‘what’s near here?’ can be as interesting, if not more interesting than ‘what’s here?’. So, generally speaking, we prefer longish tails, but can think of cases where a short tail would be preferred (e.g., like on cell phone maps or other tiny map windows).  


![longStem](cartography2/images/DataProbing/longstem.jpg)  
*Longer stems can reveal neighboring map context.*  


  
Another option is to go without a stem at all, which keeps the area around a probed location totally open. The strong connection between location and info window is lost, but this can be restored to some degree with a highlighting technique, like in the The New York Times map,&nbsp;[Geography of a Recession][14], below. Here, the highlight (black outline) gives users positive feedback and helps link it to the info window, which appears/disappears on mouse-over/off. For stemless windows that are persistent, (i.e., require a click to open and/or close) highlighting becomes even more important to maintain this visual connection.  
  


![nyTimes_stemlessProbe](cartography2/images/DataProbing/nytimes_stemlessprobe.jpg)  
*New York Times info window without a stem.*  


  
4) Open/Close  
Opening and closing an info window should be immediately obvious to users. The advantage of mouse-over windows, like in the NYTimes example above, is that they appear with almost no effort at all and can’t easily be missed. However, this ‘always on’ nature can make if feel ‘in the way’ sometimes, especially if finding non-probable map or window space takes work.  
A really obvious “X” button in the upper right corner is maybe the most immediately obvious way to close a probe. Clicking ‘away’ from the info window itself can also be effective, as long as other uses for a mouse click are also considered. In other words, should an info window close upon click%2Bdrag map panning? (Probably not.) Should it close when another location is probed via mouse click? (Probably, yes.)  
One option that I don’t see too much of is that for opening&nbsp;*multiple info windows simultaneously*. Two or more open windows is very basic, yet invaluable, way of comparing details across locations. Universal Mind’s&nbsp;[LaunchPad demo][16]&nbsp;(below) allows users to open multiple info windows and then drag-and-drop them anywhere on the map. A similar approach might give users the option of “pinning” info windows to the map at their stem points, thus maintaining stronger visual linkages to locations. Perhaps, the windows could also be repositioned, with stems changing in length and direction.  


![universalMind_multiProbe](cartography2/images/DataProbing/universalmind_multiprobe.jpg)  
*Universal Mind's LaunchPad, showing multiple info windows.*  


  
5) Look and Feel  


*   Drop Shadow.&nbsp;Drop shadows helps focus attention on info windows, elevating them above other map content and setting them apart from visually complex map backgrounds.




*   Window Corners.&nbsp;Choice of square or rounded corners is mostly a stylistic decision. If rounded, make sure that the corner radius stays constant when scaling dynamically ([9-slice scaling][18]&nbsp;works well for this).




*   Title.&nbsp;Window titles should help users answer basic questions like, ‘what are we looking at here?’, or ‘what is the name / address of this probed location?’




*   Graphic Styles.&nbsp;Good use of type styles and colors, background color, and/or subtle divider lines can help organize content and go along way in making it faster and easier to read.




*   Transparency.&nbsp;Window transparency can help by revealing underlying map content, but should be used with caution. Not enough and it can go unnoticed or be of little use, too much and it can create legibility problems or hinder our ability to focus attention on the window. It's worth considering the kind of window content being displayed as well as the base map that windows appear on. For example, long text descriptions are perhaps more tiring to read on transparent backgrounds than short ones, especially if the underlying base map is visually complex, such as a satellite image with lots of colors, textures, etc.




*   Stem Position and Angle.&nbsp;Stems positioned too closely to a corner can appear somewhat unstable. An angled stem, as opposed to a stem that extends perpendicularly from a side, can add a bit of visual interest, but too sharp of an angle can appear awkward, as shown below.&nbsp;Corner-anchored stems, although more uncommon, distance a window farther from its location than side-anchored stems, assuming equal lengths. They seem to appear most stable when extending at about 45 degrees (see below).

  
![angleProbes](cartography2/images/DataProbing/angleprobes.jpg)  
*Stems at steep angles or near corners appear less stable.*

![cornerProbe](cartography2/images/DataProbing/cornerprobe.jpg)  
*Corner stems appear most stable at a 45-degree angle.*

Alternatives to Info Windows

There are plenty of examples in which data probing doesn’t bring up an info window at all. Rather, data is presented in some other part of the page or user interface. Although obscuring map surface area can be avoided this way, one issue to consider is&nbsp;split attention. This can weaken linkages and create more work for the user, whose attention has to be in multiple places–and potentially across large distances–on screen.&nbsp;[OpenStreetMap][21]&nbsp;and&nbsp;[Flickr’s Yahoo! Maps mashup][22]&nbsp;are both good examples of this alternative.

**![osmProbe](cartography2/images/DataProbing/osmprobe.jpg)**  
*OpenStreetMap splits apart a probed location (blue outline) and its related info.*

![flickrProbe](cartography2/images/DataProbing/flickrprobe.jpg)  
*Flickr's map also splits apart a probed location (white star outline) and its info.*

Other Examples of Info Windows

1) Bing Maps

**![bingProbe](cartography2/images/DataProbing/bingprobe.jpg)**  


*   Mouse over/off to open/close
*   Dynamic window and stem positioning
*   No auto-panning
*   Short stem
*   Dynamic scaling

  
2) Google Maps**![googleProbe](cartography2/images/DataProbing/googleprobe.jpg)**  
*   Click to open/close
*   Window and stem are fixed position
*   Auto-pan to stay on screen
*   Long stem
*   Dynamic scaling

  
3) Stamen Design, Oakland Crimespotting  
  
![stamenProbe_2](cartography2/images/DataProbing/stamenprobe_2.jpg)  
*   Click to open/close
*   Scrolling content
*   Fixed size and position
*   Short stem
*   Semi-transparent background

  
4) Washington Post, Time-Space: World**![washPost_probe](cartography2/images/DataProbing/washpost_probe.jpg)**  
*   Modified Google info window
*   Click to open/close (smaller info window on mouse-over)
*   Blue scroll buttons move between points in the cluster for a unique way of organizing content

  
5) Yahoo! Maps  
  
![yahooProbe_2](cartography2/images/DataProbing/yahooprobe_2.jpg)  
*   Click to open/close (smaller info window on mouse-over)
*   Window and stem are fixed position
*   Auto-pan to stay on screen
*   Short stem at corner position
*   Dynamic scaling

 [1]: /web/20100609152251/http://maps.google.com/maps?f=q&amp;source=s_q&amp;hl=en&amp;geocode=&amp;q=chicago,%2Bil&amp;sll=37.0625,-95.677068&amp;sspn=54.753001,74.179688&amp;ie=UTF8&amp;ll=41.908409,-87.624207&amp;spn=0.406764,0.579529&amp;t=h&amp;z=11&amp;iwloc=poi1
 [2]: http://web.archive.org/web/20100609152251/http%3A/www.map.wisc.edu/
 [3]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/uwcampusprobes.jpg
 [4]: http://web.archive.org/web/20100609152251/http%3A/chicago.everyblock.com/
 [5]: http://web.archive.org/web/20100609152251/http%3A/www.london2012.com/in-your-area/map/index.php
 [6]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/everyblock_probeslideshow.jpg
 [7]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/stamen_probetabs.jpg
 [8]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/avoidprobe_blankspace.jpg
 [9]: http://web.archive.org/web/20100609152251/http%3A/en.wikipedia.org/wiki/Eduard_Imhof
 [10]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/avoidprobe_cutoff.jpg
 [11]: http://web.archive.org/web/20100609152251/http%3A/gmaps-samples-flash.googlecode.com/svn/trunk/demos/SmartInfoWindowDemo/SmartInfoWindowDemo.html
 [12]: http://web.archive.org/web/20100609152251/http%3A/gmaps-samples-flash.googlecode.com/svn/trunk/demos/SmartInfoWindowDemo/srcview/index.html
 [13]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/longstem.jpg
 [14]: http://web.archive.org/web/20100609152251/http%3A/www.nytimes.com/interactive/2009/03/03/us/20090303_LEONHARDT.html
 [15]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/nytimes_stemlessprobe.jpg
 [16]: http://web.archive.org/web/20100609152251/http%3A/www.universalmind.com/demo/launchpad/GeoLayer.html
 [17]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/universalmind_multiprobe.jpg
 [18]: /web/20100609152251/http://livedocs.adobe.com/flash/9.0/UsingFlash/help.html?content=WSd60f23110762d6b883b18f10cb1fe1af6-7db8.html
 [19]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/angleprobes.jpg
 [20]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/cornerprobe.jpg
 [21]: http://web.archive.org/web/20100609152251/http%3A/www.openstreetmap.org/
 [22]: http://web.archive.org/web/20100609152251/http%3A/www.flickr.com/map/
 [23]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/osmprobe.jpg
 [24]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/flickrprobe.jpg
 [25]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/bingprobe.jpg
 [26]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/googleprobe.jpg
 [27]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/stamenprobe_2.jpg
 [28]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/washpost_probe.jpg
 [29]: http://web.archive.org/web/20100609152251im_/http%3A/cartography2.org/Chapters/page8/files/yahooprobe_2.jpg  