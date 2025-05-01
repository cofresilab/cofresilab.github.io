---
layout: page
title: Publications
image: 
---

{% for post in site.posts %}
<p><strong><i class="fa fa-chevron-right" aria-hidden="true"></i> {{ post.date | date: "%B %d %Y" }}</strong> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></p>

{% endfor %}
