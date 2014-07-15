---
title: Centropa
subtitle: Real-time sign in map for exhibit visitors
epoch: Fall 2010
date: 2010-9-1
tech: Python, JavaScript, WebPy, PyGTK, AJAX, JSON, Google Maps API
template: project.jade
---

<div class="card">
  <div class="title">Why</div>
  <p>In my freshman year of high school my grade organized and ran an exhibit on pre- World War II Jewish life in Europe, as a part of the international organization Centropa. My part in the exhibit was the creation of a digital sign-in book and projected map that allows the visitors to type in their name and ancestor's country of origin, and have their location marked on a digitally projected map of the world. I collaborated on this project with a classmate.</p>
</div>

<div class="card">
  <div class="title">How</div>
  <p>This project was comprised of two separate components which communicated through a RESTful HTTP API server backend. The first was a fullscreen GTK+ app which captured sign in data (when typed in via my laptop running the program). The second was a fullscreen web page projected on a wall which displayed a map of the world and dropped pins whenever a new sign in was pushed to it by the backend server.</p>
</div>