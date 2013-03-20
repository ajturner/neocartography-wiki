
[Permalink](http://web.archive.org/web/20110830175707/http://cartography2.org/Chapters/page5/CartographicText.html "Permalink to Cartography 2.0 - Cartographic Text")

# Cartography 2.0 - Cartographic Text

Ben Sheesley, Axis Maps LLC
date: 09/01/09

The letters, numbers, words, phrases, etc.—the text—on the face of maps deepens our understanding of a place in ways that other graphical elements (e.g., color) cannot. Most of the maps that I encounter, whether in print or online, rely on text for one reason or another to get their message across. Without it, most would end up looking a lot more like pretty pictures than the dense information graphics they were intended to be.
Digging a little deeper, we discover a wide range of purposes for cartographic text. My default thinking tends to be that text is for naming things, but clearly it can do much more than that on the map.&nbsp;For example, map labels can reflect the character of geographical features (e.g., a curving river label), indicate the relationships between them, confirm the locations of places (e.g., a country label spread out within its boundary), describe space (e.g., lat/long measurements), and encode quantitative data. We can see many of these at work on almost any common reference map. More creative ideas for visualizing text, like Andy Woodruff’s work on&nbsp;

[mapping&nbsp;campaign rhetoric][1] using [tag clouds as map symbols][2] and the [New York Times's Twitter map][3] are great examples of text serving analytical purposes on dynamic and interactive, thematic maps.&nbsp;
Cartographic text can also serve aesthetic, or expressive purposes that impact the ‘look and feel’ of maps. In other words, text can evoke emotions in map readers, connote a range of map messages and themes, or be used to create or strengthen graphic identities. For example, the aesthetic qualities of National Geographic’s type family (e.g., the brush-like strokes of some letterforms) and labeling techniques (e.g., the gentle curvature of coastal city labels) go a long way in forming its (carto)graphic identity, perhaps even more so than the colors, icons, terrain representation, or map projection employed on its general reference maps. 

[TypeBrewer][4] is one place for exploring the expressive nature of map text, allowing users to see the effects of a range of typographic alternatives, including fonts and font pairings, on map ‘look and feel’.  
  
![ngs_text_400][5]  
Besides its many functional purposes, the text on this NGS reference map helps define its cartographic identity.  


  
The various purposes of cartographic text bring to light the challenges of the map lettering task. Generally, this is broken into two separate, but interrelated parts: type selection and type placement (i.e., positioning). Selection involves choosing the visual properties, or typographic elements, for text on the map, including type family, style, size, case, color, and tracking, whereas placement deals with the graphic association of labels with particular geographical features. Cartographers have long been interested in developing design guidelines for type selection, some of which are based on empirical research for determining legibility and people's ability to search and scan text, for example. Check out the [guidelines][6] that Prof. John Krygier talks about to his cartography students. Similarly, there has long been a desire to develop improved type placement algorithms and the automated systems that can make this half of the lettering task more efficient, some of which have become quite outstanding (e.g., [Maplex][7]).

In theory, ‘good’ map lettering can increase the likelihood that text will serve its intended purpose and make for a meaningful map. ‘Poor’ lettering, on the other hand, can result in slow or inaccurate map reading and scanning, the misinterpretation of data, or text that appears visually distracting and unsophisticated. While the consequences of misreading labels on a driving directions map might be frustrating to you and me, the implications of text misread in the field by a military officer or flight control operator can go much deeper.

In practice, map lettering is a highly iterative and often very time consuming component of mapmaking. Just changing the size of a single label, for example, will routinely require some amount of repositioning and shuffling around so that labels can&nbsp;co-exist in harmony with each other and the multitude of other map symbols, (complex) backgrounds, and graphical elements we find on maps. The task requires not only lots of patience and care, but also a strong cartographic and typographic sensibility.

Below, I'll look at just one of the practical design considerations related to type selection, namely choosing a font for maps to be displayed on screen. This is perhaps the first decision of the map lettering task and can have a significant effect on map legibility and readability, look and feel, and the ability of text to serve its intended purposes. Starting out with good choices also directly impacts the ease and efficiency of executing the task itself.

## Resolution  

Resolution is what determines how much detail we can see on screen. As the physical size of pixels gets smaller (and resolution increases), our ability to see details improves. For example, it’s no surprise that text looks clearer in high-definition than on a standard television display. The major type selection consideration here is legibility. Currently, on most computer screens we’re typically dealing with a resolution of between just 90 and 110 pixels per inch. That’s pretty low compared to what we can get out of even a common desktop inkjet printer, which can lay down ink between 300 and 600 dots per inch. Compared to the printed page, when fonts are viewed on screen we loose some of the details that make them legible and easy to read. Small finishing elements like serifs and ears can degrade, interior spaces like counters, apertures, eyes, and bowls can change shape or collapse, and stems and strokes can loose their intended weight, contrast and curvature. This is especially true at the small type sizes that cartographers often must deal with when lettering maps.

![letterformDiagram_cart2_v3][8]  
Many details in the anatomy of a font are particularly sensitive to display at small sizes on screen  


Anti-Aliasing  
The common solution for rendering fonts on screen is called anti-aliasing. Basically, shades of gray are applied to the pixels in and around fonts to give them the appearance of having smooth, curved edges and other subtle variations in form that would otherwise lost on screen. Here's the classic illustration of anti-aliasing:  
  


![antiAliasing_v2][9]  


Anti-aliasing can produce great results at larger font sizes, but tends to&nbsp;cause fonts to look clumpy and blurry&nbsp;at small sizes. Some of the software that cartographers are familiar with offer a lot of control in this area, which in some cases can help mitigate this problem. For example, in addition to several nice defaults (e.g., anti-aliasing for "readability"), Adobe Flash offers advanced, customizable anti-aliasing options for font sharpness and thickness, as shown in this [demo][10] and source [code][11]. You'll find a similar suite of options in Adobe Photoshop that can help crisp or sharpen small text.

![psd_antiAliasing][12]  
The range of anti-aliasing defaults in Photoshop. Anti-aliasing tends to hurt more than help below around 9 points.  


## Pixel Fonts 

Given the trouble of blurriness with small anti-aliased text, why not consider removing anti-aliasing, or going with a pixel (bitmap) font as an alternative? True pixel fonts are designed by arranging pixels, not vectors, into letterforms. They're intended to work without anti-aliasing at very small sizes—8 points and lower. Unfortunately, by nature, they only work at&nbsp;fixed sizes (and then at multiples of their original size) and along horizontal or vertical rows.&nbsp;So, as much as I like them for some purposes (e.g., small interface text), pixel fonts don't scale well across small size ranges, nor can they be rotated and curved along paths. The following example shows a pixel font ([Unibody 8][13]) in action on a map:  


![bitmapText][14]  
The Pixel City label (8 pt size) works well because it is oriented horizontally. The other labels (8 and 16 pt sizes) break down along curved paths.  


## Minimum Size 

As a general rule, we hesitate to go below 10 points as the minimum point size for screen-based maps. (For comparison, type at 6 pts and below is common on print maps). While 9 point type (or smaller) can be legible (as in the example above), it may require more work from the map user or be more likely to result in reading errors than type that is just one or two points larger. Of course, different typefaces and different reading conditions produce different results, so each should be examined and tested individually. Will the map be viewed on a new high-definition plasma TV, a 5-year old VGA laptop, or a handheld GPS device? Who is the intended audience? Does it consist of younger or older people? Answers to these are often unknown, especially when designing maps for the Web. This can mean considering a small size that will be legible for the ‘lowest common denominator’.

Selecting a Type Family for the Screen  
Fortunately, there are a few fonts pre-installed on our operating systems designed specifically to meet the challenges of the computer screen: [Georgia][15], [Trebuchet MS][16], and [Verdana][17].

![screenFonts_2][18]

What makes the above fonts ideal candidates for the screen? And, what are the main things to consider when selecting fonts for maps that will appear on screen so that when the opportunity arises, we can branch out beyond these defaults? Given an exponential increase in the number of fonts readily (and often freely) available for immediate use, this is an important skill that can save time and effort as well as improve the quality of map lettering.

*   Width and Spacing.&nbsp; Wide letterforms and generous letter spacing, like in Verdana (see above example), can help prevent interior spaces (i.e., counters) in letters from collapsing and letters from colliding, especially at small sizes. However, both come at the expense of overall text width, which can be a turn-off in high-density labeling scenarios. While adjusting letter spacing, also known as "tracking", has its place on maps (e.g., to fit labels to areas or lower them in the overall visual hierarchy), choosing a structurally more narrow type family is preferred to negatively spacing or scaling text, both of which should be used sparingly, if at all. Note that some fonts, like Arial, have a “narrow” variant with condensed proportions. These can appear smaller&nbsp;than their “regular” counterparts&nbsp;despite similar or even identical x-heights, so care should be taken when using them on the map.![narrowFonts_2][19]




*   Stroke Weight and Contrast.&nbsp;&nbsp;Like serifs, the stems and strokes that help define characters must also be robust enough to hold up on screen. Again, this tends to become an issue in the small size range (9-12 points) where cartographers often spend most of their time. In this range, the “thin” or “light” variants of type families should usually be avoided in favor of “regular” or heavier weights. More specifically, the&nbsp;strokes in some fonts can vary in width within singe letterforms. The amount thick-thin variation is known as stroke&nbsp;contrast. High contrast fonts tend to be less suitable for the screen because their thin portions can deteriorate, especially at small sizes.




*   Hinting.&nbsp; [Hinting][20] is&nbsp;one way in which type designers can precisely control the way font outlines are mapped to specific pixels. ‘Hints’ are encoded in font files for rendering purposes and have a big impact on legibility, especially at small text sizes when some letters are not much more than 5-6 pixels in height. Beware of knock-off fonts that are poorly hinted versions of professionally hinted originals.

## Case Study in Selecting a Map Font

Despite the vast number of fonts available to choose from, we’ve found that only a few serve our purposes well and therefore we tend to return to them over and over again. Officina (both [Officina Sans][21]and [Officina Serif][22])&nbsp;is one such font (a font family, really) that we've found to be highly versatile, employing it on everything from map user interfaces to printed reference maps. It was&nbsp;originally designed by Erik Spiekermann as a robust font for business correspondence, including memos, faxes, photocopies, and other documents output at course resolutions. A number of design characteristics, drawn from the list above, make it an ideal candidate for maps appearing on screen. Officina&nbsp;has a tall x-height, wide&nbsp;apertures&nbsp;and large&nbsp;counters, as seen in the letters 'c', 'a', and 'e', for example.&nbsp;Serifs&nbsp;are blocky and square in shape, and strokes are consistently strong, having low contrast.&nbsp;By design, Officina is also a relatively narrow type family (considerably narrower than Trebuchet MS but not as condensed as Arial Narrow, for example), which makes it effective in high density labeling scenarios.
![officina][23]  
Sample of the Officina font family

![UWarb_mapUI][24]  
Besides the tab titles (e.g., "Go"), Officina Sans is used for all of the interface text on the UW Arboretum interactive map

![ARRAfunding_new][25]  
Officina Sans and Officina Serif are used in all of the explanatory text on this ARRA funding map

![bestWestern_new][26]  
Officina Sans and Officina Serif have been employed for all of the labeling on this Best Western Hotel visitor's map  


  
There are a few more reasons we like Officina, as well. Although not directly pertaining to the limitations of the screen, these points are worth considering when selecting a map font in general:  


*   "Depth" of Family.&nbsp;Officina consists of a complementary sans and serif family, each with all of the major members (e.g., book, book italic, bold, bold italic). Pairing fonts can add an air of sophistication to the map, but selecting an appropriate combination can be challenging. So, whenever I see a serif and a sans serif designed to co-exist, I take a closer look. Together, the eight styles of the greater Officina family give us a full set of options for categorizing and differentiating a variety of map features (and interface elements) while maintaining an overall unified map 'look and feel'.




*   Character Set.&nbsp; As offered by the International Typeface Corporation, Officina contains a large [character set][27],&nbsp;including glyphs with all those accents and other special characters we commonly need on maps, especially when dealing with foreign languages.




*   Numerals.&nbsp; Numbers in Officina are "lining", as opposed to "non-lining", or "old-style". In other words, they don't have descenders that dip below the baseline. Non-lining numbers are perhaps best used in body text where they flow nicely among other words, which have similar shapes. On maps, its worth considering lining numerals because they can fit into tighter spaces more easily, including small symbols and icons.




*   True Italic.&nbsp;&nbsp;A true italic is a uniquely designed font, whereas a 'faux' italic is simply a slanted or oblique version of a Roman form. True italic fonts can add an air of sophistication to the map and help further distinguish them from their Roman counterparts. Look for letters like the lowercase 'a', 'f' and 'g' which often have a noticeably different structure in a true italic form.




*   Look and Feel.&nbsp;&nbsp;We think Officina looks really 'cool' and 'modern' yet can be applied to maps that serve a variety of purposes and audiences. Of course, our subjective reactions are likely to change over time with more general trends and styles.




*   File Format.&nbsp; Officina is available in the [Open Type][28] file format. In addition to a number of advanced typographic features, OT fonts are cross-platform compatible, which from a development perspective make them a viable option when collaborating on a project.

  
## Recommended Reading  


Books:  
Brewer, Cynthia A. 2005.&nbsp;[Designing Better Maps: A Guide for GIS Users][29]. ESRI Press: Redlands.

Lupton, Ellen. 2004. [Thinking with Type: A Critical Guide for Designers, Writers, ][30][Editors and Students][31]. New York: Princeton Architectural Press.  
  
Articles:  
Bartz, Barbara. 1970. Experimental Use of the Search Task in an Analysis of Type Legibility in Cartography. The&nbsp;Cartographic Journal&nbsp;7: 103-12.  
  
Brumberger, Eva R. 2003. The Rhetoric of Typography: The Persona of Typeface and Text. Technical Communication 51(1): 13-24.  
  
Fairbairn, D.J. 1993. On the Nature of Cartographic Text. The Cartographic Journal 30(2): 104-111.  
  
Phillips., R.J. 1977. The Legibility of Type on Maps. Ergonomics 20(6): 671-82.  
  
Shortridge, Barbara Gimla. 1979. Map Reader Discrimination of Lettering Size. American Cartographer 6(1): 13-20.  
  
Woodward, David. 1982. Map Design and the National Consciousness: Typography and the Look of Topographic Maps. In Technical Papers of the American Congress on Surveying and Mapping. Falls Church, Va.

 [1]: http://web.archive.org/web/20110830175707/http%3A/www.axismaps.com/blog/2008/10/the-geography-of-presidential-campaign-rhetoric/
 [2]: http://web.archive.org/web/20110830175707/http%3A/www.cartogrammar.com/blog/mapping-tag-clouds/
 [3]: http://web.archive.org/web/20110830175707/http%3A/www.nytimes.com/interactive/2009/02/02/sports/20090202_superbowl_twitter.html
 [4]: http://web.archive.org/web/20110830175707/http%3A/www.typebrewer.org/typebrewer.html
 [5]: http://web.archive.org/web/20110830175707im_/http%3A/cartography2.org/Chapters/page5/files/ngs_text_400.jpg
 [6]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fkrygier.owu.edu%2Fkrygier_html%2Fgeog_353%2Fgeog_353_lo%2Fgeog_353_lo10.html&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzczDy9ZS6R1HQHwJWl3khlCMxQO8Q
 [7]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fwww.esri.com%2Fsoftware%2Farcgis%2Fextensions%2Fmaplex%2Findex.html&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzfMEpls24xH1SzjI9vE_xuINtiOSg
 [8]: http://web.archive.org/web/20110830175707im_/http%3A/cartography2.org/Chapters/page5/files/letterformdiagram_cart2_v3-3-2.jpg
 [9]: http://web.archive.org/web/20110830175707im_/http%3A/cartography2.org/Chapters/page5/files/antialiasing_v2-2.jpg
 [10]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fblog.flexexamples.com%2F2007%2F10%2F24%2Fsetting-a-fonts-anti-alias-type-sharpness-thickness-and-grid-fit-type-in-flex%2F&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzdr-Eyx4yNyzJTmQfYDzMRjJkYTYw
 [11]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fblog.flexexamples.com%2Fwp-content%2Fuploads%2FLabel_fontAntiAliasType_test%2Fbin%2Fsrcview%2Findex.html&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzdARijstaZndYzO80Y7bpwlfQmkdA
 [12]: http://web.archive.org/web/20110830175707im_/http%3A/cartography2.org/Chapters/page5/files/psd_antialiasing.jpg
 [13]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fwww.underware.nl%2Fsite2%2Findex.php%3Fid1%3Dunibody%26id2%3Dinfo&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzfF2P3odWnMJ5tOwnB-xdiKqpaljw
 [14]: http://web.archive.org/web/20110830175707im_/http%3A/cartography2.org/Chapters/page5/files/bitmaptext.jpg
 [15]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fwww.microsoft.com%2Ftypography%2Ffonts%2Ffamily.aspx%3FFID%3D4&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzcJ7rnnE3xOPB0f5LmhFmaW80DMuw
 [16]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fwww.microsoft.com%2Ftypography%2Ffonts%2Ffamily.aspx%3FFID%3D2&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzchrSVOuS9GjIopztnIvbb9YyFCPA
 [17]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fwww.microsoft.com%2Ftypography%2Ffonts%2Ffamily.aspx%3FFID%3D1&amp;sa=D&amp;sntz=1&amp;usg=AFrqEze9afXcKI6PYbdBklLObP8r4Li4xw
 [18]: http://web.archive.org/web/20110830175707im_/http%3A/cartography2.org/Chapters/page5/files/screenfonts_2.jpg
 [19]: http://web.archive.org/web/20110830175707im_/http%3A/cartography2.org/Chapters/page5/files/narrowfonts_2.jpg
 [20]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fen.wikipedia.org%2Fwiki%2FFont_hinting&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzcFR5GqBm0-u_CFbRaTqlfBfuvzkQ
 [21]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fnew.myfonts.com%2Ffonts%2Fitc%2Fofficina-sans%2F&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzcIFlyQZe_2A8iVxgM9skyiNOzPUg
 [22]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fnew.myfonts.com%2Ffonts%2Fadobe%2Fitc-officina-serif%2F&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzd16Kn39Js5Jp4JRKVJZGNX56skLw
 [23]: http://web.archive.org/web/20110830175707im_/http%3A/cartography2.org/Chapters/page5/files/officina.jpg
 [24]: http://web.archive.org/web/20110830175707im_/http%3A/cartography2.org/Chapters/page5/files/uwarb_mapui.jpg
 [25]: http://web.archive.org/web/20110830175707im_/http%3A/cartography2.org/Chapters/page5/files/arrafunding_new.jpg
 [26]: http://web.archive.org/web/20110830175707im_/http%3A/cartography2.org/Chapters/page5/files/bestwestern_new.jpg
 [27]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fwww.itcfonts.com%2Ffonts%2Fcharsets&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzcB9mmxDCzqT7aMD7pCsRW49R2TSw
 [28]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Fen.wikipedia.org%2Fwiki%2FOpenType&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzepNNKERVRSdMG_t8vCjIN1GZn84Q
 [29]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Famzn.com%2F1589480899&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzcA-Odn2SKTxi4bbREvpVTdjq16TQ
 [30]: http://web.archive.org/web/20110830175707/http%3A/sites.google.com/a/axismaps.com/cartography-2-0/Home/goog_1250200379139
 [31]: /web/20110830175707/http://www.google.com/url?q=http%3A%2F%2Famzn.com%2F1568984480&amp;sa=D&amp;sntz=1&amp;usg=AFrqEze3QJLuXZOWG4NkFTLtnhey7sBNSw  