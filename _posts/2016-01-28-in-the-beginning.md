---
layout: post
title: In the Beginning
date: 2016-01-28 21:55:44 -0500
file: /audio/ep1.m4a
shownotes: <p>This is my first attempt at a <a href="http://www.manton.org/2016/01/new-podcast-timetable.html">microcast</a>--a mini podcast--hosted completely on Github using a Jekyll generated static blog.</p><p><a href="https://twitter.com/LK64076007A">Contact me</a> on Twitter.</p>
summary: An explanation of what this is.
keywords: podcasting, 
duration: "3:14" #audio length in min
length: "3258374" #filesize in byte
explicit: "no" #other option is no
block: "no" #means is shown in itunes
permalink: /1
---
{% for post in site.posts %}
<audio controls>
<source src="{{site.url}}{{site.baseurl}}{{ post.file }}" type="audio/x-m4a">
Your browser does not support the audio element.
</audio>
{{ post.shownotes }}
{% endfor %}