---
layout: post
title: JavaScript Crash Course
permalink: /javascript-crash-course/
isStaticPost: true
---
<img class="img-responsive feature-image" src="{{ site.baseurl }}/img/posts/js-bg.jpg" style="display:none">
### Advanced

Welcome to Women Techmakers Berlin's Advanced JavaScript winter course!

The course will spread over 5 lectures during March through May, where we will dive deeper in JS, following our last year's Beginners course. If you missed it - you can catch up, as all of our talks are available below.
You are also welcome to join the JS channel in the Women Techmakers Berlin Slack (invite can be found in our meetup pages), and ask your questions - to catch up on last year's material, or to ask question from the latest lecture.
This year we will keep uploading lectures, so don't worry if you have to miss one.

In addition to the lectures, we will meet to hack on our projects on a bi-weekly basis, just you, your project, the instructors and a whole-lotta-mate!


##### Lecture 1: Design Patterns
An introduction to popular software design patterns and how they can be utilized with JavaScript. In this session, we talk about what a design pattern is, what anti-patterns are, how they emerge and when to make use of one. We talk about some of the Gang of Four patterns and their applications.

##### Lecture 2: Authentication and Middleware
Most web applications rely on user accounts and interaction. In this session we will talk about building user accounts, authentication with username and password, and see an example “log in with Facebook” implementation. We will also go over the concept of middleware in Express and see how we can utilize it for various purposes.

##### Lecture 3: Bridging APIs
A web application of any complexity makes use of multiple 3rd party APIs, whether it’s a stock exchange ticker, a weather app, a news aggregator or something that interacts with storage services to store user data. In this session we will talk about modular applications and making use of existing APIs to grow the capabilities of our application.

##### Lecture 4: The Frontend
It’s time to give our application a real face. In this session we will go over the best practices of frontend engineering and building user interface applications. We will look at Vue.js, talk about its features and capabilities, and build a simple frontend with it.

##### Lecture 5: Advanced Database Constructs
There is a lot more than meets the eye when it comes to databases. In this talk we will briefly look at concepts like CAP theorem, ACID, and see how MongoDB operates under these. We will also see advanced query constructs in MongoDB with aggregate queries for reporting and analytics and other features like full text search and geolocation queries.


### Beginner

This is a course designed for introducing JavaScript and Node.js as a platform for backend applications. It assumes that you know basic concepts of (object oriented) programming but we will start from the beginner level and build up. So, the more programming experience, the better — but total newbies are also welcome, provided that they invest the required amount of time for self-learning.

The course is designed around open-source technologies, so a Unix-like system, Linux or MacOS is preferred. Git and Visual Studio Code will be our main tools, along with Node.js. Windows is not preferred, but if you absolutely have to live on Windows, you should have a working git and Node.js installation, and the rest will work.

In the end we expect to come up with a simple backend application that gets deployed with Docker and provides a REST API before a MongoDB datastore. This will not be an easy task, but we are committed to get every attendee on this level :)

Finally, this is a challenging, intensive, but fun and resourceful course. We will strive to do better each and every week. It won’t be a bed of roses, but it will provide immense learning opportunities.

We also have a dedicated Slack channel (#js-crash-course) in the [WTM Slack](https://womentechmakersberlin.slack.com/) to help out the attendees with their assignments outside the class hours. An invite link to our Slack can be found in each of the meetup events.

During the meetings a group of volunteers will be around to answer your questions.
Additionally, all our volunteers are online on Slack to answer your questions, in addition to several online-only volunteers. You'll spot them easily - they have a red cross helmet emoji as part of their names.

Additionally, all talks are recorded and uploaded to YouTube. This is done with the purpose to help all those who want to take our course and can't attend one meeting (e.g. if you caught a cold) or any meeting (e.g.  if you have to babysit). If you will watch all talks, live or online, and present a satisfying final project - you will get the graduation certificate.

#### Syllabus

##### Lecture 1: JavaScript & ES6 Fundamentals

An introduction on how JavaScript works and how to take advantage of the new ES6 syntax and features. In this session, we cover the basic programming paradigms in JavaScript, as well as topics like OOP and functional programming. We use the Chrome browser as a playground for an interactive session.

[Recorded talk](https://youtu.be/xgzHW_WqYnM)

###### Lecture 2: Node.js Ecosystem & Basics

A fast dive into the Node.js ecosystem, detailing its working principles. A brief intro to its implementation and moving on to making use of and creating modules. Demonstration of the previous JavaScript and ES6 fundamentals, delving into the module pattern and several examples to familiarize with npm packages. We also talk about interacting with the file system. Useful tools like PM2 and nodemon are introduced in this session, as well as live debugging with Node.js. We use Visual Studio Code as the IDE of choice.

[Recorded talk](https://youtu.be/MP0wROOhyH8)

###### Lecture 3: Promises and Async Programming

This session focuses on solving the challenges of asynchronous programming with certain constructs in Node.js — promises, async and await keywords. We discuss how each implementation enables a certain way of programming, and introduce a control flow library called async. We also touch upon streams and stream programming.

[Recorded talk](https://youtu.be/RH_lwP-mjVM)

###### Lecture 4: HTTP APIs with Express.js

An introduction to web applications with the express framework and most popular packages including sessions and authentication, as well middleware implementations. We go into the details of HTTP and talk about RESTful APIs. We start implementing an example back-end application with express. We briefly talk about real-time capabilities with WebSockets.

[Recorded talk](https://www.youtube.com/watch?v=ofQu4y-5v6c)

###### Lecture 5: Adding a MongoDB Datastore

This session improves on the previous express application and introduces a MongoDB database as the datastore. We look into mongoose ODM and how to model simple data structures in MongoDB. We also talk about database denormalization approaches MongoDB enables. Further experiments with MongoDB queries and wiring the REST endpoints of the express app to real data.

[Recorded talk](https://www.youtube.com/watch?v=EYYO4Le8bWQ)

###### Lecture 6: Hands-on Session

This session is fully hands on. Work on your project, ask for help with your work or for clarifications on our past materials. Let's get those websites to life!



###### Lecture 7: Testing

This session focuses on testing Node.js applications and the APIs that we have developed. We talk about general best practices in testing software, and several layers of application testing including unit testing, integration testing and acceptance testing. We implement several tests for our APIs with the test runner [AVA](https://github.com/avajs/ava).

[Recorded talk](https://www.youtube.com/watch?v=NXMwf2OSVWQ)

###### Lecture 8: Deploying & Scaling Apps with Docker

The final session in this series introduces the final step in an application's lifecycle — the deployment. We learn the basics of Docker and how to deploy our Node.js applications with Docker. We introduce the concepts of continuous integration and continuous deployment, as well as automated testing. This session also includes scaling Node.js applications with load balancers and a reverse proxy setup with nginx.

[Recorded talk](https://youtu.be/R2eYylz41Gg)

###### Lecture 9: Graduation Event

We will gather to hear the talk "JavaScript is a Buffet, not a Main Course" by [Chris Heilamnn](http://christianheilmann.com/), see the final projects and cheer our classmates!

See the [graduation event pictures](https://www.facebook.com/pg/WomenTechmakersBerlinPage/photos/?tab=album&album_id=1561335890621986)


Talk Description: 
Now that you learned about JavaScript, you're ready to take on the world as JavaScript runs everywhere. The trick is to not get overwhelmed and to find what makes you happy as happy developers are effective developers. 

Chris Heilmann has a 18 year old history of using the language and wrote many books about it. Let him help you not get lost in the rabbit hole that is JavaScript in 2017.

Read about the talk: [So, you learned JavaScript – what now?](https://christianheilmann.com/2017/12/05/so-you-learned-javascript-what-now/)


#### How to join

Sign up on [Meetup.com](https://www.meetup.com/Women-Techmakers-Berlin/events/).
Please be aware you'll be required to attend at least 80% of the classes to successfully complete the course.

#### Diversity and Code of Conduct

Our mission is that everyone feels welcome to our events no matter gender or 
nationality, take their first steps in tech and be part of our local community.

We strictly follow the [Berlin Code Of Conduct](http://berlincodeofconduct.org/) 
and we don’t tolerate any kind of bad behaviour as defined by the code of conduct.

#### Location

Le Wagon Berlin

Rudi-Dutschke-Str. 26, 10969 Berlin

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2428.4558104670805!2d13.389230816210418!3d52.50708967981181!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47a851d150f75b59%3A0x79345cc8e68056cc!2sLe+Wagon+Berlin+Coding+Bootcamp!5e0!3m2!1sen!2sde!4v1520287959707" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

#### Communication

Join the [Women Techmakers Berlin Slack](https://join.slack.com/t/womentechmakersberlin/shared_invite/enQtMjQ1ODcwNTIyMTAxLTY1NmVjMGQzOTgxNmI0ZWUwYWNlNDg0MjkyYjEwNDY5ZjVlMzU1ZDZlMjc1MGUzNzRhZWM3YzYxMDVmNWYzNjQ).

Join the #js-crash-course channel.

#### FAQ for Students

**Do I need programming knowledge to attend the Advanced course?**

Some previous programming knowledge would be really useful.

**Do I need to attend to all the sessions?**

We require at least attending at least 80% of the classes.

**Do I need to present a final project for graduation?**

Yes, presenting your project at the closing event is required to get the certificate of completion.

**I skipped some lessons and I am lost. Can I still come to the events?**

Ping the coaches on Slack, who can help you plan your catching up.

**How many hours do I need to study each week?**

Ideally you'll keep working on your project at home. We recommend investing about 3 hours a week in order to complete the whole course and do the project. 

**Do I need to prepare the sessions at home?**

Yes, it is recommended that the students will review the recently taught material before each class.

**Who can attend?**

All genders are welcome.

**How do I RSVP for each lesson?**

RSVP opens for the next Meetup one week in advance, and you can RSVP during class.

**Will food be provided?**

There will be drinks and snacks.

