---
title: Projects
permalink: /projects/
---

# 🔬 Projects

These projects reflect my work across geophysics, planetary science, and scientific data analysis.

{% assign grouped_stages = "phd_geophysics|work_applied_geology|graduate_astronomy|undergraduate_research" | split: "|" %}
{% for stage_key in grouped_stages %}
{% assign stage_projects = site.projects | where: "stage", stage_key | sort: "order" %}
{% if stage_projects.size > 0 %}
<section class="home-section">
  <h2>{{ stage_projects.first.stage_title }}</h2>
  <div class="project-grid">
    {% for project in stage_projects %}
    <article class="card project-card project-list-card">
      <p class="project-card-period">{{ project.period }}</p>
      <h3><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
      <p>{{ project.description }}</p>
      <div class="quick-links">
        <a href="{{ project.url | relative_url }}">Details</a>
        {% if project.github and project.github != "" %}<a href="{{ project.github }}">GitHub</a>{% endif %}
        {% if project.demo and project.demo != "" %}<a href="{{ project.demo }}">Demo</a>{% endif %}
      </div>
    </article>
    {% endfor %}
  </div>
</section>
{% endif %}
{% endfor %}
