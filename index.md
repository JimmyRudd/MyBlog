---
layout: default
title: 吉米杂货铺
---


<ul class="bl-vernav vernav-level">
	<li>目录</li>
    {% for post in site.posts %}
      <li>{{ post.date | date_to_string }} <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
