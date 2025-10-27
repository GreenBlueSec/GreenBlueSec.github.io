---
layout: home
title: Home
---

# Welcome to My Cybersecurity Blog

I'm Abraham, a cybersecurity professional sharing my thoughts on:
- **Professional Development** - Breaking down my journey into professional cybersecurity
- **Cyber Self-Defense** - Tips and Guidance for all levels of technology users on maintaining digital privacy and security
- **Security Tools** - Reviews and tutorials for security tools
I believe that cybersecurity is a fundamental skill to those who which to leverage any and all information technology from radio to Large Language Models... Unless you're fully off the grid, your life is inherently affected by technology. We must embrace this if we want a secure future; willful ignorance is still an option, it's just a very poor one. 

More [About Me](/about.md/)

## Latest Posts

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }}) - {{ post.area }} - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

[View All Posts](/blog/)