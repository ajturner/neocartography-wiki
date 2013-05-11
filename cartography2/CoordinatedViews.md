[Permalink](http://web.archive.org/web/20091130140927/http://cartography2.org/Chapters/page14/CoordinatedViews.html "Permalink to Cartography 2.0 - Coordinated Views, Brushing, & Highlighting")

# Cartography 2.0 - Coordinated Views, Brushing, & Highlighting

Anthony Robinson, GeoVISTA Center, Penn State
9/20/09

Making Connentions
Put simply, making connections is what each of these three techniques is designed to support. Each technique provides support for letting the user “drive” the geovisualization in a highly interactive manner. In contrast to the computational side of geovisualization, these methods emphasize the use of visual cues to discover and analyze patterns.

Multiple, coordinated views

The basic idea here is that a single data representation won’t support all possible types of inference or discovery. For example, I might have access to an interesting spatial data set containing the locations of people sick with swine flu and their movement over time. One way I could show this data is to create an animated choropleth map by aggregating the data to some sort of boundary units (let’s say by county) and coloring those units for each time period based on the number of cases they contain.

![CMV_Example_1](cartography2/images/CoordinatedViews/cmv_example_1.jpg)

This would support some basic analysis of the disease pattern over time, but what if I was also interested in possible relationships between sick people and demographic information (per capita income, educational attainment, etc…)? I could come up with a hybrid map design that encoded a bunch of variables, right?

An alternative approach is to simply provide multiple representations (views) onto the data. So in the disease example I might expand my views to include the animated choropleth map along with a scatterplot showing the relationship between income and education. You can see where this is headed – there are lots of different ways to view that same data, each with its own analytical advantages. In many cases a variety of views can lead to a variety of analytical capabilities, but it's not something you want to overdo - take some time to decide which views you really need and which might just be eye-candy (3D space-time cubes, anyone?).

![CMV_Example_2](cartography2/images/CoordinatedViews/cmv_example_2.jpg)  


Having developed multiple views, you need to consider how they can really work together, and that’s where the idea of coordination comes into play. The goal of coordination is to support the user’s ability to look at data in one view and quickly find/analyze that same observation in another view. Different toolkits support coordination across views in different ways. Most commonly, things like color schemes, classification, mouse selections, and mouseover highlighting are coordinated. In the example shown above, the two views are coordinated in terms of their color scheme and classification (color and class breaks are applied the same way in both views). In the example shown below (a screenshot from the [GeoViz Toolkit][3] showing 2008 election results in multiple, coordinated views) color and classification are **not **coordinated, but mouse selection is coordinated. One county has been interactively selected and appears highlighted in each of the four views.

![CMV_Example_GVT_Coordination](cartography2/images/CoordinatedViews/cmv_example_gvt_coordination.jpg)

Brushing  


  
A key component of multiple-coordinated view tools is that coordination is supported by brushing, which is the interactive selection of one or more data points across multiple views. For example, you might select a bunch of counties in a map with your mouse, and brushing enables this selection to propagate to other views (like a scatterplot, for example). The “brush” name comes from the idea that your mouse cursor is virtually “painting” one of the views to select items and see where they show up elsewhere. There are all sorts of variations on this theme that are possible, but the basic idea remains the same – what the user does in one view is passed along to the other views in a way that is visible and supports comparisons. Research has shown that brushing helps users identify outliers, clusters, and other patterns in data that otherwise might not be easily detected ([Baldonado et al., 2000][5]). 

![CMV_Example_3](cartography2/images/CoordinatedViews/cmv_example_3.jpg)  


In the graphic above you'll see an example of interactive brushing. The user drags a selection box over part of northern Florida and the corresponding counties light up (outlined in yellow) in the scatterplot to show where those observations fall when comparing educational attainment and per capita income. 

  
Highlighting  


  
The difference between brushing and highlighting is that brushing is the fundamental action of selecting data across multiple views, while highlighting refers to the visual techniques used to make those selections visually apparent.

For the most part, geovisualization and other interactive visualization tools make use of color to highlight items across views. This makes sense – color is a pre-attentive visual encoding. A pre-attentive visual encoding is something that can be processed immediately without focused thought or attention ([see the infovis wiki for details][7]). This means that humans are quite good at picking out “hot” colors like bright red or yellow to identify things of interest.

![Highlight_Example_1](cartography2/images/CoordinatedViews/highlight_example_1.jpg)  
*see the concept in action **[here][9]*

We are conducting research at the GeoVISTA Center at Penn State on the use of these different highlighting techniques through our GeoViz Toolkit project, with the goal of measuring whether or not some of them might offer advantages over using color. It’s an open question so far – should we stick with color or are there other things that would make geovisual analysis easier to do? In my observations so far, leader lines work really nicely and allow the user to visually track an item of interest from one view to another. In demos of our GeoViz Toolkit with depth-of-field and transparency highlighting enabled we have also had a great deal of positive feedback from users, most of whom have never seen anything quite like it before. I'm sure there's something of a "novelty" effect here, but I also think it's possible that one of these other methods besides color is at least as good, if not better in terms of raw performance (i.e. how long does it take you to identify the item of interest in each of the coordinated views).

To wrap things up, here are a few basics on multiple coordinated views:

1.  Multiple views on data can be quite powerful, but each view should offer something unique in terms of analytical power
2.  Coordination is the underlying software mechanism that allows data and data representations to be shared across views
3.  Brushing lets you select something in one view and see that selection in the other views
4.  Highlighting is an interactive visual effect that helps separate selected data from its context
5.  Color isn't the only way you can highlight something - try depth of field blurring, transparency, and leader lines too

* * *

Except where otherwise noted, content on this site available under a [Creative Commons 3.0 License][10]

 [1]: http://web.archive.org/web/20091130140927im_/http%3A/cartography2.org/Chapters/page14/files/cmv_example_1.jpg
 [2]: http://web.archive.org/web/20091130140927im_/http%3A/cartography2.org/Chapters/page14/files/cmv_example_2.jpg
 [3]: http://web.archive.org/web/20091130140927/http%3A/www.geovista.psu.edu/geoviztoolkit/
 [4]: http://web.archive.org/web/20091130140927im_/http%3A/cartography2.org/Chapters/page14/files/cmv_example_gvt_coordination.jpg
 [5]: /web/20091130140927/http://portal.acm.org/citation.cfm?id=345271
 [6]: http://web.archive.org/web/20091130140927im_/http%3A/cartography2.org/Chapters/page14/files/cmv_example_3.jpg
 [7]: http://web.archive.org/web/20091130140927/http%3A/www.infovis-wiki.net/index.php/Preattentive_processing
 []: http://web.archive.org/web/20091130140927/http%3A/www.personal.psu.edu/acr181/hlight.swf
 [9]: http://web.archive.org/web/20091130140927/http%3A/www.personal.psu.edu/acr181/hlight.swf
 [10]: http://web.archive.org/web/20091130140927/http%3A/creativecommons.org/licenses/by-nc-sa/3.0/us/  