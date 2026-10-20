---
layout: page
title: Blog
permalink: /blog/
---

# All Posts

<div class="post-list">
{% for post in site.posts %}
  <article class="post-card">
    <h2 class="post-card-title"><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <div class="post-meta">
      <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
      {% if post.area %}<span class="post-area">{{ post.area }}</span>{% endif %}
    </div>
    <div class="post-excerpt">{{ post.excerpt }}</div>
    <a class="read-more" href="{{ post.url }}">Read More &rarr;</a>
  </article>
{% endfor %}
</div>