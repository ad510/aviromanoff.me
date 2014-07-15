---
title: Veritas
subtitle: Social network for Harvard SSP
epoch: Summer 2012
date: 2012-7-15
external: http://veritas-me.com
github: http://github.com/aroman/veritas
tech: Python, CoffeeScript, Node.js, Backbone.js, jQuery, MongoDB, WebSockets
template: project.jade
---

<div class="card">
  <div class="title">What</div>
  <ul>
    <li>Recognized desire for the 1,000+ students attending 2012 Harvard Summer School (high school 
and college) to connect with other students for socialization and collaboration on school work</li>
    <li>Built real-time online social network with integrated group chat, featuring time-saving 
capability of automatically connecting students by class and dorm</li>
    <li>Within 4 weeks 71% of the 1000 students had signed up to use Veritas</li>
  </ul>
</div>

<div class="card">
  <div class="title">Why</div>
  <p>While studying computer science at the Harvard Summer School as a rising junior, I greatly enjoyed meeting and getting to know new students each day. However, after the first week, I realized that this strategy would not scale. Before too long, the summer would be over, and there would be many students with whom I had not connect. Therefore, I created an informal on-line social network exclusively for other Harvard Summer School students. I wrote a program to scrape the Harvard Summer School website and compile and a database of all of the courses offered that summer. Students signed up with their Harvard IDs, and selected the courses in which they were enrolled, and the dorm in which they lived. The website, which I named Veritas after the motto of Harvard, was composed of various chat rooms for these different groups, as well as a general chat for all students. I posted the link to the Facebook group for the 2012 Harvard Summer School session, and just 24 hours later over 100 had signed up.</p>
</div>

<div class="card">
  <div class="title">How</div>
  <p>Veritas's IRC-like chatrooms are powered by Socket.IO, which intelligently selects the fastest and most reliable realtime transport scheme available for a given client. Veritas's storage system strongly leverages the power of MongoDB's schemaless documents, which allows for one unified user model to adapt on the fly to the dorm and courses of each individual student &mdash; without knowledge of any other students in those groups.</p>
</div>

<div class="screenshots">
  <a href="veritas-screenshot-1.png">
    <img src="veritas-screenshot-1.png" class="screenshot">
  </a>
  <a href="veritas-screenshot-2.png">
    <img src="veritas-screenshot-2.png" class="screenshot">
  </a>
  <a href="veritas-screenshot-3.png">
    <img src="veritas-screenshot-3.png" class="screenshot">
  </a>
  <a href="veritas-screenshot-4.png">
    <img src="veritas-screenshot-4.png" class="screenshot">
  </a>
  <a href="veritas-screenshot-5.png">
    <img src="veritas-screenshot-5.png" class="screenshot">
  </a>
  <a href="veritas-screenshot-6.png">
    <img src="veritas-screenshot-6.png" class="screenshot">
  </a>
  <a href="veritas-screenshot-7.png">
    <img src="veritas-screenshot-7.png" class="screenshot">
</a>
<div>