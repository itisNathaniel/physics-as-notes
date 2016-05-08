---
layout: page
title: Practicals
permalink: /requiredpracticals/
---
All required practicals

{% assign sorted_threat_posts = site.categories.practical | sort: 'title', 'last' %}
{% for post in sorted_threat_posts %}
   <li style="list-style-type: none;"><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}