# TLDR-diataxis
## Goal
This project aims to be a short and accessible guide for the [The Diátaxis documentation framework](https://diataxis.fr/).
It includes:
- A reduced but comprehensive explanation of the framework -  for general undersanding. 
- Pairs of "template & golden rules" for each of the documentation types defined by Diátaxis - for those in a hurry :D or for those who seek a structured-ish workflow.
## Motivation
Offer a faster way to employ the framework so both maintainers and occasional contributers can agree on documentation standarts. 
Hopefully making [The Diátaxis framework](https://diataxis.fr/) more wide spread and known on the way.

![Diataxis diagram](assets/diataxis-map.jpg)

## What is Diátaxis?
[The Diátaxis framework](https://diataxis.fr/) is a comprehensive guide for maintainers to build great docs.
### Diátaxis Pilars - the map
#### Why understand the map?
The map will help us understand each type of documentation, but even more importantly, it will help us understand __which type of documentation we are trying to create__ - and once we know that - we are beyond the hard part of achiving excellenct documentation. Yeah, this is most of the struggle. 

Take another look at the map (or graph, however you wish to think about it)
we'll see it multiple times.
Diátaxis defines 4 types of documentations:
1. __Tutorials__ - action-oriented activity, learning via doing
2. __How-to Guides__ - action-oriented activity, applying a skill, working toward a goal
3. __Reference__ - cognition-oriented activity, quick-information-lookup while applying a skill
4. __Explanations__ - cognition-oriented activity, learning something more deeply

the list above might be overwhelming for some; its more for setting the stage and being used as a reference we can lookup for the rest of this document. Let's look at the map and things will get clearer as we progress 🧑‍💻​

#### The map of a *skill* or a *craft* :
*note: the terms "skill" and "craft" will be used interchangebly here and they mean the same thing*
![Diataxis diagram](assets/diataxis-map.jpg)
Let's contemplate about this map for a few minutes. 

As you probably noticed, the axises are labeled with 4 types of *states*: they mean to describe the state of the user that reads our docs:
1. Action
2. Acquisition 
3. Application
4. Cognition
![The Axises](assets/two-dimensions.png)

##### 

Each type of documentation falls within a different quad of the map that represents the intersection of one of the four *states*! 

##### It's not clear! I agree! Let's simpify :) 

### Learn vs Work lens
Let's take those user *states* mentioned earlier and roughly divide them into two categories:
1. Learn (*Acquisition*)
2. Work (*Application*)
(In other words: The X-axis!)

and from now on, we keep those division lens on and look at everything via them. 
Let me explain breifly: 
#### When we learn something:
We are not working. Or not producing anything of value except our own ***acquision*** of some knoweldge or skill.
We are looking for a resource that will teach us some *tool* or *concept* or basic *knowledge* that we know we currently lack in order to complete a future task.
In other words, we are not creating anything valueable that someone else can use (code, article, tools, etc.).
**We are focused on learning a concept - the concept we look to _acquire_ and be comfortable with.**
**We are asking ourselves:** (or the resource)
> Can you teach me *X* ?

for Example: 
You are a python developer and you arrive at a new company (yay). You clone the repo and you see that all of the tests are written in the pytest framework. Supposed you used other testing frameworks so far and the pytest form is unreadable for you at the moment. You must learn the framework's basics in order to start reasoning about the existing code and contribute to the project (assume this is project that enforces tests coverage). 
You are looking for someone to take you by the hand and teach you the framework's basics - __that's a Tutorial.__
| Such a Tutorial **cannot** and **should not** teach | where it belongs | category |
|-------------------------------------------------------|------------------|----------|
| how to implement a pytest plugin                      | How-to           | Working |
| how to parametrize fixtures                           | How-to           | Working |
| pytest's internal mechanisms                          | Explanation      | Learning |
| pytest's internal APIs                                     | Reference        | Working  |

__Why?__
A tutorial is aiming at teaching a concept that the pupil can generalize and build a skill upon, and it is hyper focused on action-learning. __Almost any__ explanation is unnecessary here and distructs the pupil. It's like a cooking book that teaches you basic cooking concepts, but not complete recipes - it walks you throu basic frying, baking and slicing - pointing our attention at things that will help you acquire the general skills so you can capatelize on them when you follow future recipes! 

*However...*
#### ...When we work on somehting 
We already have *sifficient working knowledge/skill* in the field or craft. 
We already *__acquired__* the basics and the conceptual knowledge and now we are looking to *apply* it into something meaningful and productive.
We know roughly what we are doing, what we should do, and we have some idea of ways to achieve our goal, but it's vauge, or we are just no sure yet. We know there's a way - we just need someone that will show it to us. 
**We are focused on the goal - the thing we want to get *done*. Our desitinaiton. 
We are asking ourselves:**
> How-to do *X*?

For Example:
supposed you are a Python developer looking for a way to make your test suite more compact and easy to maintain while not compromising on the coverage of your tests (in fact, your'e looking for a way to get more coverage with less hassle). Your'e working with pytest for a while and you comfotably write tests and fixtures that sutisfied you up until now (you alreday *aquired* the skill of working with pytest and its basic concepts). 
You notice the boliraplate patterns in your suite and you know that some parametrizatoin solutions are out there, and you step on a pytest How-to guide: ***"How to parametrize your tests"***. Great. 
| Such a How-to guide **cannot** and **should not** explain | where it belongs | category |
|-----------------------------------------------------------|------------------|----------|
| the basics of pytest                                      | Tutorial         | Learning |
| pytest's core featuers                                    | Tutorial         | Learning |
| its internal mechanisms                                  | Explanation      | Learning |
| Its internal APIs                                         | Reference        | Working  |

##### why?
__Answer:__ It must stay hyper focused on the goal - show you how to parametrize your tests; **helping you get that work *done*.**
Remeber: How-to guide is *work-oriented* document, hyper focused on the goal. It's like a recipe - you use it to follow instruction towards a specific dish - not to learn cooking's basics (that's tutorial), or contemplate on cooking chimestry and why oil makes everything taste better (explanation) or what are the nutritions facts of our favorate ingridient (reference). 
*More on __Referecne__ and __Explanation__ right away*

## Ok. We understand Tutorials and How-to guides, but what about Reference and Explanation?
---

## Do vs Think lens
Let's create another way of devision of our user-states described by the axises:

1. Do (*Action*)
2. Think (*Cognition*)

In other words: the Y-axis! 
From now on, we put those "Do vs Think" lens *on top* of our previuos "Learn vs Work" lens, so we see everything via both of them!

### When we are in "Doing" mode
We do not contemplate about things, maybe just a little, but most of the time it's our favorite keyboard caps clickin' :D .
"Doing" (*action*) isn't exclusively bound to either Learning or Working. It exists in both of them (tho I agree it is more clearly linked to Working), however, a good tutorial is one that pushes the pupil to do stuff and learn via action. 
Recall the map again, notice action(doing) exists for both Aquisition(learning) and Application(working):
![Diataxis diagram](assets/diataxis-map.jpg)
Tutorials and How-to Guides, despite belonging to the different categories of Learning and Doing correspondingly, share in common the fact that their are action-oriented towards the reader. In Tutorials the user is looking to learn a concept and we guide them via action-orinted lesson, while in the How-to Guide the user looks to accomplish a specific goal.

### When we are in "Thinking" mode
There's less clicking noise from our keyboard. We turn on noise cancellation. We contemplate about the concept, either *shallowly and breifly* when we *work* and we need a quick lookup to something (Reference), or *for longer period of time and deeply*  when we are curiuos and wish to gain deep understanding and *learn* the inner workings of our tools (Explanation). 

__Both Thinking and doing modes spans across the Learning and Working spaces, but in different ways.__

#### What's a Reference? 
A dry collection of small and densely compact pieces of information. And by information we mean __nothing but information__. There're no opinions or explanations in the reference (tho some examples for context are OK when necessary) and there's no teaching!
Nobody ever reads it. It's unreadable by design. It should be **consulted with**, not read.
 Remember, this is ***working** oriented guide, not learning*.

Recall this scene from The Big Short...
> Michael Burry : It's only a matter of time before someone else sees this investment. We have to act now.
> Lawrence Fields : And how do you know these bonds are built on subprime crap? Aren't they filled with f***ing hundreds of pages of mortgages?
> Michael Burry : I read them.
> Lawrence Fields : You what?
> Michael Burry : I read them.
> Lawrence Fields : You read them? __No one *reads* them, Michael__...

Lawrence was right. No one reads bonds. A collective of dry infromation ment not to be read but consulted with. Indeed no one read them. Except Michael Burry. 

Examples:
| context | example of reference |
|-----------------------------|-|
| Accounting | spreadsheets |
| cooking | the nutritions facts on the back of a product|
| Technical textbook | glossary or author's notes at the end of the book | 
| __software documentation__ | __API reference__ - a dry list of the methods / __Architecture diagram__ - defines software components relationships |

We're focused here on the software angle of things. 
API reference in software documentation is (usually auto generated) list of the class and methods, with little and short explanation of each in case the name isn't clear. 

##### If reference is both *thinking* (Cognition) and *working* (Application) related, when the user approaches it in the real world? 
When they need a quick lookup for something. 
For Ex:
- A user is looking for a specific endpoint of your API. 
- A user is trying to build a plugin that expands your tool's ecosystem. they'll look and consider possible entry points more than once. Each time they'll go back to your reference and lookup viable options. 

#### What's an Explanation? 

Explanation is an exceptional type of documentation from the rest in the sense that it is the only type of documentation the user can engage with when they're **away from the product**. 

The Explanation is an invitation for the user to dive deeper into the product, and the proper place to bring to light things that were implicit or obscured so far.
It is also the only place to express your thoughts and opinions - but only in a way that won't leave your users ignorant of opinions that counter yours.
For Example:
1. Design choices
2. Technical constraints (e.g. when users ask __why__ certain things are impossible)
3. Historical reasons 
4. A broader view at the product's ecosystem (if exists).
5. The philosophy and motivations at the heart of the product
6. Future plans / things this product will never be

While it may be tempting to think of explanation as a luxury to have, and understandably it takes time to put together, it is not a luxury. Without explanation your users understanding of your product is:
- fragmented
- fragile
- and their experience is anxious. 

Explain stuff to your users. They will return you with love and contributions.
