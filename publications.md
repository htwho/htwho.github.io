---
title: Publications
permalink: /publications/
---

# 📚 Publications

Selected journal articles and conference papers are listed below.

{% assign pubs_2022 = site.publications | where: 'year', 2022 | sort: 'title' %}
{% assign pubs_other = site.publications | where_exp: 'item', 'item.year != 2022' | sort: 'year' | reverse %}

{% if pubs_2022.size > 0 %}
<section class="home-section">
  <h2>2022</h2>
  <div class="presentation-year-grid">
    {% for pub in pubs_2022 %}
    <article class="presentation-card citation-entry-card">
      <h3><a href="{{ pub.url | relative_url }}">{{ pub.title }}</a></h3>
      <p class="presentation-authors">{{ pub.authors }} ({{ pub.year }}).</p>
      <p class="presentation-meta"><em>{{ pub.venue }}</em></p>
      <p class="presentation-location">
        Publication details
        <span class="inline-actions">
          <a href="{{ pub.url | relative_url }}">Details</a>
          {% if pub.doi %}<a href="https://doi.org/{{ pub.doi }}">DOI</a>{% endif %}
          {% if pub.pdf %}<a href="{{ pub.pdf }}">PDF</a>{% endif %}
        </span>
      </p>
    </article>
    {% endfor %}
  </div>
</section>
{% endif %}

{% if pubs_other.size > 0 %}
<section class="home-section">
  <h2>Other Years</h2>
  <div class="presentation-year-grid">
    {% for pub in pubs_other %}
    <article class="presentation-card citation-entry-card">
      <h3><a href="{{ pub.url | relative_url }}">{{ pub.title }}</a></h3>
      <p class="presentation-authors">{{ pub.authors }} ({{ pub.year }}).</p>
      <p class="presentation-meta"><em>{{ pub.venue }}</em></p>
      <p class="presentation-location">
        Publication details
        <span class="inline-actions">
          <a href="{{ pub.url | relative_url }}">Details</a>
          {% if pub.doi %}<a href="https://doi.org/{{ pub.doi }}">DOI</a>{% endif %}
          {% if pub.pdf %}<a href="{{ pub.pdf }}">PDF</a>{% endif %}
        </span>
      </p>
    </article>
    {% endfor %}
  </div>
</section>
{% endif %}
