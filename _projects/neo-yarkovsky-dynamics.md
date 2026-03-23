---
title: "Near-Earth objects (NEOs) Dynamics under the Yarkovsky Effect"
description: "Numerical studies of the long-term orbital evolution, migration pathways, and dynamical lifetime of near-Earth objects and Atira asteroids."
image: ""
github: ""
demo: ""
stage: "graduate_astronomy"
stage_title: "Graduate Studies in Astronomy"
order: 1
period: "Mar. 2020 - Jul. 2021"
---

<div class="project-meta-card" markdown="1">

**Period:** Mar. 2020 - Jul. 2021

**Advisor:** Prof. Ip, Wing-Huen  
**Affiliation:** Graduate Institute of Astronomy, National Central University

**Keywords:** near-Earth objects, Yarkovsky effect, Atira asteroids, Vatira asteroids, numerical simulations

**Related link:** [The orbital evolution of Atira asteroids](https://academic.oup.com/mnras/article/517/4/5921/6815743)

</div>

<div class="project-panel" markdown="1">

### Abstract

We investigated the long-term orbital evolution of near-Earth objects (NEOs), with particular emphasis on the Atira population and its possible connection to the Vatira class, by means of `Mercury6` N-body integrations including both planetary perturbations and the Yarkovsky effect. The calculations considered the main NEO sub-groups and the recently discovered Vatira asteroid `2020 AV2`, the first object known to orbit entirely inside Venus' orbit.

The simulations show that the NEO population is composed of short-lived and long-lived dynamical components, reflecting different levels of orbital stability and encounter probability with the terrestrial planets. For Atira asteroids, a fraction of the population can evolve into the Vatira region during long-term migration. The first-transition probability from Atira-class to Vatira-class orbits is about `13%`, with only weak dependence on the assumed obliquity and Yarkovsky strength.

These results indicate that thermal forces play a significant role in shaping the long-term evolution of Atira asteroids and in supplying objects to the innermost asteroid population. The statistical results further suggest a small but non-negligible Vatira population associated with S-type Atira source bodies.

### Research Focus

- Simulate the long-term orbital evolution of NEOs with `Mercury6`
- Include the Yarkovsky effect in addition to planetary gravitational perturbations
- Compare the dynamical behavior of different NEO sub-groups
- Evaluate the transfer probability from Atira-class to Vatira-class asteroids
- Estimate the long-term population implication for Atira and Vatira S-type asteroids

### Main Findings

- NEOs can be described by two dynamical components: a short-lived population and a long-lived population
- Amor-class asteroids show longer long-term dynamical survival than Earth-crossing Aten and Apollo objects
- Atira asteroids with no net Yarkovsky drift still have long-term behavior similar to relatively stable non-Earth-crossing populations
- The first-transition probability from Atira to Vatira orbits is about `13.1%`, with only modest variation for different obliquities
- The statistical analysis implies a small but non-negligible Vatira population associated with S-type Atira source objects

</div>

<div class="figure-stack">
  <figure class="figure-card">
    <img class="figure-image-wide" src="{{ '/assets/images/Artiras/neo_orbit_types.jpg' | relative_url }}" alt="Classification diagram of the main near-Earth asteroid orbital groups" />
    <figcaption class="media-caption">Figure 1. Schematic classification of the main near-Earth asteroid groups, including Amor, Apollo, Aten, and Atira objects. These categories are defined by the semimajor axis and the perihelion or aphelion distance relative to the orbits of Earth and Venus, and they provide the basic framework for tracking orbital transitions in the numerical simulations. Image source: NASA JPL CNEOS (<a href="https://cneos.jpl.nasa.gov/about/neo_groups.html">https://cneos.jpl.nasa.gov/about/neo_groups.html</a>).</figcaption>
  </figure>

  <figure class="figure-card">
    <img class="figure-image-wide" src="{{ '/assets/images/Artiras/Yarkovsky_effect.png' | relative_url }}" alt="Conceptual diagram of the Yarkovsky effect acting on a rotating asteroid" />
    <figcaption class="media-caption">Figure 2. Conceptual illustration of the Yarkovsky effect. Solar heating and delayed thermal re-radiation generate a weak but persistent force that can gradually change an asteroid's semimajor axis. Although the force is small, it becomes important over long time-scales and can help drive orbital migration into dynamically different NEO classes.</figcaption>
  </figure>

  <figure class="figure-card">
    <img class="figure-image-wide" src="{{ '/assets/images/Artiras/Vatira_2020AV2.png' | relative_url }}" alt="Orbit of 2020 AV2 relative to Mercury, Venus, and Earth" />
    <figcaption class="media-caption">Figure 3. Orbital configuration of `2020 AV2`, the first confirmed Vatira asteroid. Its orbit lies entirely inside that of Venus, making it a key example for understanding how Atira-like objects may migrate into the innermost stable asteroid region through long-term dynamical evolution.</figcaption>
  </figure>

  <figure class="figure-card">
    <img class="figure-image-wide" src="{{ '/assets/images/Artiras/210327_timeW_aeiplot_Atira23_obli_0_40.0Myr_all_helio.png' | relative_url }}" alt="Long-term orbital distribution of simulated Atira particles under Yarkovsky-driven evolution" />
    <figcaption class="media-caption">Figure 4. Distribution of simulated Atira test particles in semimajor axis-eccentricity and semimajor axis-inclination space after long-term integration with Yarkovsky forcing. The density pattern illustrates how particles spread into neighboring NEO classes, including the Vatira region, while others evolve toward more eccentric Earth-crossing orbits.</figcaption>
  </figure>
</div>
