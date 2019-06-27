---
layout: main
title: Blog
---

<h1>Blog</h1>

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a> * {{ post.date | date: "%d.%m.%y" }}</h2>
  <p>{{ post.content | strip_html | truncate: 90 }}</p>
  <hr>
{% endfor %}
