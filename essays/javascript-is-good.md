---
layout: essay
type: essay
title: Javascript is a good programming language in software engineering
# All dates must be YYYY-MM-DD format!
date: 2018-08-26
labels:
  - Software Engineering
  - Javascript

<img class="center floated image" src="../images/js.jpeg">

<div style="text-indent:2em">
I am majoring Computer Engineering. Most of our courses base on C in order to help us understand the computer architecture.
The syntax of C are more complicated than Javascript, and everything must be declared. I felt Javascript was not strict and 
organized when I started learning it. However, the variables and objects in Javascript can be changed dynamically, which 
gives us flexibility.
</div>
<img class="right floated image" src="../images/c.png">
<div style="text-indent:2em">
	The most significant difference between C and Javascript is the pointer. Pointer allows us access to memory directly 
  while we have to memage the pointer manually. For example, we use “malloc” to allocate memory in the heap and “free” 
  to release the block once we don’t use it anymore. It is hard to manage in a big program, and the mismanaged pointer
  could create memory leaks or security risk such as buffer overflow attack. We don’t need to worry about this in Javascript 
  For example, we need “malloc” to allocate memory in the heap and “free” to release the block once we don’t it. We don’t
  need to worry about this in Javascript since garbage collection will handle automatically. 
  I think that is one of the reason Javascript is better than C and C++ in software engineering. Development of
  hardware allows Javascript manage memory dynamically and automatically, so programmers can get rid of the unsafe
  factors and focus on develop software.
</div>	
  
<div style="text-indent:2em">  
The other advantage of Javascript is the heterogeneous collections. An array can store mixed data types. For example, 
we can store a string and a integer in an array as a record of student’ s name and uh-id and put it in an array of 
ICS314 students. However, in C, we need to define a struct of student with name and id number. Moreover, the size of
array in C is fixed, so we may need to implement a linked list to store those structs dynamically.
</div>	
  
<div style="text-indent:2em">  
	Furthermore, Json is considered as an Object in Javascript. Json is significantly less verbose, so it helps 
  us to define an object clearly. On the other hand, it is easy to read a Json object as human.
</div>

