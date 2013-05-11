
[Permalink](http://web.archive.org/web/20100702154019/http://cartography2.org/Chapters/page10/OverviewUI.html "Permalink to Cartography 2.0 - Overview of the User Interface (UI)")

# Cartography 2.0 - Overview of the User Interface (UI)

by Mark Harrower
date: 09/12/09

Three basic questions underpin the development of all interactive mapping systems:(1) What type of interactivity is needed (*kind of control*)?
(2) 

How much interactivity is needed (*degree of control*)? 
(3) How should this interactivity 

be implemented (*method of control*)?  
  
WHY THIS MATTERS: The articles within this UI and Usability section will help you to answer those questions and will encourage you to develop a careful, objective approach to each map you make so that (1) you don't waste your time or your employer's money on bad ideas, and (2) you can increase the chances that your maps will work once they are released into the wild.
Many of us, more often than we'd like to admit, have felt the sting of showing people our work 

only to have them confused by what we thought was a great user interface, or worse, see them underwhelmed by our work (I remember cringing once upon hearing "so, um, I can't click on anything...I just pan and zoom?"). While you can't hit a home run every time, you'll sleep better knowing your map is both useful and easy to use. In order to get to that cartographic Nirvana, though, we're going to have to take a journey through the related fields of [Human Computer Interaction][1] and [Interface Design][2] (and [here][3]). Much of this might be old hat to you, and if you've used software or the Web for even a few minutes then you'll certainly recognize much of the advice and insights in this chapter. The pros know making good maps in the 21st century requires knowing a lot about stuff that seems way beyond the borders of "cartography." The user interface, and how people work with your map—a field called *[useability][4]*—is critically important. 
Five things all designers should always remember:

1. No matter how great your data or mapping skills are, if your user interface (UI for short) is opaque and cryptic your map will fail. Period.  
  
2. Don't try to be too clever. UI's that "show-off" should be avoided. For example, after 15 years, there are still homepages that make it really hard to find the buttons and content, and you spend a lot of time hunting around and clicking on stuff and nothing happens (well, expect for the rapid departure of most anyone over the age of 14). Bad UI designs don't make your work "edgy" and "cool," they just make it annoying.#3: We live in a mouse-happy culture where folks won't wait long. This problem is only getting worse as people now expect amazing maps and applications to work instantly. And let's be honest, we're all guilty of this. I know I often give up on content that was taking "too long" to load...maybe even after just two or three seconds. Our willingness to hang in there is low, especially if we didn't pay anything to be there in the first place; our time is the only cost for being there, so we try to save it accordingly. Bottom line: If your map is underwhelming, boring, or hard to use, folks will leave pretty quickly.#4: Don't design for youself: I don't really care, nor does the person writing your paycheck, if you think the map and UI are the coolest thing ever. Unless you're going to buy a hundred thousand copies of the map, check your ego and realize that not all of your good ideas will work and everyone, even seasoned pros, can benefit from some feedback. Design for your audience not for yourself or your friends. What's wrong with our friends? Well, they likely have similar tastes and skills and are not likely to be a representative sample. More importantly, they're your friends and don't want to hurt your feelings and may feel the need to sugarcoat feedback. I've had to redo large pieces of a project when it became clear my approach wasn't going to fly with the users. It's frustrating, but that's life. The key is to accept that there will be changes and the goal is to uncover those changes sooner rather than later in the process: test early, test often...test early, test often...rinse and repeat. A thick skin helps too.  
  
5.  Your job is to not be noticed: A good UI disappears after a few seconds, like the work of a good cinematographer. The work will leave a positive impression on you without you necessarily being able to say why. It's the difference between "Wow, what a cool film" and "Wow, what a great use of zoom shots and low camera angles." Why is this important? Becuase the UI is the barrier between your users and your content and you want that barrier to be as low as possible and ultimately to disappear. Remember, folks are trying to get at that content, don't make it too hard for them.  

### The Importance of the UI to Cartography  

The success of interactive maps depends in large part on the interface—not just the map itself. The interface defines both the functionality of the map—what the map can do for the user—and the learning curve—how quickly the user harnesses that functionality. At the heart of many problems that people encounter when using interactive maps is a mismatch between the capabilities of the system and the expectations of the user conditioned by their previous experiences with interactive maps (or lack thereof). For example, many users have become accustomed to directly grabbing a map to reposition it, and when this functionality is missing they may become confused, frustrated, and generally less confident in the mapping system. They may even conclude that the map simply does not work because it does not work the way they expected it to.

### Flattening the Learning Curve  
  
In our efforts to improve the design of interactive maps, it would seem that whatever interface control feels most “natural” or “intuitive” to the user is logically the one to use. Arguably, by identifying such controls we could flatten the learning curve and increase user productivity. There are, however, at least two problems with this approach.  
First, there is rarely if ever a single best way to implement some map control like panning or zooming since it depends upon both the user (e.g., prior experiences, level of motivation) and the task they are trying to execute. For example, HCI studies have shown that the most efficient text-scrolling tool depends on how far the user needs to move in the document. Hinckley et al. (2002) demonstrate that short scroll distances (  
Rule: Thus, there is no one-size-fits-all solution to UI Design, and good mapping systems incorporate multiple methods for achieving the same outcome.

The second problem in our search for “natural” map interface designs is that people acquire interface skills largely through exposure and repetition. Hence, those interface designs that are common (e.g., magnifying-glass zoom icon) will often feel the most natural although they may not represent the best possible implementation. For example, the QWERTY layout of the computer keyboard feels natural and is preferred by most users not because it is an inherently superior layout, but simply because it is familiar. In other words, an interface designed to be intentionally inefficient has become universally popular (The QWERTY layout was designed to slow down typists because early typewriters jammed easily). More importantly, the QWERTY layout was a machine-centric solution because it forced users into a work mode dictated by the limits of the technology rather than the needs of the user. 

It is our contention that (1) design decisions made in the early days of emerging technologies are often adopted uncritically when better alternatives may exist, and (2) those early decisions are often driven more by the technological limits of the day than by a larger understanding of users’ needs. Although typewriter technology improved to address the issue of jamming, the design of the keyboard had been irrevocably cast. Are we at risk of standardizing upon another QWERTY-like interface with digital mapping systems? Have machine-centric solutions been foisted upon map users that thereby constrain how we work and think? Have the dominant GIS software and online map vendors artificially constrained our thinking about what a map interface ought to look like?

POP-QUIZ: How many different ways can you open a file on your computer? Count them and think about how you seamlessly switch between them (common methods include double click, drag-n-drop, pulldown menu&gt;file&gt;open, "recent items"). It'd also be fair to say that one of these isn't always "the best one," because it depends on context. Try to build this same carefully considered flexbility into your own work.

### The Importance of Icons  
  
One of the best ways to flatten the learning curve is to rely on icons that are self-explanatory. While many [semioticians][5] would argue that no sign/icon can be completely self-explanatory, we can all agree that the marks on our maps span a continuum from very abstract—they don't look like anything specific and can thus stand for just about anything we want—through to highly realistic or pictorial—they look very close to something we immediate recognize and are strongly linked with one thing (see examples below). In semiotics, this is known as *the degree of iconicity.*  
  
UIs based on icons have three big advantages over those based on words. Consider these signs from an airport: 

![airport_icons2](cartography2/images/OverviewUI/airport_icons2.jpg)  


  
**(1)The're multi-lingual.** The word "baggage" isn't much good for the billions of people who don't read English. This is why airports makes such heavy use of pictorial icons.

**(2) They're compact.** Icons like this can usually be made smaller than their corresponding words, and certainly much much smaller than a list of words in multiple languages. A busy international airport would need to spell "baggage" in over a hundred languages. An MP3 music player could never be shrunk down to the very small sizes we see today if the UI had to use words.

**(3) They offer clues on what the user should do. **Highly iconic UIs, if well designed, can not only substitute for words, they can actually suggest how to use something (what are the actions required to operate it). The escalator icon above suggests "a person stands on this device."

![ag_08e320_pwrseat](cartography2/images/OverviewUI/ag_08e320_pwrseat.jpg)

[Don Norman][8] in his classic "[The Design of Everyday Things][9]" compliments Mercedes Benz for designing electric car seat controls that make great intuitive sense because the controls look like the chairs themselves: Moving the back of the seat icon moves the back of the seat, creating a very strong conceptual connection between UI action and physical outcome. The user doesn't have to translate a vague list of buttons into seat positions since the movement of the controls themselves mimic the very action the user is requesting. Even better, all of this can work by touch without the need to look at the UI controls for the seats (no need to take your eyes off the road).

Of course, icons are *not *fail-proof and I've encountered many that leave me utterly baffled. This can happen if the concept behind the icon is somewhat obtuse and there are few or no obvious graphic signfiers ("sign vehicles") to choose from. For example, I would be hard pressed to suggest an icon for *ennui* as distinct from a more general *disappointment* or *boredom*, although icon designers are a remarkably clever bunch so I might be wrong. 

![macKeyboard](cartography2/images/OverviewUI/macKeyboard.jpg)

I've also run into trouble with icons/buttons on devices that are **vague** and when used seemed to do nothing. For example, just recently I couldn't figure out what these two icons on my new laptop keyboard did (above). After searching on the internet for longer than I wanted I discovered they control the amount of backlight on my keyboard. I couldn't figure this out since it was the middle of day and thus the backlight on my keyboard was not on. If I'd tried them in a darker environment, the controls might have made sense, but during the day they baffled me. Of course, these tiny keys have room for nothing but an icon, so I'm not sure what the alternative is other than to move this control from the mechanical keyboard to a software setting somewhere (which would be worse).

### Seeing versus Reading the UI 

Despite their sheen of modernity, digital clocks that show numbers ("12:45") are slower to use because they have to be "read." By comparison, the traditional clock face is a graphical depiction of the passage of time and can be "seen" at a glance. Likewise, the best UIs support that same kind of at-a-glance information extraction. Why? Because users can spend less mental effort on the UI and remain more fully engaged with the content, because it'll help to reduce split attention, and because it'll reduce frustration (no one likes having to hunt and find for a control that should be right in front of you when you need it). Sounds groovy, but how do we support that? Here are some suggestions:

1. Make sure your UI bits look different in fundamental ways: If all of your buttons are the same size, shape, and color with only words in the middle of them to distinguish them, the user has to "read" the buttons and can't simply click "the green one" or "the round one". Differences in shape, size, and color are easily seen—use them to group and distinguish functionality. 

The outer shape is most critical: Differences in the shape of an icon are easiest to see if the shapes are placed against contrasting backgrounds—they shouldn't be buried in the middle of non-UI eye candy. The UI bits should be "naked" since our eyes latch on to high-contrast edges of things in order to construct "figure" from "ground" and see something as, well, a thing. If you want to go deeper, look at the ideas of [Gestalt psychology][11] on how the brain "sees" objects. 

So what? Well, one of the most common mistakes I see in UI design is the desire to put all of the controls inside standardized boxes or pill buttons.* If they all look the same at a glance, you have to then slow down and read each one*.

2. Keep It Simple Stupid. You might have 50 Photoshop filters at your disposal, but use them sparingly. Avoid pointless UI eye candy, no matter how hard the marketing department keeps pressuring you to create a UI with "more personality". Things like gel-like 3D faux shiny buttons might make your map feel more complete or polished but from a cognitive-perceptual stand point these embellishments offer no useful information and actually upstage the very UI bits that do "the real work" for the user. In the example below, the "0" is the only thing the user really needs to see...everything else is just expensive space filler. Really. 

![calculator_gel_rectangle_button](cartography2/images/OverviewUI/calculator_gel_rectangle_button.jpg)

3. Group related items in the same space. Controls are often used in tandem, such as panning and zooming, and they should be logically grouped together.

4. Relentlessly eliminate clutter / Make the UI "self-policing": Design the leanest interface you can and go one step further and design one that only shows the controls at that moment that are needed. For example, if you can't print at some point in the workflow, there's no need to put a big print icon on the screen (since it'll suggest that you can indeed print...then you have to build a warning message to tell users "Ha! you can't!" which leaves them frustrated and you with more things to program). The fewer bits and pieces on the screen, the faster the user can find what they need. If a UI looks like someone "vomited text on the screen" you've just not done your homework.

### The Dangers of Building Too Much UI  

As designers we often feel like we should create the most complete, visually rich UI we can, in part because we want to make sure we've covered every single contingency. This feeling can also be driven in part because we're proud of our work and want to show folks what we can do. Don't fall into this trap. For example, not all maps need to have panning and zooming: If the content of the map fits easily on-screen and is fully readable at a single scale, go home early that day. But panning and zooming can't hurt, can it? Actually, it might. 

Here are 4 reasons why you should never build more UI than you need: 

**(1)** the extra time and expense to you to create the controls, 

**(2)** the extra time for users to learn a now more-complicated UI, 

**(3)** the disappointment users feel when they discover panning and zooming got them nothing for their effort (avoid "teasers"in the UI), and 

**(4)** more stuff to break!

*So how much UI is enough UI? *I don't believe there is a magic formula, but the simple answer is "when people can easily do all of the things you promised them they could do." And how do you know if you''ve achieved this? 

User testing.

Of course, people vary a lot in what they need from a map and what they bring to the map (previous experience and level of motivation being the big ones) so this is a moving target. I'm a big fan of the many, many insights from [usability expert Steve Krug][13] in particular his book *[Don't Make Me Think][14]*. One of his key ideas is "aim for the the middle 80%" when designing a UI as it is impossible to make a single map/website/piece of software that will work for everyone all of the time (the top 10% and bottom 10% require different tools). I strongly suggest reading through his book—it is time very well spent.

Just as you can build too much UI, you can also build too little. I generally argue against a completely minimal interface as (as we mentioned above) it's good to be able to do things, such as opening or saving a file, two or three different ways. This might be as subtle as a keyboard shortcut, but after watching hundreds and hundreds of students using software, I'm amazed at how folks develop their own "UI style" for getting things done and you need to build that kind of flexibility into the system to keep a range of users happy. 

**TIP OF THE DAY**: Go watch someone use some software you think you know really well. Chances are you'll find out at least a few tricks you didn't know about.

I encourage you to explore the other articles in this section and would start with **[Interface Evaluation 1: Philosophy][4]** which follows very naturally from this introduction, or go back to the [list of topics][15].

Except where otherwise noted, content on this site available under a [Creative Commons 3.0 License][16].

 [1]: http://web.archive.org/web/20100702154019/http%3A/en.wikipedia.org/wiki/Human-computer_interaction
 [2]: http://web.archive.org/web/20100702154019/http%3A/en.wikipedia.org/wiki/User_interface_design
 [3]: http://web.archive.org/web/20100702154019/http%3A/www.ambysoft.com/essays/userInterfaceDesign.html
 [4]: http://web.archive.org/web/20100702154019/http%3A/cartography2.org/Chapters/page9/InterfaceEvaluation1.html "Interface Evaluation 1: Philosophy"
 [5]: http://web.archive.org/web/20100702154019/http%3A/en.wikipedia.org/wiki/Semiotics
 [6]: http://web.archive.org/web/20100702154019im_/http%3A/cartography2.org/Chapters/page10/files/airport_icons2.jpg
 [7]: http://web.archive.org/web/20100702154019im_/http%3A/cartography2.org/Chapters/page10/files/ag_08e320_pwrseat.jpg
 [8]: http://web.archive.org/web/20100702154019/http%3A/www.jnd.org/
 [9]: http://web.archive.org/web/20100702154019/http%3A/www.amazon.com/Design-Everyday-Things-Donald-Norman/dp/0385267746
 [10]: http://web.archive.org/web/20100702154019im_/http%3A/cartography2.org/Chapters/page10/files/mackeyboard.jpg
 [11]: http://web.archive.org/web/20100702154019/http%3A/en.wikipedia.org/wiki/Gestalt_psychology
 [12]: http://web.archive.org/web/20100702154019im_/http%3A/cartography2.org/Chapters/page10/files/calculator_gel_rectangle_button.jpg
 [13]: http://web.archive.org/web/20100702154019/http%3A/www.sensible.com/
 [14]: http://web.archive.org/web/20100702154019/http%3A/www.sensible.com/buythebook.html
 [15]: http://web.archive.org/web/20100702154019/http%3A/cartography2.org/Chapters/Chapters.html "Chapters"
 [16]: http://web.archive.org/web/20100702154019/http%3A/creativecommons.org/licenses/by-nc-sa/3.0/us/  