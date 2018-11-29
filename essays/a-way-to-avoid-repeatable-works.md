---
layout: essay
type: essay
title: A Way to Avoid Repeatable Works
# All dates must be YYYY-MM-DD format!
date: 2018-11-28
labels:
  - Design Pattern
  - Game Design
---

<h2>Introduction  </h2>
<div style="text-indent:2em">
Although we just learned about design pattern recently, I found that I had used many of those concepts in my previous projects and course works. Design pattern is a framework that helps us to manage and reuse codes and projects because many issues have common points.  
In my opinion, it comes from our daily life, and we can find many examples about this. 

</div>
<h2>Typography  </h2>
<div style="text-indent:2em">
In ancient times, people needed to record their daily life, artworks, and articles by handwriting. They must have many repeatable works that they wanted to get rid of.
Finally,  they invented typography, so they only need to make one seal or stamp mold for each. The ancient Chinese who invented movable type printing press technology were “lazier”. Each mold was reusable, and they only needed to assemble those molds before printing. They didn’t know what was the next book they needed to print, but they could make it as long as they had enough individual molds. This was how ancient people used their wisdom to make their life easier.
<img class="padding-left" width = "600" length = "400"  src="../images/type.jpg">
</div>
<h2>Advantages of Design Pattern  </h2>
<div style="text-indent:2em">
In my opinion, design pattern in software engineering is similar to typography. It is the way software engineers use to avoid repeatable works. We may encounter many different kinds of problems in software design, but many of them are similar and can be solved by the same strategy. For example, when we recreated ‘digits’ in ICS 314, we adopt a general application template as a start. We could do this because all of the webs have the same features such as login, sign up, database, server, client and so on. 
</div>

<h2>Design Pattern in Game Design</h2>
<div style="text-indent:2em">
	In the final project of a previous game design course, our team used some of the design patterns. The basic concepts of object-oriented programming are related to factory.  We use inheritance and virtual methods to make several similar objects such as enemies. It is a convenient way to reuse exist objects to build more complicated objects.
</div> 
<div style="text-indent:2em">
We also found singleton was very useful. The interactions between game objects can be complicated and predictable. Some events may consist a while but game objects may have been destroyed before the those events finished. Therefore, a singleton object such as main camera is the best object for handling events. This model also includes an observer since the main camera will notify all related game objects. For example, if our hero collectes an object that can freeze all enemies several seconds, the main camera should notify all game objects that are labeled as ‘enemy’. 
</div>
<img class="padding-left" width = "600" length = "400"  src="../images/gamedesign.jpg">
<div style="text-indent:2em">
The project is also a MVC design pattern. The SQLite database is the model which carries data and can update the controller if there are changes. The Unity engine is the view, and it visualizes all objects. The C# scripts compose the controller. The controller acts on both model and view. 
</div>

<h2>Conclusion </h2>
<div style="text-indent:2em">

	
</div>