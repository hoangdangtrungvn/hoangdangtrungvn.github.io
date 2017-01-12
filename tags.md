---
layout: page
title: Tags 
---
<div class="page-content wc-container">
	<div class="post">
		<h1>Tags</h1>  
		<ul class="sideBarTags">
			{% assign tags = (site.tags | sort:0) %}
			{% for tag in tags %}
				<li><a href="{{site.baseurl}}/tag/{{ tag[0] }}" data-toggle="tooltip" data-placement="right" title="{{ tag[1].size }}">{{ tag[0] }}</a></li>
			{% endfor %}
		</ul>
	</div>
</div>