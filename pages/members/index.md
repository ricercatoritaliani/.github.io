---
title: ARI@CH - Attività
layout: page
---

# Soci

<ul class="posts">
  {% for post in site.categories.member %}
    <li><span>{{ post.member-start }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
