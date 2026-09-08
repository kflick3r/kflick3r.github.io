---
layout: single
title: "Weekly Updates"
permalink: /weekly-updates/
---

This page documents the weekly progress of my Fall 2026 Professional Development in Computer Science project.

{% assign updates = site.categories["weekly-updates"] %}

{% for post in updates %}
## [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %-d, %Y" }}*

{{ post.excerpt }}

[Read full update →]({{ post.url | relative_url }})

---
{% endfor %}