---
layout: page
title: Projects
permalink: projects
---

> Shown here are some of the data analysis projects I've done, from work, Kaggle, and courses.


## Projects List

<div>
  {% for post in site.projects %}
    <div class="py-1">
      <h3>    
      <a href="{{ post.url }}">
      {{ post.title }}
      </a></h3>
      <div class="text-sm text-gray-400">{{post.description}}</div>
      <div class="text-sm text-gray-400">{{post.date | date: "%B %-d, %Y"}}</div>
    </div>
  {% endfor %}
</div>
