---
layout: default
---

# Welcome to My Blog

This website is powered by GitHub Pages and contains articles, guides, and insights
about short‑term rental management, automation, multilingual communication, and
property management workflows.

## Latest Articles
Blog posts will appear automatically once added to the `_posts` folder.

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## About This Blog
The goal of this blog is to share practical knowledge for property managers in
Europe and Ukraine, helping them improve operations and guest experience using
modern tools like PMS.Rent.
