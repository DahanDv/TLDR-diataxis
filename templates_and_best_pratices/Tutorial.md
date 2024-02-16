This isn't a hard template, but a very fluid one which you can use as a starting point that will remind you the most important Do's and Don'ts of putting together a good tutorial. 
If you are not sure wether its a tutorial or how-to or any other type of docs that you need to create, consider reading the README of this project.


## Golden rules for excellent tutorial 
1. Clarify with yourself (or with your users) the reasons for creating this tutorial: what concept or skill the user wants to learn?
2. The lesson must be:
	1. *meaningful* - the pupil needs to have a sense of achievement. 
	2. *successful* - the pupil needs to be able to complete it. 
	3. *logical* - the path that the pupil takes needs to make sense. 
	4. *usefully complete* - don't leave it to them to figure out from a certain point. At the end of a lesson the pupil must be familiar with all the actions, concepts and tools they will encounter. 

3. **Don't try to teach**
When you do, you'll inevitably surrender to the urge of impart knowledge and information. 
you need to focus on **structuring a way, a path, in which a pupil can walk through and learn the concepts by passing through steps and following your exercises and examples.**

4. Declare a clear path at the outset. Example:
*"In this tutorial we will create and deploy a scalable web application. Along the way we will encounter containerization tools and services."*

5. **Deliver visible results early and often** 
The ideas you communicate are trivial for you, but also weird and anxiety triggering for you pupil. Ideally: __every step the learner follows should produce a comprehensible result, however small.__ This helps keep the user calm, motivated, and connnecting cause and effects.

6. **Ruthlessly minimize explanation**
It's a distraction for the pupil. Cause and effect, action-oriented learning, connecting the dots. that's all matters right now. If explanation is needed, there's a place for that.

7. **Maintian a narrative of the expected and point out what the learner should notice**
Another way to mitigate the anxiety of the pupil 
    > *"will this produce the right result?"* 

    is to **keep on telling what should happen**.
    For example:

    > *"You will notice that …{some output form cli}"* 
    > *"After a few moments, the server responds with …"*
    
    If you are aware of a common mistake - let the user know, help them troubleshot this. 

    While your pupil is hyper focused on the input-output things, it's on you to prompt them to zoom out and notice env changes - which is a crucial part of learning. 

8. **Aspire to perfect reliability**
If the user follows your instruction and doesn't get the result you promised, that's a confidence(and time) killer for them. 

---

# Title: ____ Tutorial

## Intro
*give some background briefly. Assume no familiarity with the subject. if the user is confident wiht his skills, he may be referred to the relevant How-to Guide*

__*declare a path*__
In this tutorial, ==we== are going to:
 - X 
 - Y 
 - Z  
 
By the end of this tutorial, you will be confident doing: x', y', z'.

### Part I - X
*env setup (espire for perfect reliability)*
*what are we going to do in this part
walk the user step by step*

Ideally, every step is an iteration of this loop:
1. Action
2. Result
3. Point out what the user should notice, if anything (No drifting into explanation!)

Progression by action.

*sammerize this part very briefly,
next we are going to do Y*

### Part II - Y
*Repeat the steps in part I
Ideally, this part II builds on the foundation created in Part I
If this is the case, keep remiding this to the user, and point out the elements we curry from previuos parts. 
Repetetion is a great teacher. it's not code, it's a tutorial. Remeber that.*

### Part III - Z 
*Ideally you should keep building on the accumolating foundations created at Parts I-II.*
*You can give a refreshed angle for your examples*

### Summery
*Reflect to the user the path declared at the beggining. 
this is a great spot to refer the user to all How-to Guides related to the topic!*


