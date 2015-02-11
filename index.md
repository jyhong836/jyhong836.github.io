---
layout: page
title: Hong's Blog
tagline: Less is more
---
{% include JB/setup %}

## About Me

You can find me at [GitHub](https://github.com/jyhong836), [Google+](https://plus.google.com/113310389738293078885/about), [HONG@USTC](https://jyhong.blog.ustc.edu.cn).

## Recent Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



