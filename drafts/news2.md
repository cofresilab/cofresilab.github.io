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
		       
		      <a href="{{ post.date | date: "%B %d %Y" }} | {{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
</h3>  

<p>
 
	      {% if post.img %}	
	   
	          
                <img style="width: auto; height: auto;max-width: 5px;max-height: 5px">
            
            
            
	   {% endif %}	  
	      
			<p>{{ post.content }}</p>
			<ul class="actions">
				<li><a href="{{ BASE_PATH }}{{ post.url }}" class="button">VIEW</a></li>
			</ul>
		<hr class="major" />

{% endfor %}		

</section>
