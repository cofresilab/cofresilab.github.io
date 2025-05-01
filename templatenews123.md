---
layout: page
title: News
image: 
---


{% for post in site.posts %}
<li>
{{ post.date | date: "%B %Y" }} | <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}



