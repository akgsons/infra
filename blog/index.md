---
layout: default
title: Blogs
---

{% for post in site.posts %}
* {{ post.date | date_to_string }} - [ {{ post.title }} ]( {{ post.url }} {{ post.title }} )
{% endfor %}