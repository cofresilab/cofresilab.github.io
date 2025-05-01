---
layout: page
title: News
image: 
---

{% for post in site.posts %}
<span class="opener">{{ post.date | date: "%B %d %Y" }}</span>
{{ post.title }}

{% endfor %}
