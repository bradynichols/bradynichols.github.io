---
layout: default
title: Blog
order: 3
---

Here I intend to post a mix of writings and any relevant updates on my scientific career.

<h1>Latest Posts</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>