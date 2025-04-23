---
layout: page
title: "Projects"
permalink: /projects/
---

Here are a few highlights:

<ul class="project-list">
  {% for p in site.projects %}
    <li>
      <a href="{{ p.link }}">
        <img src="{{ p.image }}" alt="{{ p.title }}" />
        <h3>{{ p.title }}</h3>
        <p>{{ p.description }}</p>
      </a>
    </li>
  {% endfor %}
</ul>
