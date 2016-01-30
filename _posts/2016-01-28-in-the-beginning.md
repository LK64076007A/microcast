---
layout: post
title: In the Beginning
date: 2016-01-28 21:55:44 -0500
file: /audio/ep1.m4a
excerpt: This is the first episode. A test really. Just a proof of concept to see if this thing could be possible.
summary: This is my first attempt at a <a href="http://www.manton.org/2016/01/new-podcast-timetable.html">microcast</a>--a mini podcast--hosted completely on Github using a Jekyll generated static blog. 
duration: "3:14" #audio length in min
length: "3258374" #filesize in byte
explicit: "yes" #other option is no
block: "no" #means is shown in itunes
permalink: /1
---
{% for post in site.posts %}
{{ post.summary | xml_escape }}
{% endfor %}