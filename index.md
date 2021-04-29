---
title: "Welcome to my blog"
---

I'm glad you are here. I plan to talk about food and drinks.



{% for post in site.posts %}
  <a href = "http://github.com/{{ post.title }}">{ post.title }}</a> - {{ post.date }}\
  {{ post.content }}
{% endfor %}
