---
layout: page
title: Research
permalink: /research/
---


{% for post in site.posts %}
## {{ post.title }}
<p style="color:gray;">{{ post.date | date: "%B %d, %Y" }}</p>

{{ post.content }}

<hr>
{% endfor %}
