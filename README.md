# Application for Technology Development Fund
# Sproti Project Description
## Autumn 2016

### Company name: HiDef Textiles

### Project title: HiDef Knits

![](figures/HiDefKnitsLogo.png)

Instructions
------------

Please following items in the preparation of project descriptions. The applicant
must answer all the items below, otherwise the application dismissed. That reads
"TODO" you can write text, insert images or tabletting. The application can not
be longer than 20 pages, excluding the cover, summary, table of contents and
bibliography. It is forbidden to change the width margin nor have the font size
smaller than 11-point Calibri (Body) or equivalent. If application is made for
other than MS Word format example PDF, the applicant must pay close attention to
page number before submitting the application. Those who do not have access to
MS Word are advised to use OneDrive. Additional information and rules can be
found on the website Rannís. The application deadline is at. 16.00 per
application deadline is entirely equation 15 February and 15 September except
where these days carry a weekend or public holiday. The application deadline
moves to the next ordinary working day.


Summary
=======

###### Summary of a maximum 1 page.

TODO

HiDef Knits is an intuitive easy-to-use design tool for handmade knitwear, that
even the not so computer savvy grandmother would be able to use. The user could
also have limited or no experience in knitting and use HiDef Knits to design a 
garment that they could outsource the knitting to.

The objective of HiDef Knits is create a tool that enables hobby knitters to 
publish their designs for others to make. 
Thereby, the output of HiDef Knits could be a valuable income source for those 
users who to choose to sell their patterns to others.

Knitted related apps currently on the market aren't sophisticated enough to 
generate even the simplest garment. They're mostly useful for keeping track 
of where you are in a written pattern. 
There are a few desktop software solutions available that create illustrative 
pattern schematics, but they have with a steep learning curve, and are 
generally too expensive for self-publishing designers or hobby knitters. 
Moreover, they are designed with sewing designers in mind, so there is 
minimal support for generating meaningful patterns for handknits. 
However, there is an abuntant selection of software for creating knitting
charts that can be translated to written directions. 
The HiDef Knits software is to encorporate all of these ideas, for a 
holistic solution that could help aspiring or experienced designers to create
bespoke knitting patterns. 
Moreover, HiDef Knits unique feature will be 3D rendering of the designed 
knitwear garment with draping that matches the proposed yarn. 

Even though parts of the solution have already been created as standalone 
programs, unfortunately, they are incompatible with one another. 
Furthermore, many of those businesses are currently out of business, 
or are not in active software development to speak of. 
HiDef Knits will be developed as a free and open-source software (FOSS).
This means that everyone is free to use, copy, and change the software
in any way. It also means that the source code is openly available so others can
contribute to and audit it.


1 Description of the project
============================

1.1. Objectives
---------------

###### Lýsið verkefninu og markmiðum þess. Hverjar eru áætlaðar niðurstöður/afurðir verkefnisins, hvers eðlis eru afurðirnar (t.d. tæki, búnaður, hugbúnaður, þjónusta).

###### Describe the project and its objectives. What are the estimated results / products project nature are the products (such as tools, equipment, software, service).
	
There has always a strong tradition of knitting for centuries, with earliest
knitted artifacts dating as far back as 11th century. 
Knitting is largely feminine utilitarian art form that unites women across 
cultures and continents. 
Many countries have a rich heritage of knitting. Iceland is known worldwide for 
both our unique wool,
such as lopi, and the traditional Icelandic *lopapeysa*, which is a unique
variation of fair-isle knitting of a blouson with a circular yoke. The renowned
lopapeysa, is relatively new, as it first documentation is from the 60s. But as
years go by, the design of the traditional woolen sweater has changed in line
with fashion trends. There are an endless variations of patterns in terms of
silhouettes and texture. For instance, in the case of the lopapeysa, they are
now often buttoned-up, opened up with a zipper, hooded, with inset pockets, and
the list goes on. But all of them share the same underlying baseline structure.

Knitting can be very rewarding, as it’s generally a labor of love. Studies have
shown that knitting has many health benefits[[1]](#_ftn1) as its practice can 
be a form of meditation. 
Knitting used to be considered passé and only in the domain of 
grandmothers, but in recent years there has been a massive resurgence. 
Knitting (and crocheting) have turned into hipster pastimes for men and women 
of varying ages.
The revival is partly due to celebrity fans like Kate Moss and Amanda Seyfried 
taking up knitting, 
but a larger impact to the knitting revival is thanks to the internet age. 
Online tutorials help wannabe knitters to become self-learned novices and later 
experts. 
There is also a large international community on the social networking site
[Ravelry](http://www.raverly.com) that has over 6.45 million registered users.
Ravelry connects knitting and crochets enthusiasts and professionals. It is both
a social platform where users can share and discuss their knitwork, but also a
venue for distributing knitting patterns, both for free and for sale, within the
site. There are also a very lively groups on facebook, such as *Handóðir
prjónarar* with over 17 thousand (mostly) Icelandic members.

Knitters take great pride in their work and most practitioners know of all the
untold hours of knitting disasters and unwanted frogging[[2]](#_ftn2), 
where a knitter unravels hours upon hours of meticulous work. This may be due 
to an error inreading the pattern or an unflattering fit. 
Since one size does not fit all, the objective of HiDef Knits is to simplify 
the process of designing original and altering knitwear with perfect fit and a 
professional finish.

A user starts by feeding into the HiDef Knits software all necessary body
measurements needed (cf. Figure 1) for constructing a garment. The first version
of HiDef Knits will solely focus on sweaters, cardigans, dresses and skirts
since they share similar building blocks. For these types of garments there 
are a total of 17 body measurements that need to be considered for an individual
fit, namely: shoulder width, chest/bust circumference, armhole depth, raglan
depth, waist circumference, hip circumference, length from hip to waist, front
and back neck length, body length at front and back, length from armhole to
lower edge, sleeve length, upper arm width, wrist width, length from center back
to wrist.

![](figures/measurements.png)

**Figure 1 Measurements**

Based on these body measurements it’s important to incorporate ease (i.e. extra
width) in the pattern design in order for the wearer to move comfortably in a
garment. For instance, 5cm ease for body circumference is sufficient, but 10cm
is preferred when designing outerwear. The HiDef Knits software will make the
necessary ease additions that are appropriate to each pattern shape based on the
user’s choice of style, namely: standard, roomy, tight, form fitting (i.e.
negative ease) or user defined.

From here the software offers constructional elements for the user to play
around with. Figure 2 depicts several classic torso silhouettes (i.e. front and
back pieces) and Figure 3 demonstrates classic sleeve silhouettes that a user
could define in the HiDef Knit software. The user starts by defining the shape
of the garment, and building on classical silhouettes those would be: tapered,
kimono or blouson. Next the user decides on length (cropped, waist, hip or knee
length). This is followed by armhole shaping, the most common silhouettes being
dropped shoulder (cf. left most variation in Figures 2 and 3), set-in shoulder,
raglan, circular yoke (e.g. lopapeysa) or saddle shoulder. The choice of armhole
shaping effects the design of the sleeve piece, and the HiDef Knits software
make sure that the front, back and shoulder pieces all correspond to one another
for perfect joining. This is extremely important for achieving a comfortable
fit. Other design elements for the sleeve piece have to deal with the look
towards the cuff, as they could be a lantern sleeve or straight sleeve with or
without any tapering. If there are cuffs (classic fold-back, bell cuff or
placket cuff) on the sleeve that design element is incorporated into the sleeve
piece for one seamless piece.

![](figures/silhouettes-torso.png)

**Figure 2 Classic torso silhouettes**

![](figures/silhouettes-sleeve.png)

**Figure 3 Classic sleeve silhouettes**

Going back to the torso (i.e. front and back pieces) there are other structural
elements to consider, such as necklines (the classic boatneck, square, round or
“V” shaped) which also effects the choice of collar (straight, split,
turtleneck, cowl, shawl). And then there is also the question of whether the
garment is tapered or not, and a choice of edging. Similar to the sleeves if the
design is lantern or straight, etc.

Moreover, if the garment is open, i.e. a cardigan, then there are several
possibilities. Center closure with zipper, overlapping or independent front band
or perhaps rounded front edges. This also adds the choice of lapels (classic or
notched) and buttonholes (if necessary).

As the user is designing a garment there is a 3D rendering of the approximate
look of the garment. So there is an interactive feature how the choice of
constructional elements effects the overall look and feel of the design.

From here the user defines the texture and color arrangement of the garment.
With the prototype starting with the most commonly used stockinette stitch,
garter stitch and ribbing, with lace and cable knit support coming later. The
user can combine available stitch patterns for practical and aesthetic purposes.
If the user chooses stockinette stitch, there will be fair-isle[[4]](#_ftn4) 
support.

As garment fit is important, the knitting gauge needs to be correctly estimated
before making any translations from measurements to numbers of stitches and
rows. This is where the choice of yarn comes to play and the individuals
knitting tension.

With all of these structural components, HiDef Knits software produces a chart
that any knitter can follow, with the correct number stitches for cast-on and
where to make decreases and increases along with appropriate bind-off
techniques. The software will also take into consideration the knitters personal
preference, whether the output should be a multiple piece construction (which is
the most common version) or as a one-piece construction (the “preferred”
approach in Iceland), where the latter does not include selvage stitches as
there are no joins needed to connect the front and back pieces together.

1.2. State of the art
---------------------

###### Gerið grein fyrir stöðu þekkingar (e. state of the art) innanlands og erlendis á þeim sviðum sem verkefnið nær til og hvernig verkefnið getur bætt við núverandi þekkingu á viðkomandi sviði.

###### Please describe the state of knowledge (e. State of the art) domestically and abroad in the areas for the project and how the project can add existing knowledge in the relevant field.

TODO


1.3. Project status
-------------------

###### Gerið grein fyrir þeirri vinnu sem hefur átt sér stað áður en ákveðið var að hefja verkefnið. Hefur tæknileg eða markaðsleg forkönnun verið gerð? Hefur frelsi til athafna verið kannað með leit í einkaleyfisgagnagrunnum?

###### Give an account of the work that has taken place before the decision to start the project. Have a technical or market pilot study been conducted? have freedom of action have been investigated in search of patent databases?

After consulting 200 Icelandic knitters, 82% had designed a garment for
themselves and 10% had published their patterns (remaining 18% did not consider
themselves a designer). The majority built their work on existing patterns in
terms of calculating the number of stitches needed. Some created their garments
on the fly, and as a result of their undocumented approach their designs were
not repeatable. Generally, the designers jolted calculations with pen and graph paper,
but in an erratic way such that they didn’t feel comfortable in publishing their
work with others. Those who published their work mostly used Excel to manage
their calculations and grading of sizes.

From personal observations, when knitters share their original designs on social
media, the comment threads are bombarded with questions about pattern
availability. For hobbyist knitters, the excitement of starting a new project
often supersedes detailed preplanning, and there may be last minute alterations
since what you initially planned might not work out due to forgotten decreases
or increases that result in a poorly fitted garment. Therefore, since it’s not
known beforehand if a project will be loved by so many, it’s can be extremely
hard to retrace your steps to publish a pattern in a coherent way for others to
follow, let alone using the appropriate terminology and abbreviations. The HiDef
Knits software objective is to help those aspiring designers (both for personal
use and pattern distributions) for easier preplanning that result in an overall
improved knitting experience as there is minimal painstaking assembly process
due to forgotten structural elements.

According to the Foundation for a Free Information Infrastructure, 
software patents should not exist under European law.[[3]](#_ftn3)
Moreover, all of HiDef Knits features are based on known processes, 
and will be developed as a free and open-source software, 
therefore there is no grounds for a patent.


2 Novelty
=========

2.1. Market situation
---------------------

###### Gerið grein fyrir væntanlegum markaðsgeira og stöðu markaðar. Gerið grein fyrir þörf á markaði (innanlands og/eða erlendis) og á hvaða hátt afurðin svarar henni. Lýsið samkeppnisaðilum og á hvaða hátt afurðin er frábrugðin afurðum annarra samkeppnisaðila.

###### Please describe the potential market segment and market position. Please describe the the need of the market (domestic and / or foreign) and the manner in which the product answers it. Describe the competitors and the way the product is different from the products other competitors.

As mentioned before in section 1.3, of the over 200 Icelandic knitters polled, the
majority of knitwear designers use pen and graph paper to create their designs. 

There are several software solutions that aid with fair-isle design, 
that is to say creating multi-color imagery in knitwear.
[Knit Visualizer by Knit Foundry](http://knitfoundry.com/software.html) is a
knitting software that has not been updated since December, 2008. It is
essentially a chart wizard that translates chart symbols to knitting
abbreviations. They have a free demo version for users to interact with the
software, however, the interface is not intuitive for knitting novices and there
are no libraries included unless you buy the full version, at a flat-fee of
$185 (which is considered too excessively priced by most Ravelry users). The
output of the software is user-defined charts, and can be based on 40 common
stitches and 75 different cable stitches. 
A drawback that is frequently discussed in Ravelry forums is the written pattern 
generated would always need editing to group repeats, etc. Nevertheless, a nice
program to get illustrated charts for knitting. Similar to Knit Visualizer is 
[Knitting Chart Editor](http://www.stitchmastery.com/), 
a by StitchMastery. Priced at £60, the full version includes hundreds of 
predefined stitches including 150+ cables, Estonian stitches, brioche, 
beading and twined stitches. 
They offer a stitch font library (bought seperately).
Not only does StitchMastery include more types of predefined stithes, moreover, 
the drawbacks from Knit Visualizer are confronted by Stitchmastery, 
as the software has the ability to detect repeated stitches and automatically
annotate them.
Last version, was released 2014, with no new software development announced.
Reviews on Ravelry and experiend knitters blogs[[7]](#_ftn7) warn prespective 
users that there is a steep learning curve to use the program, 
and a manual that is often not sufficient. However, pattern instructions 
with for repeats are easily created and charts are nicely formatted. 	
Another competitor is [EnvisioKnit](http://www.envisioknit.com/) by 
Jane of EnvisioKnit Design Studio, priced at $99. 
Unlike StitchMastery, the manual is easy to navigate and learn the basic 
commands with many commands are intuitive.[[8]](#_ftn8) 
Otherwise, very similar capabilities to that of StitchMastery.
Yet another chart visualizing software is [KnitBird](http://knitbird.com/), 
priced at €59. However, they offer purely a chart without any automated 
written instructions. On the other, there main feature not offered by the others
is an image importer where you can adjust the level of pixelation/detail.

Furthermore, users download the Knit Visualizer, StitchMastery, and KnitBird 
software on their computer so there can be some technical difficulties to
install the program for users depending on their hardware. Especially the 
software that haven't released an update in the past few years.
HiDef Knits would be a web-based application, only requiring an updated browser.
Note none of these programs offer a 3D rendering of textures based on your 
created stitch chart. 

Unfortunately, none of these aformentioned software applications take 
the design process further, in particular in terms of pattern grading 
(i.e. sizing), which is the main selling point of HiDef Knits. 
However, there is a web-based application called 
[Prjónamunstur.is](http://prjonamunstur.is/) that is a good tool for 
designing an Icelandic lopapeysa with your own fair-isle pattern. 
There is even a 3D rendering of the pattern, and with a downloadable
PDF instruction of your design available in several lanuages. 
Although this is similar to what HiDef Knits will provide. 
Prjónamynstur’s drawback is that it only produces fair-isle blousons that 
have a circular yoke and only based on 3 body measurements
(shoulder circumference, sleeve length, and length from armhole to lower edge).
However, HiDef Knits will be designed with more flexibility, and choice of
constructional components. Therefore, an Icelandic lopapeysa would only be one
possible configuration of many for possible garment design within HiDef Knits.
Moreover, Prjónamunstur hasn’t been updated since March, 2015 and requires
Microsoft SilverLight to run, e.g. making it obsolete for latest versions of
Chrome.

Commercial fashion industry use computer aided design (CAD) software. At the
forefront is Kaledo (previously known as PrimaVision) by Lectra, with customers
such as Louis Vuitton, Hermès and H&M. Another, CAD based fashion software is
SmartDesigner by ASP Creation. Both of these solutions are not meant to deal
with knits especially. They are for general fashion design, but offer a knitting
module for viewing. Since these solutions are marketed for commercial industry,
they are well beyond the price range of self-employed knitwear designers.
Furthermore, based on the documentation the knit modules are focused on
relatively simple cable knits and fair-isle knitwear as they are meant for
mass-production, hence detailed nuances of hand knitting with a professional
finish are not addressed as they are not efficient for such manufacturing. The
CAD fashion software is essentially designing knit textiles to be made with
industrial knitting machines, that are then **cut** and assembled just as is
done with normal woven fabrics. However, when dealing with handknits, each piece
is knit from one continuous yarn, and only cut at the very end. Thus its shaping
is determined by the choice of decreases and increases, and the choice of bind
off techniques that are all detailed in the knitting pattern.

[Garment Designer](http://www.cochenille.com/garment-designer/) by 
Cochenille Design Studio is a relatively affordable software solution for 
garment design, priced at $199. However, current version was released in 2005
and ridden in errors, despite being sold as compatible with Windows 10. 
Plugins are available (for Win XP to 8.1) at extra cost, around $25 a pop.
The garment design is limited to a drop-down pane of prefined shapes and sizes.
It's possible to adjust some measurements, but the overall shape is predefined 
with limit options in terms of flexibility of design. 
Moreover, if contradictory design elements are chosen together, 
or input variables are invalid, the software's error handling is not intuitive 
of what is wrong or the the program freezes. Therefore, this progrom is not
appropriate for unexperienced designers as the learning curve is quite steep. 
Furthermore, Garment Designer is marketed for general pattern design to help 
with grading. There is only  a basic knitting module, with limited options of  
createing unique stitch texture or fair-isle charts. The output is also hard 
to convert to standard knitting instructions (they don't give up repeats etc.)
Therefore, Garment Designer would need to be done in conjuction with a more 
sophisticated knitting chart editor/visualizer as previously discussed.
Since these programs are not designed to be compatible with one another, 
this requires a lot of manual conversions that consequently hinders the flow 
of the design process.

To summarise, most knitting software out there are chart illustrators, where
some can even recognize pattern repeats that preferred when publishing written
directions. 
Prjónamunstur offers additional grading, but only for lopapeysa styled garment. 
Garment Designer has more variety in terms of tailoring, but the learning curve 
is steep and software developement is no longer active. 
Same applies for professional CAD fashion software, but they are priced too 
highly for the target audience of HiDef Knits. 
Morover, Garment Designer's knitting module is very rudimentary as developement
efforts were for pattern design for sewing. 


2.2. Challenges
---------------

###### Lýsið tæknilegum og hönnunarlegum áskorunum sem eru fólgnar í þróun afurðarinnar.

###### Describe technical and design challenges bearings, which involve the development product.
	
TODO
	
1.	Creating a software architecture that is scaleble to be flexible enough
	to create custom stithces, and how to effectively mix and match stitches
	such that the pattern repeats harmonize. 

2.  Given the number of knitting visualising software out there, and most 
	forum posts on Ravelry discussing the pros and cons of those programs, 
	the main complaint is poor user experience. The design isn't intutive 
	enough and the learning curve is too steep. As a result, many aspiring
	designers are deterred of making the effort of streamlining the design 
	process and continue to use graph paper and manual calculations of stitches. 
	
3.  Realizing 3D draping of a knitted garment on a 3D model, allowing the user
    to preview the garment without having to create an actual sample and having
    a model wear it. The draping will be based on shape and type of yarn chosen
	as yarn weight can have unexpected effect of the draping which is hard for
	designers to anticipate. 

4.  Software sustainability, the target audience is not computer savvy 
	and the usage needs to be simple to implement. 
	Therefore hardware requirements or third party support 
	needs to be minimal or easy to install.
		

2.3. Derived opportunity (Spin-off)
-----------------------------------

###### Lýsið mögulegum afleiddum tækifærum sem geta orðið til, t.d. vegna nýrrar þekkingar í verkefninu og/eða vegna notkunar afurðarinnar.

###### Describe the potential secondary opportunities that can lead to, for example, for new knowledge of the project and / or the use of the product.

Future work for HiDef Knits is support for designing socks, hats, skirts, pants, 
shawls, and other accessories.	
A natural extension would be to add support for other types of textiles, 
especially crochet (that is not currently addressed in the market).
Moreover, it should be relatively straight forward to translate
the software for woven textiles, where the shaping would be done via burst
seams or gathers. 
Note, that since the project is developed as FOSS, outside parties would be
able to build upon the HiDef Knit framework, not necessarily for textiles 
production. For instance, gaming developers could strip down the knitting 
intricacies away from the program and just use the 3D modelling of garments 
as a standalone program for more varied avatars. 

Direct usage of HiDef Knits software would renders a knitting pattern based
on the users design. 
The designer is free to publish the pattern for others to use, either free of 
charge or commercially. 
HiDef Knits will not put impose any non-commercial license, however, most 
likely there will be an attribution clause to help with marketing 
of the HiDef Knits solution, similar to Creative Commons license
[Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) 
(CC BY 4.0).

TODO

**The designer can either publish the pattern for others to use or knit
themselves.**

**order for them to work yourself or knitted garment.**


2.4. Intellectual property policy
---------------------------------

###### Lýsið áætlun fyrirtækisins um hvernig farið verður með mögulegar óefnislegar eignir (einkaleyfi, vörumerkjavernd, hönnunarvernd) sem fást úr verkefninu.

###### Describe your business plan on how to be a possible intangible property (patent, trademark protection, design) obtained from the project.

A principal of the designers of HiDef Knits create free and open source software
(FOSS). This means that everyone is free to use, copy, and change the software
in any way. It also means that the source code is openly available so others can
contribute to and audit it.

Given the nature of how many of past knitwear software solutions have either 
discontinued development or are rarely updated, and are therefore become 
obsolete in terms of hardware and software requirements.
We believe that creating a solution that is FOSS will benefit future users.
Therefore even if we decide to not support the solution any longer by cutting
updates or no longer releasing patches, the knowledge gained by the project will
not be lost and could be picked up by other knit-programmers-enthusiasts in 
future.

Moreover, open source software is typically much less resource-intensive than
their proprietary counterpart, meaning that you can run it well even on older
hardware.

Along similar lines, users can take a piece of the open source software and
tweak it to suit their needs. Since the code is open, it's simply a matter of
modifying it to add the functionality you want. This is not applicable to
proprietary software.

The software will be developed open to the public from GitHub at
<https://github.com/HiDefTextiles/HiDefKnits>.


3 Organization and Management
=============================

3.1. Management
---------------

###### Gerið grein fyrir því hvernig verkefninu er stýrt, hverjir stýra því og ábyrgð hvers þátttakanda. Tilgreinið verkefnisstjóra, hverjir sitja í stjórn verkefnisins og verkaskiptingu hennar.

###### Give an account of how the project is managed, who control and responsibility each participant. Specify the project manager, who is in control project and its division of labor.

**Dr. Helga Ingimundardóttir**, is the project manager for HiDef Knits. Helga
holds a PhD in Computational Engineering from the University of Iceland, and has
BSc. degree in Mathematics. Helga was software developer at Valka ehf. from
2012-2015, where she was lead developer on software for a X-Ray guided cutting
machine that automatically removes pin bones and cuts fish fillet to the desired
portions. The system analyzes individual fish fillet for highly uniform portions
based on size, weight or value. Since 2015, Helga has work for AGR Dynamics as a
SQL specialist for implementation and customization on AGR’s inventory
optimization software.

Helga is a fourth generation textile designer. Her grandparents owned and
operated the knitwear manufacturing company ICESHEEP from 70s through 00s. Helga
is familiar with the design process for knitwear through ICESHEEP. Helga has
also been known from designing and visualizing her own fair-isle patterns
through MATLAB programming.

**Ólafur Þór Magnússon**, TODO on 3D modelling

**Brennan Novak**, an American national based in Berlin, he has extensive
knowledge on UI/UX design and a great advocate for open-source software.

His skill sets mainly lies in interface design, user experience design,
front-end engineering, web development, and branding. For the last sixteen years
Brennan has worked for web startups, consulted for Fortune 100 companies (e.g.
Nike), worked at advertising and digital agencies, as well as served individuals
and small to medium sized businesses, as well co-founded TODO.

Brennan’s two main projects in recent years have been MailPile and Qubes OS.
MailPile is a self-hosted e-mail client with easy encryption support, and Qubes
OS is a security-oriented operating system. Both MailPile and Qubes OS are FOSS.

**Áslaug Einarsdóttir** is an advisory to the board. Áslaug is retired, but in
the past she worked as a tailor before starting her own knitwear company
ICESHEEP in the 1970s. Áslaug was the primary knitwear designer working mostly
with lopi. Since retiring in 2005, Áslaug has limited herself to personal
handknits.


3.2. Cooperation
----------------

###### Ef um er að ræða samstarfsverkefni, gerið grein fyrir eðli samstarfsins og gildi þess fyrir verkefnið. Gerið grein fyrir hlutverki allra samstarfsaðila í verkefninu. Lýsið samstarfi bæði við innlenda og erlenda 	samstarfsaðila.

###### If the case of a cooperative, describe the nature of the partnership and value for the project. Please describe the role of all partners project. Describe cooperation both with domestic and foreign partners.

TODO	
	
1.	Check with University of Iceland for cooperation

2.	Brennan’s network within the international FOSS community. 


3.3. Budget
-----------

###### Gerið grein fyrir kostnaði og fjármögnun verkefnisins. Hvernig verður brugðist við ef áætluð fjármögnun til verkefnisins stenst ekki?

###### Please describe the costs and funding. How will react if the projected funding for the project does not?

The majority of the funding is needed for salaries in order for the developers 
to dedicate their time and effort for developement of HiDef Knits and getting the
software off the ground. 
There will be three employees, each specialising in a specific part of the 
software solution: 
Helga will develop the back-end and knitting, 
Ólafur will create the 3D modelling, and  
Brennan supervises the user-friendly interface and has invaluble experince with 
marketing FOSS software. 
Other operational costs are for co-working space, 
yarn to produce realistic textures and stitches, 
website costs (hosting, domain registration, etc.).
	
HiDef Knits is a passion project, so if funding falls through, development will 
be done in the developers spare time, when possible. 
Generally, an open-source project stands or falls with the involvement of the 
core developers and the participation of the community that surrounds it usage. 
Therefore, full-time developement is preferred in the intiital stages in order 
for the project to gain momentum and to be a the point of accepting contribution 
from outside volunteering developers.

Therefore, without sufficent funding, the direction of HiDef Knits would be 
to strip down the proposed functionalities, and focus on only creating support 
in creating grading software for for simple stockinette stitch and basic ribbing 
(leaving cable knit and lace stitch support to other programs). 
Constructional elements build upon a tapered pullover, and releases between 
modules (sleeves, collars, neckline etc.), would be postponed.
The 3D modelling of the garment would be nice to have, as it would help the 
designer visualize the final product before starting the time-consuming process
of actually knitting the garment, but not necessary for the sake of pattern 
creation. An 2D rendering of the individual knit pieces would suffice. 

Perhaps if there could be some cooperation between the already established 
knit chart visualisers, which could import the HiDef Knits pattern pieces 
as a template for further stitch design. Although, it would be preferred
the stitch design would be done in the same software environment as the 
garment construction as there might be some alterations needed to incorporate
prettier pattern repeats of stitches. 


4 Value
=======

4.1. Business objectives
------------------------

###### Lýsið viðskiptalegum markmiðum. Gerið grein fyrir veltu sem afurðin getur skapað umsækjendum á markaði fyrstu 5-10 árin eftir að afurð kemur fyrst á markað. Hvaða markaðshlutdeild er stefnt að.

###### Describe your business objectives. Please describe the turnover of the product may applicants made the market the first 5-10 years after the product comes first market. What market share is planned.

Despite the software being open-source, we intend to offer it freely in source
code form only, and provide the executable binaries to paying customers, i.e.,
offering the commercial service of compiling and packaging of the software.
Since this product is aimed at self-employed designers or personal use the price
is model is not fully determined. Either by a flat-fee for using HiDef Knits
with price range of $25-$30 per user (similar pricing as a knitting handbook),
or we would adopt in-app purchases; where we charge per library modules (i.e.
sleeves silhouettes, collars, bind-off techniques, etc.). 

The most straightforward approach of funding would be selling of our branded 
merchandise, i.e., selling patterns of garment design with HiDef Knits software
on Ravelry.

Another means of revenue, would be to offer commercial technical support contracts 
and services. In that case, professional business (e.g. knitting magazine publishers)
would pay for developement of a particular feature they would like to have.
Similarily, we could sell certificates and trademark use to those businesses
where we lift the restrictive attribution license, which allows them to publish
patterns in book-format without citing HiDef Knits as the pattern generator. 

There could also be a advertising-supported software approach taken, where we would 
for instance partner up with a yarn manufacturer by proposing their yarn for a pattern. 

Other ways for achieving financial return for the costs on open-source software
would be in the form of training seminars, where we could teach proper use of
the HiDef Knits software, along with other related skills beneficial to our
demographic, such as consulting on how to market your designs, model
photography, etc.


4.2. Way to market
------------------

###### Gerið grein fyrir hvernig á að koma afurð á markað (þ.á m. aðferðafræði, áætlaðri markaðshlutdeild, fjármögnun og framleiðslugetu). Lýsið markaðstengslum og bolmagni umsækjenda til að koma afurðinni á markað. Hver er helsta markaðslega óvissan í verkefninu?

###### Give an account of how to bring a product to market (including methodology, estimated market share, financing and production). Describe the market context and capacity of the applicants to bring the product to market. What is the main commercially uncertainty in the project?

TODO	
	
1.  Ravelry, user base 6.45mi.
	Note, Iceland is leading the way with an estimated 346 Ravelers per 10,000 Icelanders! (cf. [http://www.ravelry.com/about/fourmillion](http://www.ravelry.com/about/fourmillion))
	Or 346*332,529/10,000~=11,838 Icelanders with Raverly accounts.	17,500 on Handóðir Prjónarar.
	

2.  International knitting conferences / workshops


4.3. General value
------------------

###### Lýsið á hvaða hátt niðurstöður verkefnisins geta aukið verðmætasköpun á Íslandi umfram tekjur af afurðinni (hagræðing eða auknar tekjur annarra innlendra aðila vegna notkunar afurðarinnar).

###### Describe the manner in which the results of the project can increase value creation in Iceland excess income of the product (efficiency or increased revenues by other residents the use of the product).

The emphasis of HiDef Knits is being an intuitive easy-to-use design tool, that
even the not so computer savvy grandmother would be able to use or even be
useful for those limited or no experience in knitting to design a garment that
they could outsource the knitting to.
HiDef Knits aim is to enable hobby knitters to self-publish their designs for
others to make. Where the output of HiDef Knits could be a valuable income
source for those users who to choose to sell their pattern to others.

Note, of over 262 thousand currently uploaded patterns on Ravelry, 22% of them
are published for free. Among the knitting community, there is a general
consensus that when designing knitwear patterns there is considerable amount of
time, energy, skill, expertise and creativity involved that deserves to be
compensated for. The vast majority of patterns on Raverly are sold for an
estimated $5.05 per pattern (PDF download and paid via PayPal). Knitwear
patterns are quite price sensitive and based with prices from 2008 they have
only increased in terms of inflation.[[5]](#_ftn5)

Most knitwear designers on Ravelry do not make a living by selling their
patterns, and Iceland is no different in that regard. 
There is considerable effort that goes into designing and publishing a
pattern, with on average 34.5 hours spent on each pattern in the production
stage for an experienced knitwear designer not to mention initial cost for
approximately £130 for yarn, tech editing, test knitting.[[6]](#_ftn6) 
By using HiDef Knits, it would be possible to reduce the manual labor needed in 
terms of tech-editing (valued at £30) and human errors that are common due to 
miscalculation
could be avoided, making the patterns virtually error-free. Because, if errors
are found the designers are confronted with increased post-production cost in
terms of working out the error, possibly even having to send the pattern back to
the tech editor for review, which can often take more time than the initial
production. That is why good pattern creation for the beginning is of paramount
importance, and doesn’t cause unnecessary confusion for the knitters using the 
pattern. 

Of 200 Icelandic knitters polled about garment design and software usage, 
82% considered themselves designers, but only 10% had published their patterns.
Most did grading of their patterns for various sizes, but a third only did one 
size. The reasoning why most of the designers did not share their work was 
mostly due to the effort of self-publishing patterns as the design process was 
not structured and done ad-hoc, and sometimes free-form knitting process. 
By using the HiDef Knits software, it would be possible to close the gap 
of aspring designers to published designers. 


5 References
============
[[1]](#_ftn1) Geda, Yonas E., et al. "Engaging in cognitive activities,
aging, and mild cognitive impairment: a population-based study." *The Journal of
neuropsychiatry and clinical neurosciences* 23.2 (2011): 149-154.

[[2]](#_ftn2) Frogging is when knit work is undone – it is called frogging
because frogs say “rip it, rip it.”

[[3]](#_ftn3) Foundation for a Free Information Infrastructure. 
"Patentability and Democracy in Europe". 
[http://swpat.ffii.org/index.en.html](http://swpat.ffii.org/index.en.html).
Retrived: 2016-09-12.

[[4]](#_ftn4) Fair-isle knitting is when multiple colors are knitted
simultaneously over a single row.

[[5]](#_ftn5) Ravelry forum discussion on pricing:
[http://www.ravelry.com/discuss/for-the-love-of-ravelry/2612404/1-25\#12](http://www.ravelry.com/discuss/for-the-love-of-ravelry/2612404/1-25#12). 
Retrived: 2016-09-10.

[[6]](#_ftn6) Woolly Wormhead, "The true cost of a pattern."
[http://www.woollywormhead.com/blog/2014/9/17/the-true-cost-of-a-pattern.html](http://www.woollywormhead.com/blog/2014/9/17/the-true-cost-of-a-pattern.html). 
Retrived: 2016-09-10.

[[7]](#_ftn7) Stephanie Tallant, "Software Review: Stitchmastery Knitting Chart Editor"
[http://www.sunsetcat.com/2011/11/05/software-review-stitchmastery-knitting-chart-editor/](http://www.sunsetcat.com/2011/11/05/software-review-stitchmastery-knitting-chart-editor/). 
Retrived: 2016-09-10.

[[8]](#_ftn8) Stephanie Tallant, "Chartmaking Software Review: EnvisioKnit"
[http://www.sunsetcat.com/2011/07/12/chartmaking-software-review-envisioknit/](http://www.sunsetcat.com/2011/07/12/chartmaking-software-review-envisioknit/). 
Retrived: 2016-09-10.

