---
layout: page
title: Blog
permalink: /blog/
---
<p>Read the latest updates, release notes, and behind-the-scenes stories.</p>
<ul class="post-list">
  {% assign all_posts = site.posts | sort: 'date' | reverse %}
  {% for post in all_posts %}
  <li>
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: '%B %d, %Y' }}{% if post.author %} • {{ post.author }}{% endif %}</p>
    <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
  </li>
  {% endfor %}
</ul>

