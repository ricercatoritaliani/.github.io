---
title: ARI@CH - Associazione Ricercatrici e Ricercatori Italiani in Svizzera
navigation_weight: 1
author: Riccardo Maria Bianchi
layout: default
pagination:
  enabled: true
---

L' *"Associazione Ricercatrici e Ricercatori Italiani in Svizzera"* (**ARI@CH**) promuove, valorizza e sostiene l'attività dei **ricercatori italiani** operanti nelle Università o negli Istituti e nei Centri di Ricerca, pubblici e privati, ubicati **in Svizzera**.

Ulteriori informazioni sull'associazione possono essere trovate nella sezione [Chi siamo]({{ site.url }}/pages/about/).

Il calendario delle attività, promosse dai Soci, è pubblicato sul sito, nella sezione [Attività]({{ site.url }}/pages/activities).

# News

<div id="home">
  <ul class="posts">
    {% for post in site.categories.news %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>
