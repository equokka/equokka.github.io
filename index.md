---
layout: main
---

Welcome, <span style="color:#000000;background:#8bfc14">STRANGER</span>

Latest blog posts:
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url }}">{{ post.title }}</a> * {{ post.date | date: "%d.%m.%y" }}</li>
  {% endfor %}
</ul>
