---
layout: single
title: "Weekly Updates"
permalink: /weekly-updates/
---

This page documents the weekly progress of my Fall 2026 Professional Development in Computer Science project.

## Mid-Semester Project Evaluation

As part of CSPB 3112, I completed a mid-semester evaluation of StudySync, reviewing my original project goals, development progress, and plans for the remainder of the semester.

[Read my StudySync Mid-Semester Project Update]({{ '/mid-semester-project-update/' | relative_url }})

---

## Weekly Project Updates

{% for post in site.categories.weekly-updates %}

### [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %-d, %Y" }}*

{{ post.excerpt }}

[Read full update →]({{ post.url | relative_url }})

---

{% endfor %}
