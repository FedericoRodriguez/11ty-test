---
title: Hellow World
layout: 'base.njk'
---

Hello Fede!!!

{% for post in collections.post %}

- [{{post.data.title}}]({{ post.url }})

{% endfor %}
