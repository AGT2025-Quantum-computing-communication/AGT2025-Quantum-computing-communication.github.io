---
layout: default
title: Scholarships
permalink: /scholarships/
---
<!-- The following will generate a list of all your posts with clickable titles and dates -->
<h1>Scholarships</h1>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
      <span> - {{ post.date | date: "%B %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
