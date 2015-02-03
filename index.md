---
layout: page
title: Hong's Blog
tagline: Less is more
---
{% include JB/setup %}

The site is based on Jekyll.

## Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



