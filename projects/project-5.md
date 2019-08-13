---
layout: project
type: project
image: images/welcome-website.PNG
title: Website Design
permalink: projects/Website Design
date: 2019
labels:
  - Network Programming
  - dynamic HTML
  - Web Architecture
  - Client and Server side programming
  - Javascript
  - CSS
  - jQuery
  - Express
  - Node.js
  - XML
  - Database
  - API
summary: Used web architecture and protocols to create a web application on both the server-side and client-side. Full stack web development.

---


<img src="/images/distance.PNG"  style="width: 100%;">
<img src="/images/form-map.PNG"  style="width: 100%;">
<img src="/images/schedule.PNG"  style="width: 100%;">
<img src="/images/widget.PNG"  style="width: 100%;">












The purpose of this project was to create a full-stack website from both the client side to the server side. While the website itself is visually simple, many different coding languages and techniques were used in it's creation.

Beginning with the client side, 3 main pages were created: A widget page, schedule page, and form input page. The widget page had 3 main components: an instagram widget, and twitter stream, and a password validator. CSS was used to display each page and was implemented by inline, embedded, and external page techniques. Each page displayed a navigation bar containing hyperlinks that allowed users to switch pages.

The password validator let a user type in a password and it then displayed the strength of the password by a colored scale. The validator was implemented in two different ways, one using javascript and the other using jQuery.

The schedule page also had three main componenets: the actual schedule, a picture slideshow, and a map. All the schedule entries were saved in a database. When the page loaded, the database was accessed, the schedule table dynamically created, and displayed as can be seen in the picture. The events in the schedule each contain location hyperlinks and a thumbnail picture of the location, which are also displayed in a slideshow to the right of the schedule. Below the schedule and slideshow is a Google Map with a distance form. The map is automatically populated with markers that correspond to locations in the schedule. In the form, the user can enter two locations, the method of how they would like to get to said location, and the method of measurement (miles, kilometers, etc). When they click 'Go' the map will then show the distance between the locations with the given specifications as well as display the directions, which uses Google Map APIs to obtain that information. Finally, the entire page can be translated to any other language using a Google Translate API.

The form input page allows a user to add an event to their schedule. It allows users to input Day, Timing, Name, Location, and URL to the event. The user can use the map to the right of the form to select a location and URL, which automatically populates the form when a location is selected. When the user clicks 'Submit', the form performs basic validation on the form: if certain fields are alphanumeric, if all input fields are filled out, and date/time ranges are possible, etc. Once the entire form has been validated, the event is pushed into the schedule database, a success message is displayed, and the page is rerouted.

The server-side that enables the client side to perform seamlessly was implemented in two ways: HTTP protocol and Express (Node.js). When started, both established a socket and bound to a port to allow communication. They allowed the client to communicate with the server using GET and POST requests, had the server handle each request, and returned the appropriate response to the client. It also used SQL/MYSQL to create, push to, and pull from the schedule database. Furthermore, a simple admin page was added to the client side. It allowed the server to allow login (using a separate user database) and establish sessions for each users.


the UStudy application was to create an application that was not yet in existence that would help students at the University of Minnesota using User Interface and Design practices. To begin the process, my teammembers and I brainstormed various app ideas. After much deliberation, we settled upon an app that helped students find and form study groups. Once the idea was formed, we each performed a series of interviews on a diverse set of students to better understand what they felt would be beneficial to see in an app. We analyzed the transcripts from all of the interviews and found 5 main implications that our application must meet.

<img src="/images/ustudy goals and implications.PNG" style="float: right; width: 50%; margin-right: 1%; margin-bottom: .6em;" >

Once our implications were set, we began the ideation process. During this time, we proposed over 100 different ideas that our app should contain that met those 5 implications. We then grouped those ideas into categories, including, but not limited to, Features, Study Times/Locations, Security, and Group Dynamics. In pursuit of these qualities, we determined UStudy will offer UMN students the ability to form study groups in-app, and to communicate with all the standard features of a messaging service. Students and study groups will be able to use the app to find nearby study locations; they may then schedule events and meetings at these locations at times that work for them. UStudy users will be able to control which aspects of their personal information they share with others through the app, to ensure that their privacy and comfort are maintained.

<img src="/images/ustudy ideation.PNG" style="float: left; width: 50%; margin-left: 1%; margin-right: 1%; margin-bottom: .8em;" >

The next step of our process was to actually create the application. We first created a POP, which allows hand-drawn sketches to be turned into interactive protoypes. This allowed us to have a better grasp on how the entire application would come together and made us aware of what pieces we were missing. Once our POP was complete and we included everything that met the features and implications above, we began coding the application using Android Studio. Using the POP, we delegated certain features and pages to each teammember to complete within a designated timeline. 

Finally, in order to understand the strengths and weaknesses of our completed application, we had another diverse set of University of Minnestoa students use our apps and collected feedback. We asked them to perform both "think aloud" walk throughs as well as summative tasks to obtain time-to-complete-a-task data, misstep data, and overall feedback. From those analytics, we were able to determine futuristic modifications to the User Interface Design to better the application.

<img src="/images/ustudy quantitative data.PNG"  style="width: 100%;">

