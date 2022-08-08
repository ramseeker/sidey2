---
title: 2000 Hot Wheels Green Haulers Bus 1:64


layout: post
date: 2022-04-06 T03:58:00
---

A cool green dinky car.

<div class="image-gallery">
  {% for image in site.static_files %}
    {% if image.path contains '/assets/dinkyhauler' %}
     <a href="{{image.path}}">  <img src="{{ image.path  | resize: "800x800" }}"></a>

    {% endif %}
  {% endfor %}
</div>
