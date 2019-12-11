---
layout: page
title: Materi
---

<ul>
	
{% for materi in site.categories.materi %}
	<li>
		<a href=" {{ materi.url | remove_first:'/' }}">{{materi.title}}</a>
		<p>{{materi.meta}}</p>
	</li>
{% endfor %}
</ul>


