---
layout: page
title: Heroes of Boston
---
{% include JB/setup %}

<!--
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
-->

<div>
  <ul id="grid">
    {% for post in site.posts %}
      {% if post.image-thumb != '' %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}"><img alt="{{ post.title }}" src="{{ post.image-thumb }}" width="125" height="125" /></a></li>
      {% endif %}
    {% endfor %}
  </ul>
</div>
