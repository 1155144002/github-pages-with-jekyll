---
title: "Welcome to my blog"
---

## I'm glad you are here. I plan to talk about food and drinks.
My name is Jericho.
![Profile picture](https:github.com/1155144002.png)


{% for post in site.posts %}
  <a href = "http://github.com/{{ post.title }}">{{ post.title }}</a> - {{ post.date }}\
  {{ post.content }}
{% endfor %}
