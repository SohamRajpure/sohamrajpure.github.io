---
layout: page
title: Writing
permalink: /blog/
---

<div class="posts-list-page">
  {% for post in site.posts %}
  <a href="{{ site.baseurl }}{{ post.url }}" class="post-item">
    <span class="post-item-title">{{ post.title }}</span>
    <span class="post-item-date">{{ post.date | date: "%B %e, %Y" }}</span>
  </a>
  {% endfor %}
</div>
