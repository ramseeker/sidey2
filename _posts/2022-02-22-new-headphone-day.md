---
Title: New Headphone Day
layout: post
---

I slipped by the [Goodwill](http://goodwill.com) the other day to drop off some stuff and of course **after** I had dropped off the stuff
I had to go look and see if there was more crap to bring back. :)

Turns out there was and I snagged these [kids headphones](https://amzn.to/3h66L1p) for two bucks. I have to tell you that this might be the
best two dollars ever spent becuase now I **don't have to listen to [cocomelon]( https://amzn.to/3h6Jhca) ad nauseum.** I don't know what it is with this show
but it seems that **every todddler** knows it and **loves it**

At least, mine does.

<div class="image-gallery">
  {% for image in site.static_files %}
    {% if image.path contains '/assets/kidphones' %}
     <a href="{{image.path}}">  <img src="{{ image.path  | resize: "800x800" }}"></a>

    {% endif %}
  {% endfor %}
</div>

