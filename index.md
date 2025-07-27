---
layout: home
title: Home
---

# Welcome to My Cybersecurity Blog

I'm Abraham, a cybersecurity professional sharing insights on:

- **Professional Development** - Breaking down my journey into professional cybersecurity
- **Security Tools** - Reviews and tutorials for security tools
- **Digital Privacy** - Protecting personal and organizational data
- **Research** - Original security research and findings

## Latest Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View All Posts](/blog/)