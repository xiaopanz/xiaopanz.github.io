---
layout: page
title: projects
permalink: /projects/
description: Research projects from my papers in embodied AI, multi-robot systems, and robot learning.
nav: true
nav_order: 3
---

<div class="paper-project-grid">
  {% for project in site.data.paper_projects %}
    <article class="paper-project-card" id="{{ project.id }}">
      <a class="paper-project-image" href="{{ '/publications/' | relative_url }}#{{ project.id }}" aria-label="Publication details for {{ project.name }}">
        <img src="{{ project.image | prepend: '/assets/img/projects/' | relative_url }}" alt="{{ project.alt }}" loading="lazy" decoding="async">
      </a>
      <div class="paper-project-body">
        <p class="paper-project-venue">{{ project.venue }}</p>
        <h2>{{ project.name }}</h2>
        <p class="paper-project-title">{{ project.title }}</p>
        <p>{{ project.summary }}</p>
        <div class="paper-project-links">
          <a href="{{ project.paper }}" class="btn btn-sm z-depth-0" target="_blank" rel="noopener noreferrer">Paper</a>
          {% if project.website %}<a href="{{ project.website }}" class="btn btn-sm z-depth-0" target="_blank" rel="noopener noreferrer">Project page</a>{% endif %}
          {% if project.code %}<a href="{{ project.code }}" class="btn btn-sm z-depth-0" target="_blank" rel="noopener noreferrer">Code</a>{% endif %}
        </div>
      </div>
    </article>
  {% endfor %}
</div>

See the [publications]({{ '/publications/' | relative_url }}) page and [Google Scholar](https://scholar.google.com/citations?user=iLrGkU4AAAAJ) for citations, and my [CV]({{ '/cv/' | relative_url }}) for ongoing research and experience.
