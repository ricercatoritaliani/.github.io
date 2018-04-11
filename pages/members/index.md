---
title: ARI@CH - Attività
layout: page
---

# Soci

Di seguito, la lista dei soci con il link ai profili personali.

Per i nuovi soci: alla pagina ["Come contribuire"]({{ site.url }}/pages/members/how-to-contribute.html) questa pagina potete trovare le istruzioni per collaborare allo sviluppo del sito.

---

<ul class="posts">
  {% for post in site.categories.member %}
    <li> <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> - [socio dal <span>{{ post.member-start }}</span>] </li>
  {% endfor %}
</ul>
