---
layout: default
title: Posts
---
<h2>{{ page.title }}</h2>
<ul class="listpost">
  {% for post in site.posts %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>