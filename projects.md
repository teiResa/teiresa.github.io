---
layout: page
title: Project Sites
permalink: /projects/
---

The links lead to the project sites. I intend to put small previews of the other end of the links here in the future. They're in no perticular order.

<h2> WebDev & Design </h2>
<em> Includes illustrations and animations. </em>
<ul>
  <li> <a href="https://techkeen.wixsite.com/website/"> WebDev </a> </li>
  <li> <a href="https://teiresa.github.io/Pure-CSS-Illustrations-Lessons/"> Pure CSS Illustrations </a> </li>
  <li> <a href="https://teiresa.github.io/profile-card-component/"> Profile Card </a> </li>
  <li><a href="https://teiresa.github.io/responsive-site/"> Sample Responsive Website </a> </li>
  <br>
  <br>
  And a few from the pre-responsive era:
  <li> <a href="https://teiresa.github.io/esl-teacher-desk/"> ESL teacher website </a> </li>
  <li> <a href="https://teiresa.github.io/robogenes/"> former personal site </a> </li>
  </ul>

  <h2> Programming languages </h2>
  <em> These would just lead to source code printed on a webpage. So, some are linked. </em>
  <ul>
    <li> <a href="https://teiresa.github.io/java/pages/index.html"> A collection of Java projects </a> </li>
    <li> <a href=""> A collection of Arduino (C++) projects </a> </li>
    <li> <a href=""> Some Python </a> </li>
  </ul>

  <h2> Miscellany </h2>
  <ul>
  Some incomplete projects I am keeping to finish when I have the time:
  <li> <a href="https://teiresa.github.io/TicTacTwo/"> <s> Tic Tac Toe (CSS) </s></a> </li>
  <li> <a href="https://teiresa.github.io/Hangman/"> <s> Hangman (Py) </s></a> </li>
  </ul>
</div>




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
