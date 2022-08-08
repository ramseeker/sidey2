---
title: Blue Bird Bus Piggy Bank
layout: post
date: 2022-04-21 T13:15:00
link: https://amzn.to/3p291e0

---

You never know what this stuff goes for. It's a [plastic piggy bank](https://www.ebay.com/sch/i.html?_from=R40&_trksid=p2380057.m570.l1313&_nkw=bus+piggy+bank&_sacat=0&mkcid=1&mkrid=711-53200-19255-0&siteid=0&campid=5338921011&toolid=11800&mkevt=1) and yet sold for over $26.51. Go figure.


<div class="image-gallery">
  {% for image in site.static_files %}
    {% if image.path contains '/assets/bluebirdbank' %}
     <a href="{{image.path}}">  <img src="{{ image.path  | resize: "800x800" }}"></a>
{% endif %}
  {% endfor %}
</div>
