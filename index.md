---
title: "Welcome to my blog"
---

I'm glad you are here. I plan to talk about food and drinks.

[Github](http://github.com)

{% for post in site.posts %}
  <h2>{{ post.title] }} - {{ post.date }}</h2>
  <p>{{ post.content }}</p>
{% endfor %}
