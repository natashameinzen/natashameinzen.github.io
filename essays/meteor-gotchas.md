---
layout: essay
type: essay
title: Meteor Gotchas
date: 2017-10-19
labels:
  - Software Engineering
  - Meteor
---


Meteor can be an extremely useful tool during the process of creating an app, linking the server to the clients. It is pre-structured, giving a very helpful starting point, but allows programmers to edit and customize their app. However, as useful as Meteor is, it does take a bit of getting used to and quite a bit of effort to understand the individual aspects of meteor and how each part works.

One problem that I have run across while using Meteor is the tendency to forget to link created files into index.js. While this step is extremely small and probably requires one of the least amounts of code, it is probably one of the most important steps in the process. Without this step, all the application is is a series of individual code snipits that fail to work together, therefore rendering it useless. Many times I have refreshed my app, just to see everything I worked on disappear for some unknown reason. After combing through lines of code, I realize that I completely overlooked the obvious- I didn't link the new files into index.js. I have tried to make it a habit that before I even write any code within a new file, as soon as I create a new directory, or file, I immediately add it to index.js. It's much better to be safe than sorry.

A second problem that I have encountered, and I still encounter, is how long it takes to set up Meteor, run Mongo, and refresh my app. I know when I begin a project or branch an existing project, I will spend at least 5 minutes setting up Meteor just to test my application. Once I know everything is running correctly, each time I type new code, or edit an existing file, it will take roughly a minute to process any changes and for them to be reflected in my app. While this isn't a huge issue, it is a time-eater, where I could have been debugging other issues instead of waiting, twidling my thumbs in the hopes that everything is working correctly. However, I have yet to find a solution that will speed up this process, and doubt there are many solutions given that many other users encounter the same problems. Furthermore, the amount of time that Meteor uses, it saves by convienence.
