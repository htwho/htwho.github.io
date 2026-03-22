---
title: Home
permalink: /
---

<section class="hero hero-panel">
  <p class="eyebrow">Academic Homepage</p>
  <h1 class="hero-title">{{ site.title }}</h1>
  <p class="meta">Ph.D. Student in Geophysics | National Central University</p>
  <p class="hero-subtitle">
    I am a Ph.D. student at the Graduate Institute of Geophysics, National Central University. My current
    research focuses on borehole temperature monitoring, distributed temperature sensing, and the thermal
    structure of active faults. I also work on planetary science topics, especially the dynamics and
    long-term evolution of small bodies in the inner Solar System.
  </p>
  <div class="profile-links">
    <a href="{{ site.scholar_url }}">Google Scholar</a>
    <a href="{{ site.researchgate_url }}">ResearchGate</a>
    <a href="{{ site.orcid_url }}">ORCID</a>
    <a href="{{ site.github_url }}">GitHub</a>
  </div>
</section>

## Research Overview

<div class="citation-blocks">
  <article class="citation-card">
    <p class="citation-year">Focus Areas</p>
    <ul class="card-list">
      <li>Borehole temperature monitoring</li>
      <li>Distributed temperature sensing</li>
      <li>Thermal properties of active faults</li>
      <li>Small-body dynamics in the inner Solar System</li>
      <li>Planetary science data analysis</li>
    </ul>
  </article>
</div>


## Selected Publications

{% assign selected_pubs = site.publications | sort: 'year' | reverse %}
<div class="citation-blocks">
  {% for pub in selected_pubs limit:2 %}
  <article class="citation-card">
    <p class="citation-year">{{ pub.year }}</p>
    <p class="citation-text">
      {{ pub.authors }} ({{ pub.year }}). <a href="{{ pub.url | relative_url }}">{{ pub.title }}</a>.
      <em>{{ pub.venue }}</em>.
    </p>
  </article>
  {% endfor %}
</div>

## Explore More

<div class="citation-blocks two-column-cards">
  <article class="citation-card compact-card">
    <p class="citation-year">About &amp; CV</p>
    <p class="citation-text">
      Background, education, work experience, and selected academic activities.
    </p>
    <p class="citation-text"><a href="{{ '/cv/' | relative_url }}">View profile</a></p>
  </article>
  <article class="citation-card compact-card">
    <p class="citation-year">Projects</p>
    <p class="citation-text">
      Research projects across geophysics, applied geology, planetary science, and observational studies.
    </p>
    <p class="citation-text"><a href="{{ '/projects/' | relative_url }}">View projects</a></p>
  </article>
  <article class="citation-card compact-card">
    <p class="citation-year">Presentations</p>
    <p class="citation-text">
      Conference presentations, posters, and workshop contributions organized by year.
    </p>
    <p class="citation-text"><a href="{{ '/presentations/' | relative_url }}">View presentations</a></p>
  </article>
  <article class="citation-card compact-card">
    <p class="citation-year">Contact</p>
    <p class="citation-text">
      Email, institutional address, office information, and map location.
    </p>
    <p class="citation-text"><a href="{{ '/contact/' | relative_url }}">Get in touch</a></p>
  </article>
</div>
