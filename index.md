---
title: "Welcome to my blog"
---

I'm glad you are here. I plan to talk about food and drinks.

[Github](http://github.com)

{% for post in site.posts %}
  {{ [post.title](http://github.com) }} - {{post.date }}
  <p>{{ post.content }}</p>
{% endfor %}
