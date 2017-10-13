---
layout: post
title: "i want to be a turtle so bad"
tag: turtle
category: turtle
comments: true
date: 2017-10-13 10:04:00
---
<div class="post-categories">
  {% if post %}
    {% assign categories = post.categories %}
  {% else %}
    {% assign categories = page.categories %}
  {% endif %}
  {% for category in categories %}
  <a href="{{site.baseurl}}/categories/#{{category|slugize}}">{{category}}</a>
  {% unless forloop.last %}&nbsp;{% endunless %}
  {% endfor %}
</div>

Turtles are so cool.
