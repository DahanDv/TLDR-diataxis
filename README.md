# TLDR-diataxis
(WIP)
This project aims to be a short and accessible guide for the [The Diátaxis documentation framework](https://diataxis.fr/).

![Diataxis diagram](assets/diataxis.jpg)

## What is Diátaxis?
[The Diátaxis framework](https://diataxis.fr/) is a comprehensive guide for maintainers to build great docs.
### Diátaxis Pilars 
Take another look at the map (or graph, however you wish to think about it)
Diátaxis defines 4 types of documentations:
1. Tutorials
2. How-to Guides
3. Reference Guides
4. Explanations Guides
![Diataxis diagram](assets/diataxis.jpg)

As you probably noticed, the axises are labeled with 4 types of *states* of the user that reads your docs:
1. Action
2. Acquisition 
3. Application
4. Cognition
![The Axises](assets/two-dimensions.png)
Let's take a closer look at this: 
- The X-axis: *Action* and *Cognition* is the 

Each type of documentation falls within a different quad of the map that represents the intersection of one of the four *states*! 

##### It's not clear! I agree! Let's simpify :) 

### Study vs Work lens
Let's take those user *states* mentioned earlier and roughly divide them into two categories:
1. Work
2. Learn

and from now on, we keep those division lens and look at everything via them. 
Let me explain breifly: 
#### When we learn something
We are not working. Or not producing anytihng of value except our own ***aquision*** of some knoweldge or skill.
We are looking for a resource that will help us understand some *tool* or basic *knowledge* that we know we currently lack.
In other words, we are not creating anything valueable that someone else can use (code, article, tools, etc.).
for Ex: 
If we just **learn** what is an API, its basic usecases and examples ***in a Tutorial***, we do not expect to find at the same tutorial instruction of how to design a complexed and abstruct meta-programing plugins-architecture APIs; That would be nuts for someone who's just trying to get the basics of a concept or a tool! 
Such How-To guide will assume we already have suffecient knowledge to approach such task in the first place!
*However...*
#### ...When we work on somehting 
We already have *sifficient working knowledge/skill* in the field or craft. 
We know roughly what we are doing, what we should do, and we have some idea of ways to achieve our goal. 
**We are focused on the goal - the thing we want to get *done*.
We are asking ourselves:**
> How-to do *X*?

For Ex:
supposed you are a Python developer looking for a way to make your test suite more compact and easy to maintain while not compromising on the coverage of your tests. You notice the boliraplate patterns in your suite and you know that some parametrizatoin solutions are out there, and you step on a pytest How-to guide: ***"How to parametrize your tests"***. Great. 
Such a How-to guide **cannot** and **should not** explain: 
the basics of pytest, 
it's core features, 
or it's internal mechanisms.
It must stay hyper focused on the goal - show you how to parametrize your tests; **get that work *done*.**




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
