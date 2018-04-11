---
title: ARI@CH - Attività
layout: page
---

# Attività

<ul class="posts">
  {% for post in site.categories.activity %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
