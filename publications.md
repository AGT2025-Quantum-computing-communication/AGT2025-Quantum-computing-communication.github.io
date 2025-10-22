---
layout: default
title: Publications
permalink: /publications/
---
<!-- The following will generate a list of all your posts with clickable titles and dates -->
<h1>Publications list</h1>


[1. Chaos generalized synchronization of coupled Mathieu-Van der Pol and coupled Duffing-Van der Pol systems using fractional order-derivative](https://www.sciencedirect.com/science/article/pii/S0960077917300681)

<ul>
  {% for post in site.publications %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> 
      <span> - {{ post.date | date: "%B %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
