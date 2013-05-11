
[Permalink](http://web.archive.org/web/20100702173807/http://cartography2.org/Chapters/page9/InterfaceEvaluation1.html "Permalink to Cartography 2.0 - Overview: Interface Evaluation")

# Cartography 2.0 - Overview: Interface Evaluation

by Robert E. Roth, Department of Geography, Penn State University
date: 02/23/10

Synopsis  
  
This entry oulines my underlying philosophy to user interface design and evaluation: user-centered design. I begin by introducing the user-centered design philosophy and outlining a six-stage design and development workflow based upon this philosophy. I then discuss the evaluation component of user-centered designed, comparing formative evaluation and summative evaluation. I close with a brief discussion on how interface success is measured during interface evaluation, introducing the concepts of usability and utility. Over the course of the entry, I identify six 'interface evaluation recommendations': this list of recommendations is continued in the next entry on classifying interface evaluation methods.
Folks who have inspired much of my thinking on this: [Sven Fuhrman][1], [Mark Harrower][2], [Steve Krug][3], [Jakob Nielson][4], [Donald Norman][5], [Alan MacEachren][6], [Catherine Plaisant][7], [Anthony Robinson][8], [Ben Shneiderman][9]

Keywords: interface evaluation, user-centered design, usability, utility, discount interface evaluation

Give Me User-Centered Design or Give Me Death  


  
In his introduction to the [User Interface and Usability][10], Mark Harrower stressed the importance of designing for the user. Despite the pride and satisfaction we derive from our cartographic applications, we have to remember that the tools we develop serve the needs of others (OK, [sometimes we do make interactive maps just for fun][11]). One of my all-time favorite quotes – which seems appropriate for almost every mapping context – comes from [Denis Wood (1992: 193)][12]: "We don't have problems cartographers can fix, we have *problems.*..and maps can help solve them." The end game isn't the interactive map itself, it's what the users do with it.

The above approach to interface design emphasizing the end user audience is generally referred to as [user-centered design][13]. User-centered design is a software design and development philosophy that relies heavily upon iterative evaluation and revision of the application based upon user feedback. I believe that **user-centered design is the only option to ensure software success**. Evidence supporting this claim come from the fields of [Human-Computer Interaction][14] (HCI), [Information Visualization][15], and even now Cartography and are as numerous as they conclusive. Despite the almost universal recommendation to focus upon the user, user feedback often is solicited only at the end of the development process (when it is too late to make significant improvements), if solicited at all. Reasons for ignoring users include lack of access to the targeted end users, lack of time or money to involve the users, and, unfortunately, a general belief held by interface designers and software developers that they know best and that their users blindly will accept whatever they come up with (cough, Window Vista). All of these issues lead to user frustration and lack of adoption (together leading to the death of the application), prompting my first interface evaluation recommendation:

Interface Evaluation Recommendation #1: Know your audience and test your interactive map with a representative sample of this audience. 

Focusing on the iterative nature of user-centered design, [Anthony Robinson and his colleagues (2005)][16] recommend a six-stage process following the user-centered design philosophy (Figure 1), slightly modified from a version offered by [Slocum et al. (2003)][17]. User-centered design begins by completing a work domain analysis, sometimes referred to as a *task analysis*. At this stage, developers survey the needs of the targeted end users and identify how their current set of tools and usage strategies can be improved and appended, leading to my second recommendation:

Interface Evaluation Recommendation #2: Solicit user feedback early in the project...like, even before you begin interface design.

![figure1_userCentered](cartography2/images/InterfaceEvaluation/figure1_userCentered.jpg)

***Figure 1: ****The User-Centered Design Process. A six-stage UI design workflow that follows the user-centered philosophy. Image derived from **[Robinson et al. (2005: 245)][16]**.*

Following the task analysis, there are four interconnected stages. During [conceptual development][13], designers discuss with end users and identified stakeholders the basic feature set for inclusion in the application and its overall architecture; [this should include a conversation about the type of interactivity that is needed in the application (i.e., the kind of control), the amount of interactivity that is needed (i.e., degree of control), and the way in which the interactivity should be implemented][10]. This discussion is followed by a prototyping stage, where designers create and circulate both paper (hand-drawn or made with a graphics design program) and interactive mock-ups. Prototypes are evaluated through *interaction and usability studies*, first in a very informal manner (perhaps with a group of stakeholders annotating paper mock-ups) and later in a more formal, robust manner (perhaps testing an alpha version of the product using a representative sample of end users). Formal feedback from the evaluation stage leads to the *implementation *of the fully-featured beta version of the application.

I wish to take note of two important aspects of steps #2-5 before completing the description of the Figure 1 workflow. First, it is important to stress that steps #2-5 are iterative. The most thought-through projects may work through these dozens of iterations before releasing the final product. Second, although these four steps are presented linearly, it may not be necessary to work through all four steps with each iteration (as represented by the nested cycles in Figure 1). Following the first evaluation of the prototype, it may become clear that designers need to go back to the drawing board, returning to conceptual development without implementing the interface; this would be a positive finding, as it would save time and effort in the development of an ill-conceived tool. Similarly, it is recommended to evaluate designs at both the prototyping stage and at the implementation stage (thus returning to step #4 after completing step #5). Each round of evaluation should lead to a parallel revision of the interface, whether in the working prototype or the actual implementation. These two important points lead to my third interface evaluation recommendation:

Interface Evaluation Recommendation #3: Solicit user feedback throughout the design process and iteratively revise the interface accordingly.

The final step in the user-centered design is [debugging][13] of the application. The purpose of the debugging is to identify small, somewhat easy to fix usability issues in the software, not to identify major issues in the conceptual design. Don't fall into the trap of only including user input at the debugging stage. Including users only at the tail end of the project is a major concern, for reasons I lay out below.

  
Interface Evaluation  


  
Interface evaluation has many names. The most common label is [usability testing][19], although it will be clear from the discussion on the difference between usability and utility in the following section that this label is limited. A second common label is [user testing][20], although this term has a much broader meaning for scientific researchers. If you are performing a Google Scholar search, you can also try such keywords as [usability engineering][21], [usability inspection][22], [methods for HCI][23], or [human factors research][24]. I use the term [*interface evaluation*][13]** ** in this entry because it does not have the ambiguities or limitations of other terms; the lexical distinction does not correspond to a significant practical distinction, although I acknowledge that this set of terms are not completely synonymous. I define [*interface evaluation*][13]** **as any input for or critical examination of the user interface – whether at the beginning or ending stages of development or in a formal or informal manner – aimed at improving its ease-of-use and usefulness.

Interface evaluation generally falls into one of two categories: formative or summative. [*Formative Evaluation*][13]** ** describes the feedback solicited in the early to intermediate stages of the project that specifies the requirements of the interface. Returning to Figure 1, formative evaluation includes step #1 and the majority of iterations through steps #2-5, guiding initial concept development and prototyping of the software and extending into the evaluation of partially-featured alpha versions of the software. Thus, formative evaluation is the backbone of user-centered design.

On the other hand, [*summative evaluation*][13]** ** is conducted only after the interface is implemented, serving a confirmatory "it works" role for the interface. Summative usability evaluation generally is applied for one of three reasons:

**(1) **to compare multiple in-house interface designs that support the same task in order to determine which to include in the final software release (while this would be ideal for all applications, time and money constraints often make development of parallel designs impractical),

**(2)** to compare a new version of an existing product to the older version to ensure that the new version is an improvement, and

**(3)** to compare the final software release to competitor software that supports similar tasks in order to convince potential users to buy your product.

When coupled with an extensive program of formative evaluation, summative evaluation methods can be a useful component of the development cycle, serving as the final quality check before release. Unfortunately, summative evaluation is all too often used as a last-second bandage, a last ditch effort ordered by the boss to save a sinking ship. Sole reliance upon summative evaluation is the equivalent of placing all your chips on black: you'll either find out that your designs work (allowing you to high-five your buddies and hit the pool) or you'll find that your designs do not work at a point in the development process when it is too late or too costly to remedy the situation (leaving you belly-up). If you gamble enough times, eventually the house will win. This leads me to my fourth recommendation:

Interface Evaluation Recommendation #4: While it is important to complete both formative and summative interface evaluation, place your focus upon formative interface evaluation.

There is only one caveat to an active emphasis on user-centered, formative interface evaluation: it can be costly, in terms of time, money, and user participation. Many of the methods used for interface evaluation have their origins in [positivist scientific inquiry][25]. Here, each experiment is carefully prepared, varying each treatment slightly, controlling for any confounding variables, and requiring hundreds or even thousands of participants to provide the power necessary to detect small differences in the recorded signal. Qualitative methods (e.g., [interviews][26], [focus groups][27], [participant observation][28]) also require generation of detailed protocols and coding structures in order to be scientifically robust.

However, it is important to remember that goal of interface evaluation is quite different than that of science. Scientists wish to generate universally-applicable theories that inform the design and implementation of all interfaces, while interface designers and developers simply want to make sure that their current project works. Because of the difference in goals, designers can ascertain formative feedback from users quickly by employing *discount *interface evaluation, or the informal administration of an interface evaluation method using as few as 3-6 participants ([Shneiderman and Plaisant 2010][29]). The results of discount testing are not statistically analyzed for significance, but instead simply are used as a way to get general reactions to and opinions about the project, ensuring that the software is meeting user needs and expectations and identifying major [*head-slappers*][13]** ** (obvious usability issues missed by the developers because of their familiarity with the software) early on in development ([Krug 2000][30]). The discount interface evaluation approach allows for numerous rounds of feedback during design and development, leading us to my fifth interface evaluation recommendation:

Interface Evaluation Recommendation #5: When time, money, and participants are limited, evaluate your product multiple times with only a handful of participants rather than evaluating your product only once or twice with the entire set of participants.

Budgeting for multiple rounds of discount interface evaluation saves both time and money in the long run. 

Measuring Interface Success: Usability versus Utility  


  
Before I introduce numerous evaluation methods that have been developed for examining software, it is important to first discuss how software success is determined. Software success is often defined in terms of usability and utility. [*Usability*][13]** **refers to the ease-of-use of the software. The [Usability.gov][31] site – an excellent web resource for learning about interface design and evaluation – identifies five components of usability that are related to the user's experience with the software:

**(1) ease of learning** (i.e., [*learnability*][13]* *): how quickly a user picks up the interface without prior use

**(2) efficiency of use**: how quickly a user can interact with the interface once learned to complete the desired tasks

**(3) memorability**: how well a user can return to an interface and pick up where he or she left off

**(4) error frequency and error severity**: how often users make mistakes and how fatal these mistakes are

**(5) subjective satisfaction**: how well the interface is liked

Usability-based evaluation examines each of these five components in order to provide developers with recommendations on how to optimize them.

[![figure2_usabilityGov][33]](cartography2/images/InterfaceEvaluation/figure2_usabilityGov][33].jpg)  


***Figure 2: ****[Usability.gov][31]**. If you are interested in learning more about usability engineering, I recommend checking out this site.*

In contrast,* *[*utility*][13]** **refers to the usefulness of the software. Utility-based interface evaluation examines if the software is appropriately and completely serving the needs of the user. Further still, utility describes not just the (mis)match between user needs and system provisions, but also the quality of products derived by the user while using the system. Usage products include completion of a step in a workflow, creation of an output file for storage, or, in the context of scientific research, generation of new hypotheses and insights.

In practice, usability and utility typically do not play nice. In order to make an application more usable, it is our first instinct to purge the interface, removing overly complex and confusing features and simplifying those features that must remain in the application. However, to make an application more useful, our first instinct is to add new features (giving the user a larger toolkit with which to work) and to increase the number of input parameters for existing features (giving the user added flexibility to apply the tool as he or she pleases). These competing forces lead the interface designer to ask the proverbial question of [which comes first][33]: the chicken or the egg?

To help answer this question, let's take a look at an example comparing two interfaces designed for multimedia entertainment. The iPod shuffle (Figure 3) is the archetype of simplicity and an applauded success story in interface design. Thinking about the recommendations of [Usability.gov][31], the iPod shuffle is easy to learn how to use, provides an efficient interface for playing audio, is easy to remember how to use over time, generates only a small amount of non-fatal usability errors, and is incredibly well-liked (as demonstrated by the millions sold).

[![figure3_ipod][35]](cartography2/images/InterfaceEvaluation/figure3_ipod][35].jpg)

***Figure 3: ****The latest generation of **[iPod shuffle][35]**.*  


  
On the other hand, the 'RothPod shuffle' (a.k.a., my living room entertainment center – Figure 4) is the archetype of complexity and operates upon an absurd web of crossed wires (and crossed fingers). The 'RothPod shuffle' exhibits a steep learning curve that never really flattens, requires the usage of a half dozen remote controls, makes return users look like Guy Pearce in *Memento*, elicits many more erroneous entries than correct ones, and has been rejected as unusable by a great number of roommates and girlfriends. Thus, the iPod shuffle appears to be a much more successful interface, at least from a usability standpoint.

![figure4_rothpod](cartography2/images/InterfaceEvaluation/figure4_rothpod.jpg)  


***Figure 4: ****My living room entertainment center, otherwise known as the 'RothPod shuffle' (not pictured: slob on couch).*

Despite being ostensibly less usable, I would not say that the 'RothPod Shuffle' is a failure. There is an important difference between the iPod shuffle and the 'RothPod' counterpart: the user needs that they support. Apple realized that there was a subset of users that did not need a majority of the features implemented in the original iPod, which itself was already a subset of multimedia functionality that could have been included. Because the needs that the iPod shuffle serve are straightforward and generalizeable across multiple users, interface utility can be optimized through a [*transparently usable*][13]** *** *interface (i.e., an interface that is immediately usable without any training). The 'RothPod shuffle' exemplifies the exact opposite scenario: the amalgamation of equipment serves a complex (for instance, watching Family Guy on Hulu.com while playing Quarterback Club '99 on Nintendo 64 and blasting Journey on the stereo...hey, we've all been there) and specialized (well...maybe we haven't all been there) set of user needs. The flexibility and interoperability built into the 'RothPod' user interface allows me to fulfill my complex and specialized needs, no matter how ridiculous. 

Now, could my 'RothPod shuffle' example be more usable? Absolutely, but it is unlikely that it will ever achieve the transparent usability exhibited by the iPod shuffle. Therefore, **usability is relative to utility**. This leads me to my sixth recommendation:

Interface Evaluation Recommendation #6: While usability and utility are both essential for software success, utility comes first.

In summary, first ensure that the application is meeting user needs and then make revisions to improve its usability.

* * *

Glossary of Terms**  
**  
*conceptual development* - formalization of the basic architecture and feature set for inclusion in the application

*debugging* - the identification of small, somewhat easy to fix usability issues in the software at the final stages of development

*discount interface evaluation* - the informal administration of an interface evaluation method using as few as 3-6 participants

*efficiency of use* - how quickly a user can interact with the interface once learned to complete the desired tasks 

*error frequency* - how often users make mistakes

*error severity* - how fatal the mistakes made by the user is to the session

*formative evaluation* - feedback solicited in the early to intermediate stages of the project that specifies the requirements of the interface

*head-slappers *- obvious usability issues missed by the developers because of their familiarity with the software

*interface evaluation* - any input for or critical examination of the user interface – whether at the beginning or ending stages of development or in a formal or informal manner – aimed at improving its ease-of-use and usefulness

*learnability* - how quickly a user picks up the interface without prior use

*memorability* - how well a user can return to an interface and pick up where he or she left off

*prototyping *- development of a series of mock-ups of various quality (e.g., hand drawn, made with a graphics program, early implementations with limited interactivity) early in the design process so that interface designs can be evaluated and revised before it is prohibitively costly to do so

*subjective satisfaction* - how well the interface is liked

*summative evaluation* - interface evaluation conducted after the interface is implemented in order to determine if the interface works and how it can be improved in the final revision prior to deployment

*task analysis* - an examination of the targeted end users' needs, often completed early in the design process

*transparent usability* - an interface that is immediately usable without any training  
usability - the ease-of-use of the software

*user-centered design* - a software design and development philosophy that relies heavily upon iterative evaluation and revision of the application based upon user feedback

*utility* - the usefulness of the software

* * *

Except where otherwise noted, content on this site available under a [Creative Commons 3.0 License][37].

 [1]: http://web.archive.org/web/20100702173807/http%3A/geoweb.evans.txstate.edu/directory/faculty/fuhrmann/fuhrmann.html
 [2]: http://web.archive.org/web/20100702173807/http%3A/www.geography.wisc.edu/%7Eharrower/
 [3]: http://web.archive.org/web/20100702173807/http%3A/www.sensible.com/
 [4]: http://web.archive.org/web/20100702173807/http%3A/www.useit.com/
 [5]: http://web.archive.org/web/20100702173807/http%3A/www.jnd.org/
 [6]: http://web.archive.org/web/20100702173807/http%3A/www.geovista.psu.edu/members/maceachren/
 [7]: http://web.archive.org/web/20100702173807/http%3A/www.cs.umd.edu/hcil/members/cplaisant/
 [8]: http://web.archive.org/web/20100702173807/http%3A/www.personal.psu.edu/acr181/
 [9]: http://web.archive.org/web/20100702173807/http%3A/www.cs.umd.edu/%7Eben/
 [10]: http://web.archive.org/web/20100702173807/http%3A/cartography2.org/Chapters/page10/OverviewUI.html "Overview: The User Interface"
 [11]: http://web.archive.org/web/20100702173807/http%3A/www.cartogrammar.com/blog/the-music-of-geography-ohio-is-a-piano/
 [12]: http://web.archive.org/web/20100702173807/http%3A/www.amazon.com/Power-Maps-Denis-Wood/dp/0898624932
 [13]: http://web.archive.org/web/20100702173807/http%3A/cartography2.org/Chapters/page9/InterfaceEvaluation1.html#1
 [14]: http://web.archive.org/web/20100702173807/http%3A/en.wikipedia.org/wiki/HCI
 [15]: http://web.archive.org/web/20100702173807/http%3A/en.wikipedia.org/wiki/Information_visualization
 [16]: http://web.archive.org/web/20100702173807/http%3A/www.geovista.psu.edu/publications/NCI/Robinson_Auto_Carto_CAGIS_inpress_05.pdf
 [17]: http://web.archive.org/web/20100702173807/http%3A/www.ingentaconnect.com/content/acsm/cagis/2003/00000030/00000004/art00001
 [18]: http://web.archive.org/web/20100702173807im_/http%3A/cartography2.org/Chapters/page9/files/figure1_usercentered.jpg
 [19]: /web/20100702173807/http://scholar.google.com/scholar?hl=en&amp;q=usability%2Btesting&amp;btnG=Search
 [20]: /web/20100702173807/http://scholar.google.com/scholar?hl=en&amp;q=user%2Btesting&amp;btnG=Search
 [21]: /web/20100702173807/http://scholar.google.com/scholar?hl=en&amp;q=usability%2Bengineering&amp;btnG=Search
 [22]: /web/20100702173807/http://scholar.google.com/scholar?hl=en&amp;q=usability%2Binspection&amp;btnG=Search
 [23]: /web/20100702173807/http://scholar.google.com/scholar?hl=en&amp;q=methods%2Bin%2BHCI&amp;btnG=Search
 [24]: /web/20100702173807/http://scholar.google.com/scholar?hl=en&amp;q=human%2Bfactors%2Bresearch&amp;btnG=Search
 [25]: http://web.archive.org/web/20100702173807/http%3A/en.wikipedia.org/wiki/Positivism
 [26]: http://web.archive.org/web/20100702173807/http%3A/en.wikipedia.org/wiki/Semi-structured_interview
 [27]: http://web.archive.org/web/20100702173807/http%3A/en.wikipedia.org/wiki/Focus_groups
 [28]: http://web.archive.org/web/20100702173807/http%3A/en.wikipedia.org/wiki/Participant_observation
 [29]: /web/20100702173807/http://www.amazon.com/Designing-User-Interface-Human-Computer-Interaction/dp/0321537351/ref=sr_1_1?ie=UTF8&amp;s=books&amp;qid=1252010702&amp;sr=1-1
 [30]: /web/20100702173807/http://www.amazon.com/s/ref=nb_ss?url=search-alias%3Dstripbooks&amp;field-keywords=don%27t%2Bmake%2Bme%2Bthink&amp;x=0&amp;y=0
 [31]: http://web.archive.org/web/20100702173807/http%3A/www.usability.gov/
 []: http://web.archive.org/web/20100702173807/http%3A/www.usability.gov/
 [33]: /web/20100702173807/http://portal.acm.org/citation.cfm?id=1081432.1081556
 []: http://web.archive.org/web/20100702173807/http%3A/www.apple.com/ipodshuffle/gallery/#image
 [35]: http://web.archive.org/web/20100702173807/http%3A/www.apple.com/ipodshuffle/gallery/#image
 [36]: http://web.archive.org/web/20100702173807im_/http%3A/cartography2.org/Chapters/page9/files/figure4_rothpod.jpg
 [37]: http://web.archive.org/web/20100702173807/http%3A/creativecommons.org/licenses/by-nc-sa/3.0/us/  