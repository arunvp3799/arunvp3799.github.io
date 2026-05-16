---
permalink: /blog/
title: "Blog"
layout: archive
author_profile: true
---

Thoughts on AI, machine learning, data engineering, and things I find interesting.

{% assign posts = site.posts %}
{% assign entries_layout = page.entries_layout | default: 'list' %}

<div class="entries-{{ entries_layout }}">
  {% for post in posts %}
    {% include archive-single.html type=entries_layout %}
  {% endfor %}
</div>
