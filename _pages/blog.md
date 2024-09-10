---
title: "Blog"
permalink: /blog/
layout: single
entries_layout: grid
author_profile: true
classes: wide
---

<div class="posts-grid">
  {% for post in site.posts %}
    {% include archive-single.html %}
  {% endfor %}
</div>