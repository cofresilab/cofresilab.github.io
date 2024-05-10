---
layout: page
title: News2
image: 
---


<!-- Section -->
<section>

	  
{% for post in site.posts %}

<p>

<h3><i class="fa fa-chevron-right" aria-hidden="true"></i>
		      {{ post.date | date: "%B %d %Y" }} | 
		      <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
</h3>  
<p>
 
	      
			<p>{{ post.content }}</p>
			<ul class="actions">
				<li><a href="{{ BASE_PATH }}{{ post.url }}" class="button">VIEW</a></li>
			</ul>
		<hr class="major" />
{% endfor %}		

</section>


