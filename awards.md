---
layout: default
title: Awards
permalink: /awards/
---
<!-- The following will generate a list of all your posts with clickable titles and dates -->
<h1>Awards list</h1>

**1. Quantum Communication Best Researcher Award.** Read more about [here](https://amo-physics-conferences.scifat.com/alain-giresse-tene-quantum-communication-best-researcher-award-3541).


<ul>
  {% for post in site.awards %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
      <span> - {{ post.date | date: "%B %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>

