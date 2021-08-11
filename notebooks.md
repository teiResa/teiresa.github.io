---
layout: page
title: Notebooks
permalink: /notebooks/
---

<div class="notebooks-list">
<p> In the process of moving stuff from <a href="https://techkeen.wixsite.com/website/"> my wix site </a>
</p>

  <ul>
    <li> WebDev </li>
    <li> Electronics </li>
    <li> Programming </li>
    <li> Arduino </li>
    <br>
    <li> Home Projects </li>
    <li> La Cuisine </li>
  </ul>
</div>

Recent blog entries:

<div class="posts">
  {% for post in site.noteposts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ notepost.title }}</a></h1>
      <div class="date">
        Written on {{ notepage.date | date: "%B %e, %Y" }}
      </div>
      <a href="{{ site.baseurl }}{{ notepost.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
