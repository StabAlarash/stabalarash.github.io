---
layout: page
title: Projects
permalink: /projects/
---
Here's a list of my projects:

<div class ="image-gallery">
  {% for project in site.projects %}
    <div class="box">
      <a href="{{ project.url }}" title="{{ project.title }}">
        <img src="{{project.image | absolute_url }} " class="img-gallery" />
      </a>
      <h4>{{ project.title }}</h4>
      <h5>{{ project.description }}</h5>
    </div>
  {% endfor %}
 </div>
