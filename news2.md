---
layout: page
title: News2
image: 
---


<!-- Section -->
<section>

	  
{% for post in site.posts %}
<p> <i class="fa fa-chevron-right" aria-hidden="true"></i>
		      <h4>{{ post.date | date: "%B %d %Y" }}</h4> 
		      <h2><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h2>  <p>
 
	      
			<p>{{ post.content }}</p>
			<ul class="actions">
				<li><a href="{{ BASE_PATH }}{{ post.url }}" class="button">VIEW</a></li>
			</ul>
		</article>
		<hr class="major" />
{% endfor %}		

</section>



