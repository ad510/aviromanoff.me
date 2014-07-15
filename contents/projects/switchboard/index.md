---
title: Switchboard
subtitle: Intuitive settings hub for Linux desktops
epoch: Winter 2011 - Summer 2012
date: 2011-5-12
external: http://elementaryos.org
launchpad: https://launchpad.net/switchboard
tech: Vala, C, GTK+, XEMBED, D-Bus, WAF, CMake
template: project.jade
---

<div class="card">
  <div class="title">What</div>
  <ul>
    <li>Identified need for coherent and cohesive app and API for exposing system configurations (e.g. device and appearance settings) on Ubuntu-based systems</li>
    <li>Created API to enable developers to build modular interfaces for easy configuration of their software and hardware peripherals</li>
    <li>Received full sponsorship (all expenses paid) to attend the 2011 Ubuntu Developer Summit in Orlando, Florida to present my work on Switchboard</li>
    <li>Switchboard has been translated into over 50 languages and currently ships with elementaryOS Luna (Ubuntu-based), which has been downloaded 475,000+ times since Spring 2012</li>
  </ul>
</div>

<div class="card">
  <div class="title">Why</div>
  <p>I have been using Linux as my desktop operating system for two years, after having migrated from Mac OS X. When I made the transition, I was frustrated by the lack of coherence and cohesion, both technically and graphically, of the system settings in Linux desktop environments. Each settings panel is typically developed individually, by different projects with different goals and user interfaces, making it cumbersome and confusing for users to change and view settings on their computers. I created a desktop-agnostic, modular, organized and friendly system to solve this ubiquitous modern Linux problem. The system is called Switchboard, and consists of a user-facing graphical interface that organizes the configuration panels installed into categories, and an API with a Vala/C/GTK+ library that enables developers to create settings panels for Switchboard. Switchboard will be included in the next version of elementaryOS (Luna), and is licensed under the GNU LGPL version 2.</p>
  <p>As a result of my involvement with elementary and my work on Switchboard, I was invited to and attended the 2011 Ubuntu Developer Summer in Orlando, Florida. I presented the software to a panel of Canonical engineers and it is being considered for adoption by Ubuntu and other free desktop projects.</p>
</div>

<div class="card">
  <div class="title">How</div>
  <p>Switchboard's API provides an elegant interface API which abstracts X11's XEMBED window embedding protocol. This enables developers writing in many languages and toolkits to embed their interface directly into the Switchboard UI. Additionally, the Switchboard API allows developers to interact with the Switchboard app itself and communicate state information such as activity progress.</p>
</div>

<div class="screenshots">
  <a href="switchboard-screenshot-1.png">
    <img src="switchboard-screenshot-1.png" class="screenshot-undersized">
  </a>
  <a href="switchboard-screenshot-1.png">
    <img src="switchboard-screenshot-2.png" class="screenshot">
</a>
<div>