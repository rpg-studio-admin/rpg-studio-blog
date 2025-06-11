---
layout: default
title: "Início"
---

Bem-vindo ao devlog do RPG Studio. Aqui você encontrará atualizações sobre o desenvolvimento da plataforma.

<hr>

## Últimas Atualizações

<div class="posts">
  {% for post in site.posts %}
    <article class="post">
      <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>
      <div class="meta">
        <span class="date">{{ post.date | date: "%d/%m/%Y" }}</span>
      </div>
      <div class="entry">
        {{ post.excerpt }}
      </div>
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Leia Mais</a>
    </article>
    <hr>
  {% endfor %}
</div>