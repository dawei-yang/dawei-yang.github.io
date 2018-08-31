---
layout: project
type: project
image: images/pacman_open.jpg
title: Pacman
permalink: projects/Pacman
# All dates must be YYYY-MM-DD format!
date: 2017-12-15
labels:
  - C#
  - Unity
summary:  Recreating game Pacman with Unity and C#.
---
<div >
  <img class="center rounded" src="../images/pacman.jpg">
</div>

<div style="text-indent:2em">
  As a final project of a game design course, our team decided to create a clone of the popular arcade game, Pacman. In this game, player spawns as Pacman in a maze with 4 different ghosts: Blinky, Inky, Pinky, and Clyde. The objective of the game is to collect all of the “dots” that are scattered throughout the entire maze while avoiding the ghosts. If one of the ghosts touches the Pacman, he’ll die, respawn, and one of his lives will be deducted from his total life count. If Pacman’s total life count reaches 0, the game is over. Special dots, when collected, will trigger special events such as freezes the ghosts. Every collectible in the game provides a different score value that is added to your total score upon collection.
</div>
<div style="text-indent:2em">
   We made this game in Unity, and the codes were written in C#. My job was to implement the trigger event system and the scene manage system. When an event is triggered the system will call multiple methods. For example, when Pacman eats a blue dot, all the ghosts will be freezed and turn blue. Moreover, a method will be called to recover the state of ghosts after a certain time. One of the best way to handle trigger events is to use delegates and events. I also used the labeling API to change the tags of game objects, so we could control the game objects efficiently . The biggest challenge of this project was to merge all works that were made by different people together. We attached the event trigger system in a singleton object, main camera in this case, so that everyone can raise events thru the camera.
</div>
<div>
<br/ br/>
Source code: <a href="https://github.com/dawei-yang/Pacman"><i class="large github icon "></i>dawei-yang/Pacman</a>
</div>
