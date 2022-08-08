---
title: A Trip to the Aquarium
layout: post
---

Over the weekend we went to the [Niagara Falls Aquarium](https://www.aquariumofniagara.org/) because
everybody was getting just a **little bit** stir crazy as we enter the second half
of Feb. 

So, I took a few pics: 

<div class="image-gallery">
  {% for image in site.static_files %}
    {% if image.path contains '/assets/aquarium' %}
     <a href="{{image.path}}">  <img src="{{ image.path  | resize: "800x800" }}"></a>

    {% endif %}
  {% endfor %}
</div>
