---
layout: default
---

{% for post in site.posts %}
{% if post.categories contains "archive" %}
<ul>
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
</ul>
{% endif %}

{% endfor %}
