# TLDR-diataxis
(WIP)
This project aims to be a short and accessible guide for the [The Diátaxis documentation framework](https://diataxis.fr/).

![Diataxis diagram](assets/diataxis.jpg)

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

the list above might be overwhelming for some; its more for setting the stage a being used as a reference we can lookup for the rest of this document. Let's look at the map and things will get clearer as we progress 🧑‍💻​

#### This map is of a *skill* or a *craft* :
![Diataxis diagram](assets/diataxis.jpg)
Let's contemplate about this map for a few minutes. 

As you probably noticed, the axises are labeled with 4 types of *states* of the user that reads your docs:
1. Action
2. Acquisition 
3. Application
4. Cognition
![The Axises](assets/two-dimensions.png)

##### 

Each type of documentation falls within a different quad of the map that represents the intersection of one of the four *states*! 

##### It's not clear! I agree! Let's simpify :) 

### Study vs Work lens
Let's take those user *states* mentioned earlier and roughly divide them into two categories:
1. Work (*Application*)
2. Learn (*Acquisition*)
(In other words: The X-axis!)

and from now on, we keep those division lens and look at everything via them. 
Let me explain breifly: 
#### When we learn something:
We are not working. Or not producing anytihng of value except our own ***acquision*** of some knoweldge or skill.
We are looking for a resource that will teach us some *tool* or *concept* or basic *knowledge* that we know we currently lack.
In other words, we are not creating anything valueable that someone else can use (code, article, tools, etc.).
**We are focused on learning a concept - the concept we look to _acquire_ and be comfortable with.**
**We are asking ourselves:**
> Can you teach me *X* ?

for Ex: 
You are a python developer and you arrive at a new company. You clone the repo and you see that all of the tests are written in the pytest framework. Supposed you used other testing frameworks so far and the pytest form is unreadable for you at the moment. You must learn the framework basics in order to start contributing to the project (assume this is project that enforces tests coverage). 
You are looking for someone to take you by the hand and teach you the framework's basics - __that's a Tutorial.__
| Such a Tutorial **cannot** and **should not** teach | where it belongs | category |
|-------------------------------------------------------|------------------|----------|
| how to implement a pytest plugin                      | How-to           | working |
| hot to parametrize fixtures                           | How-to           | working |
| pytest's internal mechanisms                          | Explanation      | Learning |
| Its internal APIs                                     | Reference        | Working  |

__Why?__
A tutorial is aiming at teaching a concept that the pupil can generalize build a skill upon, and it is hyper focused on action-learning. __Almost any__ explanation is unnecessary here and distructs the pupil. Resis the temptation to explain in a tutorial. It's like a cooking book that teaches you basic cooking concepts, but not complete recipes - it walks you throu frying, baking and slicing - pointing our attention at things that will help you aquire the general skills so you can capatelize on them when you need to! 

*However...*
#### ...When we work on somehting 
We already have *sifficient working knowledge/skill* in the field or craft. 
We already *Acquired* the basics and the conceptual knowledge and now we are looking to *apply* it into something meaningful and productive.
We know roughly what we are doing, what we should do, and we have some idea of ways to achieve our goal, but it's vaug, at best. We know there's a way - we just need someone that will show it to us. 
**We are focused on the goal - the thing we want to get *done*. Our desitinaiton. 
We are asking ourselves:**
> How-to do *X*?

For Ex:
supposed you are a Python developer looking for a way to make your test suite more compact and easy to maintain while not compromising on the coverage of your tests (in fact, your'e looking for a way to get more coverage with less hussle). Your'e working with pytest for a while and you comfotably write tests and fixtures that sutisfied you up until now (you alreday *aquired* the skill of working with pytest and its basic concepts). 
You notice the boliraplate patterns in your suite and you know that some parametrizatoin solutions are out there, and you step on a pytest How-to guide: ***"How to parametrize your tests"***. Great. 
| Such a How-to guide **cannot** and **should not** explain | where it belongs | category |
|-----------------------------------------------------------|------------------|----------|
| the basics of pytest                                      | Tutorial         | Learning |
| pytest's core featuers                                    | Tutorial         | Learning |
| it's internal mechanisms                                  | Explanation      | Learning |
| Its internal APIs                                         | Reference        | Working  |

##### why?
__Answer:__ It must stay hyper focused on the goal - show you how to parametrize your tests; **get that work *done*.**
Remeber: How-to guide is *work-oriented* document, hyper focused on the goal. It's like a recipe - you use it to follow instruction towards a specific dish - not to learn cooking's basics (that's tutorial), or contemplate on cooking chimestry and why oil makes everything taste better (explanation) or what are the nutritions facts of our favorate ingridient (reference). 
*More on __Referecne__ and __Explanation__ right away*




## Goal
Create a reduced version of the document: [The Diátaxis documentation framework](https://diataxis.fr/).  
The guide should explain briefly and reduce the framework to a list of guidelines,  
"Do's and Dont's," with some accompanying examples,  
so anyone who writes documentation can quickly check on themselves.  
This reduced version of Diataxis won't cover [The Diátaxis documentation framework](https://diataxis.fr/) in its Orthodox interpretation.  
However, it is better than the Wild West of documentation we suffer from today,  
and it may encourage some to go deeper on the matter and perfect their docs.  

## Motivation
[The Diátaxis framework](https://diataxis.fr/) is a comprehensive guide for maintainers to build great docs.  
The sad truth is - most people won't (or can't) make the time to learn it.  
Understandably, documenting takes time and effort.  
And learning [The Diátaxis framework](https://diataxis.fr/) also takes time.  

In order to encourage more maintainers to adopt [Diátaxis](https://diataxis.fr/) as a standard for their docs,  
either via their own craft or by outside, one-time contributors,  
we need to make this knowledge more accessible and digestible.  
