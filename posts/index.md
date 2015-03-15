---
layout: default
title: Blog posts
---
{% for post in site.posts %}
<h2><a href="{{ post.url }}">{{ post.title }}</a><small> {{ post.date | date_to_string }}</small></h2>
{% endfor %}
