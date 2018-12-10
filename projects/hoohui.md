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
summary: Our team designed and implemented a web application "Hoohui" in React framewrok, and it connects students and companies with careers. 
---
<img class="medium" width="700" height="500" src="../images/companyhome.PNG">
<h2> Goal</h2>
<div style="text-indent:2em">
 Our goal was to create a convenient web application that connects students and companies with job opportunities.  We used HTML, CSS, and Javascript along with React framework to develop this application which allows students or companies to create their own account. Companies can post new positions. Each position must have name, requirement, description. Meanwhile, the students can create their profiles which contain their skills and interests. This app We also deployed it to Galaxy.
</div>
<div style="text-indent:2em">
    Company users are allowed to review all the students' profiles, and they are able to send messeges to whom they are interested in. Students can see the messeges that are attached in their own profiles and reply to the companies where they want to apply. Admin can see all the profiles and positions and delete those that are not appropriate.
</div>  
 
<h2> Design pattern and project management </h2>
<div style="text-indent:2em">
  We followed the MVC design pattern and adopted the <a href="https://ics-software-engineering.github.io/meteor-application-template-react/" >meteor-applacation-template-react template</a>. In this case, MongoDB is the model, and Blaze is the view, and FlowRouter is the controller. Because we had done a similar project before, it was easy to start our project with this. 
 We used Git Hub to manage our project. There are three milestones. Each contains eight issues, and each person in our team was assigned two issues per milestone. 
</div>

<div><img class="medium" width="300" height="200" src="../images/studentaccept.PNG"></div>

<h2> Implementation </h2>
<div style="text-indent:2em">
On of the most significant work I did was to implement the login system. Companies and students use the same login option, and the system should determine the current user belongs to a company or a student and route the correct pages and components. In order to do this, I did some research about the user library of Meteor. There are several approaches. I decided to use the profile field in the user account because that field exists in every user account. If a company sign up, a messege "company" will be added into that field, while a student will be marked as "student". When a user logs in successfully, the system looks at that field and redirects the user to the corresponding page. Moerover, I needed to publish the "profile" field, so I can subscribe it in the login page. 
</div>

<h2> Conclusion </h2>
<div style="text-indent:2em">
The application has been deployed to Galaxy, but it needs some improvement. For example, the system should match students with companies based on their skills. In this project, our team applied all skills and knowledge that we had learned from ICS314 such as roject management, functional programming and design pattern. All of these helped us solve problems. Moreover, we all gained software development experience and learned how to work in a team project.
</div>

<br/>
<div>Source code: <a href="https://github.com/ho-ohui/hoohui"><i class="large github icon"></i>hoohui</a></div>
<div>Home page: <a href="https://ho-ohui.github.io/">hoohui</a></div>
