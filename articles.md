---
layout: page
title: Articles
permalink: /txts/
---

{% for post in site.posts %}
<div id="date">[{{ post.date | date_to_string }}]</div> - <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}

