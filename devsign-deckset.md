# devsign

^ As iOS developers, we have lived through a number of revolutions over the years.

--- 

![](Images/iPhoneOS2.jpg)
# 2008

^ First there was the revolution of 2008, when we could develop native apps for the iPhone OS for the first time.

---

![](Images/Swift.png)
# 2014

^ Recently there was the revolution of 2014, where we got a brand new programming language: Swift.

---

![](Images/JonyIve.jpg)
# 2013

^ But to me personally, the most significant and exciting revolution, was the revolution of 2013, when Jony Ive gave a keynote at WWDC that introduced the brand new design mindset of iOS 7.

^ With a single grand stroke, Jony officially banished skeumorphism from the ecosystem. 

---

![left](Images/DodgeballLeather.jpg)
## "... this isn't what we ordered"

^ It was a sad day for leatherworkers across the world.

---

> Design... 
> It's the whole thing,
> **the way something actually works**. 
-- Jony Ive

^ In its place Jony introduced a new "flat" style focused on clarity, deference, and usability. He explained it like this:

^ "We have always thought of design as being so much more than **the way something looks**. It's the whole thing, **the way something actually works**." - Jony Ive

^ This really spoke to me as a developer with dormant design sensibilities.

^ I've always been amazed by graphic designers and their technical prowess, but at the same time I was always too scared to really try and create something in their medium.

---

## Just like real life!
![inline](Images/Skeumorphism.png)

^ Skeumorphism scared me off even further, because back then apps were distinguished by who had *the most realistic wood effect* in their UI, and I could barely draw a stick figure. 

---

## adding leather/wood
## ≠ 
## important

^ And then after that specific keynote, none of that mattered anymore. The *leather and wood are gone* and we're told that design is not just about the way something looks. 

^ This was great news for me, because I no longer had to be scared about being a Photoshop/Illustrator *n00b*.

---

## making things work 
## = 
## important

^ Even better, I was told that design encompasses the way something actually works. 

^ And what do we do as iOS developers? *We make things work*. 

^ Our apps may look ugly, they may be a little hard to use, but hey, with just a limited set of tools we can actually make things work. 

---

![fit](Images/LightBulb.png)

^ So after that keynote by Jonny Ive, I had a true lightbulb moment.

^ I realized that if my skills at making things work are essential to an app's design, then I really want to be involved in app design.

^ And I hope you do too.

---

## design-centric development
## =
## devsign

^ The aim of this talk is to encourage you to become a design-centric developer, being able to shape your app's design as it's being developed and help out with part of the process.

^ The ability to devsign is becoming increasingly important as software production keeps moving from staged waterfall models to collaborative agile ones. 

^ App teams are usually quite small and require great communication, so understanding your team-mates and working towards the same goal is paramount. No matter what each of your disciplines or skills may be.

---

## Designers & Developers
![inline](Images/DesignerDeveloper.png)

^ Designers and developers are usually seen as polar opposites: Right-brain vs Left-brain. However, there are many similarities between us like being analytical, solving problems, loving coffee, and hating glare.

^ I could list many more, but the one that truly matters and can mend any differences is this: designers and developers are both passionate about making great apps. 

^ We will push and pull on each other in equal measure because creating an app is not an entirely linear handoff process until it ships, it's an interwoven journey that you must embark upon as a cohesive unit. 

^ As we move along, you'll notice that two things will always hold true: 

---

### design will create new *demands* for development

---

### development will reveal *gaps* in design

---

### so...

^ So... 

^ How do you improve harmony and increase alginment with designers?

^ Where do you start if you're short on resources?

^ Why should you approach development with a design-centric mindset?

^ Well, there are many different subsets of design that tackle specific challenges, but I'll give you a quick overview of the 4 main design disciplines:

---

# product

^ Product

---

# interaction

^ Interaction

---

# visual

^ Visual

---

# user experience

^ User Experience

---

![left 50%](Images/PokerFace.png)
## "... say what?"

^ These may seem like just a bunch of buzzwords to you right now and that's just fine.

^ For each of these, I will give a basic definition and simplified overview, along with a few tips on how, as a developer, you can influence key design decisions at each stage of app production and maybe help out a bit too. 

^ However, your ability to influence the overall production cycle depends on the size and structure of your organization.

^ So, take this advice with a pinch of salt and really think about how it applies to you. How far can you take it? How much do you want to learn? Where do you draw the line?

^ Whatever your choice is, I hope I can at least make the design world seem more accessible :]

---

## product design
### "what should the app *do*?"

^ The first step in making an app involves product design.

^ In this stage, you want to figure out *what the app should do*, at a high level.

^ This is a good time to take a look at the competition, see what features their apps have, look at their reviews, and see if there's any common things that people love or hate about those apps.

^ It's also a good time to make sure that an app fits in well with your company or client's overall strategy, and that it's worth the time, money, and effort to make it in the first place. 

---

![inline](Images/CrittercismTweet.png)

![inline](Images/HealthKit.png)![inline](Images/WatchKit.png)![inline](Images/CloudKit.png)

^ I became interested in product design by simply reading about the business-side of apps. What was the industry trending towards, what are my competitors up to, and what are the emerging technologies in the field?

^ Eventually, I was constantly thinking of new features and the APIs I could use to make them possible. Sharing them with friends and co-workers was great too, because I could get an immediate *"well that's stupid"* or *"wow that's awesome"* and discuss my ideas.

^ Doing this several times meant I was more comfortable participating in sales pitches or project scoping, and was greatly appreciated in key decisions on adding or dropping a feature based on my technical expertise.

^ Though I never fully acted as a product designer, I could certainly help make sense of an app as it was being developed.

---

## interaction design
### "how should the app be *used*?"

^ The next step you'll encounter is interaction design.

^ In this stage, you want to figure out *how the app should be used*, at the UI level.

^ This is the time to think about how many screens you'll have, what your I/O points will be, and devise a logical flow between all the different features of your app in terms of UI components.

^ This is also a great time to think of common patterns and expected behaviors in human<->computer interaction, without resorting to needlessly complex gestures or screens to accomplish a task.

---

![inline](Images/Gestures.png)

![inline](Images/Feedback.png)

^ Once I got past the big scary words and fancy methodologies, I realized that participating in interaction design was easy if I just stuck to iOS platform patterns and got really comfortable wth view controllers, segues, and actionable components.

^ Once I could build a storyboard with ease, I was able to engage in rapid prototyping and analyze the advantages/disadvantages of different navigation solutions, such as *Tab Bar Controller -vs- Page View Controller*.

^ And really, as I was putting designs together and trying to make something work, I would let my iOS dev expertise come through and redefine the navigation hierarchy if it was breaking norms, modify UI components to make more sense, and experiment with different gesture recognizers.

^ Turns out, interaction design was a big part of my day-to-day.

---

![inline](Images/FuchsTweet.png)

![inline](Images/HumanInterfaceGuidelines.jpeg)

^ So at this point, I imagine many of you are thinking "If this is Interaction Design, then I'm definitely an Interaction Designer!"... and this is certainly true to a large degree.

^ For iOS developers at least.

^ Thanks to *Apple's Human Interface Guidelines*, UIKit, and their tightly controlled ecosystem, we can put our trust in well-defined platform patterns and user expectations.

^ However, if you come from old-school desktop development or the wild wild web, you'll know that interaction design can be very complex, largely decentralized, and definitely needs a lot more thought. It's not always a given and that's where we need the pros. 

^ Not all problems are created equally though, so make sure your app stands out by solving these problems in an easy way; not by making more along the way. Apple made it easy, but not dispensable.

---

## visual design
### "how should the app *look*?"

^ Once your interactions are sorted, it's time to make your app beautiful and meaningful with visual design!

^ In this stage, you want to figure out *how the app should look*.

^ This is the time to think about the best presentation of your UI as well as the best representation of its purpose.

^ It's a great time to think about your brand and make sure that the look and feel of your app fits in well with your company's metaphors and customer's emotions. Your choice in color, typography, and layout can really sway a user's review.

---

![inline](Images/MengTweet.png)

^ When people hear "design", they usually think of "visual design" and can get scared off because of the technical skill and tool mastery it requires. However, I was able to participate in the process by simply getting to know the more *visual side of Xcode*, with features such as canvas rectangles in Interface Builder and the all-new live rendering.

^ Xcode can only do so much though, so I began to meet designers half-way and try to handle some of their more menial tasks which I actually found quite exciting. I barely know my way around Illustrator, but with a few basic commands I'm able to take a raw file and slice icons, modify their color, and adjust their size.

^ Eventually, your skills and interest will grow if you just commit a little bit of your day to these tools and follow good tutorials, much like you would on RayWenderlich.com. 

---

![inline 88%](Images/Fonts.jpg)

![inline](Images/ColorWheel.jpg)

^ I'm still very new to the field, but I'm hoping to make "the leap" some time and whenever I can I try to choose my own color palettes, mess around with different layouts, and even make some of my own icons.

^ The easiest way to earn a bad review, besides a crash, is to greet your new user with *Bright Green Comic Sans*. Trust me. Poor visual design may not affect the usability or performance or your app, but it can certainly make you look like an amateur. 

^ You don't have to become an expert in Photoshop and Illustrator because I know they can be pretty complex, but there are easier options for UI design out there - like Sketch!

^ However, if you can't find the time to learn a new tool, then simply focus on the pursuit of simplicity. Highlight the useful by making it beautiful! And don't forget your Typography and Color Wheel basics :P

---

## user experience design
### "... everything?"

^ Finally, we've reached the hot-topic of UX design...

^ UX design is the process of enhancing user satisfaction with your product by improving its usability. Therefore, it's the most empowering and accessible discipline to us developers.

^ And not only us but all of your teammates as well, because user experience is defined by any and all exchanges between a user and an app.

^ So, whether you've been aware of it or not, *anything you've implemented that affects your user is considered UX design*.

^ Designer purists will berate me for this, but I think that, in many ways... 

---

> devs are the ultimate gatekeepers of ux
-- Me

^ ... developers are the ultimate gatekeepers of UX.

^ Why? Well, users can't interact with an idea, they can't shop with sketches, and *they can't message through a .psd file*.

---

# iOS .ipa ≠ 
![right 100%](Images/IPA.jpg)

^ But, *they can definitely use an .ipa*. 

^ As mentioned in the beginning, developers have the ability to make something that works and we can ship it too - no matter how ugly it looks, how hard it is to use, or how badly it performs in the app store.

^ At least it's out there as a full-fledged app. 

---

![inline](Images/ReviewAP.png)

![inline](Images/ReviewSP.png)

![inline](Images/ReviewTW.png)

![inline](Images/ReviewVC.png)

![inline](Images/ReviewWF.png)

^ Furthermore, a lot of UX is defined by the responsiveness of your app. For example, asynchronous networking and 60 FPS animations are benchmarks of great UX, both defined by technical metrics that live within the developer's code. 

^ And if you disagree, I'm sure Scott Goodson will have a few words for you ;]

^ So, the easiest path for you to *"devsign for UX"* is to view your implementation from a user's point of view and make any future decisions with this mindset.

^ Reduce your crashes. Improve performance. Listen to your users, observe their behaviours, incorporate their feedback, and anticipate their reactions.

---

## ux 
## = 
## home

^ UX is your home. Indie or Big. Seasoned or New. This is what you do day-in and day-out, though you might not have realized it :]

---

## p + dev 
## =
## tangible ideas

^ Able to validate the feasibility of new features

---

## i + dev
## =
## quick prototypes

^ Can compare several solutions with ease

---

## v + dev
## =
## beautiful interfaces

^ Whatever you make will look amazing

---

## p + i + v + dev
## =
## app

^ You're in the App Store

---

## bad ux * (p + i + v + dev)
## =
## bad app :[

---

## good ux * (p + i + v + dev)
## =
## good app :]

---

# dev·sign
### verb \dēv-ˈzīn\

^ I hope you all embrace the opportunity to *devsign*, because iOS developers have a huge advantage over all others.

^ We have incredible design-centric tools like Interface Builder. We have a closed platform that strives for uniformity. We subclass from UIKit.

^ Remember that - like Jony Ive said in the revolution of 2013 - design isn't just about how it looks, but also how it works.

^ The lines between design and development have never been easier to cross.

^ Keep honing your developer craft, but take interest in design too - it's not that scary.