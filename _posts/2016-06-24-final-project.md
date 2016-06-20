---
layout: post
title: "Week 10 - Final Project"
description: Comments about the final project.
modified: 2016-06-24
category: personal
imagefeature: final.png
comments: true
---

A new programming language was introduced in the fifth week of the course. We started learning JavaScript, a language used by 92% of sites on the web. Together with JavaScript, the course introduced Jasmine as the testing framework and jQuery, a library designed to simplify the client-side scripting of HTML.

> Talk about Phaser, JavaScript, design, Waffle, Dev cycle.

You can see our work on this GitHub <a href="https://github.com/festinalent3/final-project-makers" target="_blank">repo</a>. The application has been deployed on Heroku. You can play <a href="https://makers-invaders.herokuapp.com/" target="_blank">here</a>.

These are the **skills** that I acquired after this week:

  - **Testing with Jasmine:** Write simple test for the JavaScript objects used on the application.

  - **jQuery:** I wrote some functions using jQuery in order to animate the behaviour of the game and give it some dynamism. The buttons of the game, used for selecting the number of pins knocked down, change dynamically in order to avoid wrong input from user and also provide a simpler game experience (instead of typing the number of pins on a form for example).

  - **JavaScript:** Understand some similarities and differences of JavaScript in comparison with Ruby. How to create objects (not classes) in JavaScript, what is a constuctor, why use prototypes, etc.

  - **Google chrome DevTools:** Used to efficiently track down layout issues, test JavaScript code on the console, inspect the HTTP requests of my controllers and get insights for code optimization.

  - **State machine model:** Although there are several ways to solve this challenge, I decided to base my solution on the Finite-state machine (FSM) modeling. A particular FSM is defined by a list of its states, and the triggering condition for each transition. The states represent different situations during a bowling game such as: rolling the first ball in a frame, rolling the second ball in a frame, scoring a strike, and so on. The states change from one to another by a triggering event or condition (aka transition), which in this case are the pins knocked down when rolling a ball and the possible bonus when scoring a spare or strike. 

  The image below is a state diagram for a bowling game:

  ![Diagram](http://s19.postimg.org/408xieodv/Graph.png)
