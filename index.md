---
layout: default
title: Home
---

# Welcome to My Jekyll Website

Hello! This is a simple Jekyll website to help you get started. 

## Recent Posts

{% for post in site.posts limit:3 %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
    <small>{{ post.date | date_to_string }}</small>
  </article>
{% endfor %}
