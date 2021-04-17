---
layout: home
title: 动态
category: news
description: 动态
keywords: 动态
---

<div class="row">
		<div class="col-1">
			<h2><a href="/readme.html">关于行知番茄</a></h2>
			<p>一款高效极简的番茄钟软件</p>
		</div>
	{% for page in site.tags.news %}
		<div class="col-1">
			<h2><a href="{{ post.url }}">{{ page.title }}</a></h2>
			<p>{{ page.description }}</p>
		</div>
	{% endfor %}
</div>
