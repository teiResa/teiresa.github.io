---
layout: page
title: Project Sites
permalink: /projects/
---

Recent blog entries:

<div class="posts">
  {% for post in site.projects %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ project.url }}">{{ project.title }}</a></h1>
      <div class="date">
        Written on {{ project.date | date: "%B %e, %Y" }}
      </div>
      <a href="{{ site.baseurl }}{{ project.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
