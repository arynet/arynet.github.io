---
layout: page
title: Blog
permalink: /blog/
---

<ul class="list-unstyled">
  <li>{{ post.title }}</li>
</ul>

<ul class="list-unstyled postss">
	{% for post in site.posts %}  
	   <li>  
		   <bd>{{ post.date | date_to_string }}</bd>
		   <a href="{{ BASE_PATH }}{{ post.url }}">  
		   <h4>{{ post.title }}</h4></a> 
	   </li>  
	{% endfor %}  
</ul>