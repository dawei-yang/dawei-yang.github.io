---
layout: essay
type: essay
title: A Way to Avoid Repetitive Works
# All dates must be YYYY-MM-DD format!
date: 2018-11-28
labels:
  - Design Pattern
  - Game Design
---

<h2>Introduction  </h2>
<div style="text-indent:2em">
Although we just learned about design pattern recently, I found that I had used many of those concepts in my previous projects and course works. Design pattern is a framework that helps us to manage and reuse codes and projects because many issues have common points.  
In my opinion, it is wisdom that comes from our everyday life, and we can find many examples about this. 

</div>
<h2>Typography  </h2>
<div style="text-indent:2em">
In ancient times, people needed to record their everyday life and artworks by handwriting. They must have a huge amount of repetitive works that they wanted to get rid of.
They invented typography, so they only need to make one seal or stamp mold for each page. The ancient Chinese who invented movable type printing press technology were “lazier”. Each mold was reusable, and they only needed to assemble those molds before printing. They didn’t know what was the next book they needed to print, but they could make it as long as they had enough individual molds. If we apply the MVC design pattern in this case, the book is the model, the view is composing of molds, and human is the controller.
<img class="padding-left" width = "600" length = "400"  src="../images/type.jpg">
</div>
<h2>Why do we need Design Pattern  </h2>
<div style="text-indent:2em">
In my opinion, design pattern is a way software engineers use to avoid repetitive works by creating repeatable frameworks. We encounter many different kinds of problems in software design, but many of them are similar and can be solved by the same strategy. For example, when we recreated ‘digits’ in ICS 314, we adopt a general application template as a start. We could do this because all of the webs have the same features such as login, sign up, database, server, client and so on. 
</div>

<h2>Design pattern in game development</h2>
<div style="text-indent:2em">
	In the final project of a previous game design course, our team used some of the design patterns. The basic concepts of object-oriented programming are related to factory.  We used inheritance and virtual methods to make several similar objects such as enemies. It is a convenient way to reuse exist objects to build more complicated objects.
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
In conclusion, design pattern comes from our everyday life, and we are using the similar ideas to solve problems in many other situation. In software engineering, design pattern is an efficient framework that can reduces works and allow us starting a project fast.
	
</div>
