layout: page
title: "PAGE TITLE"
permalink: /about/


てすと 


<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>