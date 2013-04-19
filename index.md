---
layout: page
title: Heroes of Boston
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

If you'd like to help please contribute to hero profiles at [GitHub repository](http://github.com/{{ site.author.github }}).
