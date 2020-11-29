---
layout: default
---


{% for post in site.posts %}
{% if post.categories contains "information" %}
<ul>
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
</ul>
{% endif %}

{% endfor %}
