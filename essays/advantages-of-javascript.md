---
layout: essay
type: essay
title: Advantages of Javascript
# All dates must be YYYY-MM-DD format!
date: 2018-08-31
labels:
  - Software Engineering
  - Javascript
  - C
---

<img class="floated image" width = "400" length = "350" align="center" src="../images/js.jpeg">

<h2>First Javascript  </h2>
<div style="text-indent:2em">
I am majoring Computer Engineering. Most of our courses base on C in order to help us understand the computer architecture, so I am not comfortable Javascript at the beginning.
The syntax of C are more complicated than Javascript, and everything must be declared. I thought Javascript was not strict and 
unorganized when I wrote my first Javascript programme because the type of a variable can be changed while an array can contain different data types. After I have written several Javascript programmes I found those features actually were advantages of Javascript.
</div>
<img class="rounded image" width = "250" length = "250" align="right" src="../images/c.png">


<h2>Garbage collection  </h2>
<div style="text-indent:2em">
	The most significant difference between C and Javascript is the pointer. Pointer allows us access to memory directly, but we have to mamage the pointer manually. For example, we use “malloc” to allocate memory in the heap and “free” 
  to release the block once we don’t use anymore. It is hard to manage this in a big program, and the mismanaged pointer
  could create memory leaks or security risk such as buffer overflow attack. We don’t
  need to worry about this in Javascript since pointer is not allowed and garbage collection handles this automatically. 
  I think that is one of the reason Javascript is better than C or C++ in software engineering. Development of
  hardware technology allows Javascript manage memory dynamically and automatically, so programmers can get rid of the unsafe
  factors and focus on developing software.
</div>	

<h2>Heterogeneous collection  </h2>
<div style="text-indent:2em">  
The other advantage of Javascript is the heterogeneous collections. An array can store mixed data types. For example, 
we can store a string and a integer in an array as a record of student’ s name and uh-id and put that record in an array of 
ICS314 students. However, in C, we need to define a struct of student with name and id number. Moreover, the size of
array in C is fixed, so we may need to implement a linked list to store those structs dynamically.
</div>	

<h2>Other advantages</h2>
<div style="text-indent:2em">  
	JSON is considered as an Object in Javascript. Json is significantly less verbose, so it helps 
  us to define an object clearly. In the WOD of object oriented, we implemented the menu of Jumba Juice, and I found it's easier to use and read. JSON can be recognized by most platforms, so we don't need to worry about format transformation.
	Moreover, Javascript is a protocol oriented language. Protocol Extension allows child classes use the methods in base class directly once those children satisfy the protocol. 
</div>


