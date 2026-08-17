---
layout: home
title: Home
---

# Welcome to My Cybersecurity Blog

I'm Abraham, a cybersecurity professional sharing my thoughts on:
- **Professional Development** - Breaking down my journey into professional cybersecurity
- **Cyber Self-Defense** - Tips and Guidance for all levels of technology users on maintaining digital privacy and security
- **Security Tools** - Reviews and tutorials for security tools

I believe that cybersecurity is a fundamental skill to those who wish to leverage any and all information technology from radio to Large Language Models... Unless you're fully off the grid, your life is inherently affected by technology. We must embrace this if we want a secure future; willful ignorance is still an option, it's just a very poor one. 

More [About Me](/about/)

## Latest Posts

<div class="post-list post-list--compact">
{% for post in site.posts limit:5 %}
  <a class="post-row" href="{{ post.url }}">
    <span class="post-row-title">{{ post.title }}</span>
    <span class="post-row-meta">{% if post.area %}{{ post.area }} &middot; {% endif %}{{ post.date | date: "%b %d, %Y" }}</span>
  </a>
{% endfor %}
</div>

<a class="btn" href="{{ '/blog/' | relative_url }}">View All Posts</a>