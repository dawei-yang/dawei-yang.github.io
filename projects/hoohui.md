---
layout: project
type: project
image: images/hoohui.png
title: "hoohui"
date: 2018-12-07
labels:
  - HTML CSS
  - Javascript
  - React
  - Meteor
summary: Our team designed and implemented a web application "Hoohui" in React framewrok, and it connects students and companies with careers. Companies can post jobs, browse students' profiles and send notifications to students that they want to recruit. On the other hand, students can post their profiles, browse the notifications from companies, and reply to companies. We also deployed it in Galaxy.
---
<img class="medium" width="500" height="500" src="../images/android_app.jpg">
<h2> Introduction</h2>
<div style="text-indent:2em">
 Our goal is to create a convenient application that connect students to job opportunities. This application allows students or companies to create their own account. Companies can post new positions. Each position must have name, requirement, description. Company users can see all student profiles and send messege to those who they are interested in. Meanwhile, the students can create their profiles which contain their skills and interests. 
</div>
<div style="text-indent:2em">
    Company users are allow to review all the students' profiles, and they are able to attach a message in a profile of a student whom they are interested in. Students can see the messeges that are attached in their own profiles and reply to the companies that they want to apply.  
  
</div>  
<h2> Design pattern and project management </h2>
<div style="text-indent:2em">
  First, we decided to use MVC design pattern and adopted the <a href="https://ics-software-engineering.github.io/meteor-application-template-react/" >meteor-applacation-template-react template</a>. In this case, MongoDB is the model, and Blaze is the view, and FlowRouter is the controller. Because we had done some practice before, it was easy to start our project with this. 
</div>

<div style="text-indent:2em">
We used Git Hub to manage our project. There are three Milestones each contains eight issues. Each person was assigned two issues, but only one should be in process. Every issue should have a branch. Once I've done an issue, I merged the master to the current branch and tested. If there's no error, then I merged the current branch into the master.
</div>


<div style="text-indent:2em">
On of the most significant work I did was to implement the login system. Companies and students use the same login, and the system should determine the current user belongs to a company or a student and rount the correct page. In order to do this, I need to know how does Meteor manage the user accounts. There are several approaches. I decided to use the profile field in the user account. If a company sign up, a messege "company" will be added into that field, while a student will be marked as "student". When a user logs in successfully, the system looks at that field and redirects the user to the corresponding page.  
</div>
<br/>
Source code: <a href="https://github.com/ho-ohui/hoohui"><i class="large github icon "></i>hoohui</a>
