---
layout: default
title: 吉米杂货铺
---


<ul class="bl-vernav vernav-level">
	<li>目录</li>
    {% for post in site.posts %}
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}         {{ post.date | date_to_string }}</a></li>
    {% endfor %}
</ul>
