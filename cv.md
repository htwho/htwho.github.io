---
title: About & CV
permalink: /cv/
---

# 👤 About & CV

<div class="citation-blocks two-column-cards">
  <article class="citation-card compact-card">
    <p class="citation-year">Curriculum Vitae</p>
    <p class="citation-text">You can download my CV here: <a href="{{ '/assets/files/2026_htlai_CV.pdf' | relative_url }}">Curriculum Vitae</a></p>
  </article>
</div>

## ✨ Profile

<div class="citation-blocks">
  <article class="citation-card">
    <p class="citation-text">I’m a Ph.D. student at the Institute of Geophysics, National Central University, working with <a href="https://tec.earth.sinica.edu.tw/Ma_K_F.html">Prof. Kuo-Fong Ma</a> on the MiDAS project. Our research focuses on borehole temperature monitoring to better understand the thermal properties of the Milun fault using distributed temperature sensing (DTS) technology.</p>
    <p class="citation-text">Previously, I worked with <a href="https://www.astro.ncu.edu.tw/people/faculty_bio_e.php?id=5">Prof. Wing-Huen Ip</a> on the dynamics of small bodies in the inner solar system. My research explored how non-gravitational forces influence their orbits and long-term evolution. I also studied the surface composition of Comet 67P during its perihelion, analyzing microwave spectroscopic data collected by the Rosetta spacecraft.</p>
    <p class="citation-text">I enjoy discussing academic research and exchanging ideas with people from different backgrounds. If you’re interested in any of these topics or would like to share your own experiences, I’d be glad to connect.</p>
  </article>
 </div>

## 🔍 Research Interests

<div class="citation-blocks">
  <article class="citation-card">
    <p class="citation-year">Research Interests</p>
    <ul class="card-list">
      <li>Borehole temperature monitoring</li>
      <li>Thermal properties of active faults</li>
      <li>Small-body dynamics in the Solar System</li>
      <li>Planetary science data analysis</li>
    </ul>
  </article>
</div>

## 🎓 Education

<div class="citation-blocks two-column-cards">
  <article class="citation-card compact-card">
    <h3>Ph.D. Student in Geophysics</h3>
    <p class="citation-text">Graduate Institute of Geophysics, National Central University</p>
    <p class="meta">Taoyuan, Taiwan</p>
  </article>
  <article class="citation-card compact-card">
    <h3>Master of Science in Astronomy</h3>
    <p class="citation-text">Graduate Institute of Astronomy, National Central University</p>
    <p class="meta">Taoyuan, Taiwan</p>
  </article>
  <article class="citation-card compact-card">
    <h3>Bachelor of Science in Physics</h3>
    <p class="citation-text">Department of Applied Physics and Chemistry, University of Taipei</p>
    <p class="meta">Taipei, Taiwan</p>
  </article>
</div>

## 💼 Work Experience

<div class="citation-blocks two-column-cards">
  <article class="citation-card compact-card">
    <p class="citation-year">Sep. 2021 - Jul. 2024</p>
    <h3>Administrative and Research Assistant</h3>
    <p class="citation-text">Graduate Institute of Applied Geology, National Central University</p>
    <p class="meta">Taoyuan, Taiwan</p>
  </article>
  <article class="citation-card compact-card">
    <p class="citation-year">Aug. 2017 - Jul. 2019</p>
    <h3>Administrative Assistant</h3>
    <p class="citation-text">Department of Applied Physics and Chemistry, University of Taipei</p>
    <p class="meta">Taipei, Taiwan</p>
  </article>
</div>


## 📜 Recent Presentations

{% assign presentations_page = site.pages | where: "path", "presentations.md" | first %}
<div class="citation-blocks">
  {% for item in presentations_page.recent_presentations %}
  <article class="citation-card">
    <p class="citation-year">{{ item.year }}</p>
    <p class="citation-text">{{ item.text }}</p>
  </article>
  {% endfor %}
</div>
