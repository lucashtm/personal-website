---
layout: page
title: Categories
---

<h1 class="categories-title">Categories</h1>
<div class="categories-list">
	{% for category in site.categories %}
		{% capture category_name %}{{ category | first }}{% endcapture %}
		<a class="category-link" href="#{{ category_name }}">{{ category_name }}</a>
	{% endfor %}
</div>

<div class="categories">
	{% for category in site.categories %}
		{% capture category_name %}{{ category | first }}{% endcapture %}
		<h3>{{ category_name }}</h3>
		<ul id="{{ category_name }}">
			{% for post in site.categories[category_name] %}
				<li class="post-short">
		      <a href="{{ site.baseurl | append: post.url }}"><h3>{{ post.title }}</h3></a>
		      <p class="date">{{ post.date | date_to_string }} <span class="reading-time"> - 2 minutes to read</span></p>
		    </li>
			{% endfor %}
		</ul>
	{% endfor %}
</div>