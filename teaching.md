---
layout: default
title: Teaching
---

<div>
<h1>Teaching</h1>
<p>I was a teaching assistant for the following courses at the Department of Computer Science of the Athens University of Economics and Business. My responsibilities included the preparation and teaching of weekly lab sessions, grading of homework / exams, as well as holding regular office hours. I have also given a number of lectures for some of the courses.</p>
<h4><strong>Athens University of Economics and Business (2013 - 2019)</strong></h4>

{% for item in site.data.courses %}

   <span>{{ item.period }}</span>
   <ul>
   <li>
   {{ item.name }}
   </li>
   </ul>
   {% endfor %}

</div>