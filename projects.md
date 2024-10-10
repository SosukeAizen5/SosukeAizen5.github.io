---
layout: page
title: "Work/Projects"
permalink: /projects/
---

## My Projects

Here are some of the projects I've worked on:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span class="post-date">({{ post.date | date: "%b %d, %Y" }})</span>
      <p>{{ post.excerpt | strip_html }}</p>
    </li>
  {% endfor %}
</ul>
