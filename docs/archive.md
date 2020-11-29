---
layout: default
---

{% for post in site.posts %}
{% if post.categories contains "archive" %}

<a href="{{ post.url }}">{{ post.title }}</a>
{% endif %}

{% endfor %}
