---
title: Kinsmart 1950 Suburban Schoolbus
layout: post
---

[Shop for Kinsmart Plastic Buses on Amazon](https://amzn.to/3CJHYtK)

<div class="image-gallery">
  {% for image in site.static_files %}
    {% if image.path contains '/assets/kinsmartbus' %}
     <a href="{{image.path}}">  <img src="{{ image.path  | resize: "800x800" }}"></a>

    {% endif %}
  {% endfor %}
</div>

