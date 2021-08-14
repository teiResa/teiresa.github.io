---
layout: page
title: Notebooks
permalink: /notebooks/
---

<div class="notebooks-list">
<p> In the process of moving stuff from <a href="https://techkeen.wixsite.com/website/"> my wix site </a>
</p>

  <ul>
    <li> <a href="https://techkeen.wixsite.com/website/"> WebDev </a> </li>
    <li> <a href="https://techkeen.wixsite.com/website/"> Electronics </a> </li>
    <li> <a href="https://techkeen.wixsite.com/website/"> Programming </a> </li>
    <li><a href="https://techkeen.wixsite.com/website/"> Arduino </a> </li>
    <br>
    <li> <a href="https://techkeen.wixsite.com/website/"> Home Projects </a> </li>
    <li> <a href="https://techkeen.wixsite.com/website/"> La Cuisine </a> </li>
  </ul>
</div>

Recent note entries:

<div class="posts">
  {% for post in site.noteposts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>
      <div class="date">
        Written on {{ page.date | date: "%B %e, %Y" }}
      </div>
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
