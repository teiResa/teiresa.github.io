---
layout: page
title: Digital Sketchbook
permalink: /sketchbook/
---

### Welcome to my gallery
 Here we have a selection of my experiments in digital art. I am currently
 still learning basics, and have no scanner. Everything on here was more to
 satisfy my own curiosity than to show off.

<div class="posts">
  {% for post in site.art %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ art.url }}">{{ art.title }}</a></h1>

      <div class="entry">
        {{ art.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ art.url }}" class="read-more">See More</a>
    </article>
  {% endfor %}
</div>
