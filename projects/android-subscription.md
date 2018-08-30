---
layout: project
type: project
image: images/android_open.jpg
title: Subscription Manager
permalink: projects/Subscription Manager
# All dates must be YYYY-MM-DD format!
date: 2017-12-12
labels:
  - Jave
  - XML
  - SQLite
  - Android Studio
summary: Deploying an Android app helps users to manage their subscriptions.
---

<img class="ui medium rounded image" img src="../images/android_app.jpg">

<div style="text-indent:2em">
  Hulu, Netflix, Chegg... more and more subscription we subscribe recently. It is necessary to keep track how much we pay every month. In our EE396 project, my team proposed, designed and developed an Android app that manages subscriptions of users.
The app lists subscriptions, synchronizes subscription payments with Google Calendar, and keeps track of total payments.
Compared to the other apps in Play Store, it can add the subscriptions into Google Calendar.
</div>
<div style="text-indent:2em">
  The main screen of this app lists all the subscriptions and sums up the total monthly cost. User can enter subscriptions in the secondary screen. We created this app with Android Studio, and we also used the SQLite library and Google Calendar API.
All the subscriptions are shown in a ListView, and the monthly payment is shown in the right corner. User can click the existing subscription in the ListView, and the app will go to the third screen where user can update or delete the selected subscription.
</div>
<div style="text-indent:2em">
My job was to figure out how to switch in different activities and how to use the API of Google Calendar. We decided to use SQLite database to store data. Once user enter a new subscription the date and cost will be stored in the database. Every time the app switches to main screen, the listview will update the data.  
</div>

Source code: <a href="https://github.com/dawei-yang/EE396_E13"><i class="large github icon "></i>dawei-yang/EE396_E13</a>

