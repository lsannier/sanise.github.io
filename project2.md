---
layout: project2
title: Projets en entreprise
---


<h1>{{ page.title }}</h1>

<ul>
  {% for project in site.data.projects %}
    <li>
      <a href="{{ project.link }}">
        <img src="{{ project.image }}" alt="Image de {{ project.name }}">
        <h2>{{ project.name }}</h2>
        <p>{{ project.description }}</p>
      </a>
    </li>
  {% endfor %}
</ul>
