---
layout: page
title: Hello World!
tagline: github powered blog
---
{% include JB/setup %}



## Hello World

I am blogging after a long time, first post I want to write is on how I setup my new macbook pro



    
## Sample Posts



<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

* apply a template
* write posts


