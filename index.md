---
title: "Welcome to my blog"
---

## I'm glad you are here. I plan to talk about food and drinks.
My name is Jericho.
<img src ="https://avatars.githubusercontent.com/u/80061077?s=60&v=4" width="100")


{% for post in site.posts %}
  <a href = "http://github.com/{{ post.title }}">{{ post.title }}</a> - {{ post.date }}\
  {{ post.content }}
{% endfor %}
