# debian.js
a debian strech respin , with a bunch of added tools that make it a JavaScript Centric OS. 

why use respin?
===============

solo project, time and investment. there are other things I want to focus on, rather than build tools, and compile time. Fast iteration, I'll release the respins in 32 and 64bit, and provide all the configuration information / automation scripts as current source.

what does debian.js do?
=======================

debian.js is simply a respin of debian strech, that leans heavily on the latest node.js to complete a varity of all tasks in the operating system. Using webkit through the nw.js project, and leveraging the customizable and ultra fast fvwm, the goal is to create the entire desktop experiance as a set of HTML5 applications.

how is this different than project x?
=====================================

debian.js is a full throwback to it's trunk. it is completely compatible, and entierly stock base OS debian. debian.js utilizes xorg (wayland planned in the future) alongsind fvwm. While debian.js creates a lot of the desktop you interact with inside the browser, debian.js does not lean on the webstack to manage the placement, composition, and managment of the windows. debian.js can run on machines with as little as 256Mb of ram and no hardware acceleration. Another distingushing feature at the moment, debian.js uses nodejs and webkit as it's heart.

I liked chromeOS a lot, it was too restrictive. While I was configuring my own build, I thought I would give a crack at creating a few of the every day tools I needed in HTML5, and obviously this is Linux so I'm doing it just a little bit different than those on the scene already. My main inspiration are SymphonyOS and OS.js and obviously chromeOS/JoliCloud. I'm also a big fan of the debian ecosystem.

list of added packages
======================

starting with a base of debian strech netinstall for chosen architecture:

global npm packages:

* nw

global apt packages:

* xorg
* fvwm
* nodejs
* libnss3
* libconf-2-4
* atk1.0
* libxss
* libexif-gtk5
* atk1.0
* libgtk2.0-0
* libcups2
* libsound2
