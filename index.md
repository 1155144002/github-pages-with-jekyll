---
title: "Welcome to my blog"
---

## I'm glad you are here. I plan to talk about food and drinks.
My name is Jericho.
![Profile picture](https://avatars.githubusercontent.com/u/80061077?s=400&v=4?size=50)


{% for post in site.posts %}
  <a href = "http://github.com/{{ post.title }}">{{ post.title }}</a> - {{ post.date }}\
  {{ post.content }}
{% endfor %}
