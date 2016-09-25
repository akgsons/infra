---
layout: default
title: Blogs
---

<br/>
## {{page.title}}
---

{% for post in site.posts %}
* {{ post.date | date_to_string }} - [ {{ post.title }} ]( {{ post.url }} {{ post.title }} )
{% endfor %}