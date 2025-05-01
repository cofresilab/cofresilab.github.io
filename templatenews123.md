---
layout: page
title: News
image: 
---
<nav id="menu">
<ul>

{% for post in site.posts %}
<li>
<span class="opener">{{ post.date | date: "%B %d %Y" }}</span>
<li> {{ post.title }} </li>
</li>
{% endfor %}
</ul>
</nav>


