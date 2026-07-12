---
layout: default
title: Welcome to My Blog
---

# Welcome to My Blog

This blog contains articles, guides, and insights about short‑term rental management, automation, multilingual communication, and property management workflows using PMS.Rent.

## Latest Articles

Below are all published articles:

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}
---
{% endfor %}

## About This Blog

The goal of this blog is to share practical knowledge for short‑term rental managers in Europe and Ukraine, helping them improve operations and guest experience using modern tools like PMS.Rent.
