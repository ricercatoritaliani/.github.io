---
title: ARI@CH - Attività
layout: page
---

# Soci

<ul class="posts">
  {% for post in site.categories.member %}
    <li> <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> - [socio dal <span>{{ post.member-start }}</span>] </li>
  {% endfor %}
</ul>
