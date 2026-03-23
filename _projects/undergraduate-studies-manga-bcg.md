---
title: "Multiple Cores of Brightest Cluster Galaxies from MaNGA Data in Redshift 0-0.2"
description: "Research on multiple cores in brightest cluster galaxies using SDSS MaNGA data across redshift 0-0.2."
image: ""
github: ""
demo: ""
stage: "undergraduate_research"
stage_title: "Undergraduate Studies"
order: 1
period: "Sep. 2017 - Dec. 2018"
---

<div class="project-meta-card" markdown="1">

**Period:** Sep. 2017 - Dec. 2018

**Advisor:** Dr. Lin, Yen-Ting  
**Affiliation:** Institute of Astronomy and Astrophysics, Academia Sinica

**Keywords:** brightest cluster galaxies, multiple cores, galaxy mergers, SDSS, MaNGA

**Related link:** [Related publication page]({{ '/publications/2022-manga-multiple-cores/' | relative_url }})

</div>

<div class="project-panel" markdown="1">

### Abstract

This project investigated the occurrence of multiple cores in brightest cluster galaxies (BCGs) using imaging and spectroscopic data from the Sloan Digital Sky Survey and the MaNGA project. Because BCGs sit near the centers of galaxy clusters and continue to grow through mergers, the presence of multiple bright cores provides a useful observational tracer of ongoing or recent galaxy assembly.

The work focused on identifying candidate multiple-core systems in the redshift range `z = 0-0.2`, examining their morphology in SDSS images, and constructing a detection workflow to distinguish genuine central substructures from nearby projected sources. The analysis combined image inspection, source detection, and structural measurements around the central galaxy in order to estimate how often BCGs contain multiple cores within their inner regions.

This undergraduate research contributed to a broader effort to connect observed multiple-core fractions with the merger-driven mass growth of massive galaxies in clusters. The project also provided practical experience in survey-image analysis, photometric source extraction, and building data-driven criteria for identifying interacting galaxy systems.

### Research Focus

- Inspect BCG morphology using SDSS and MaNGA survey data
- Identify candidate multiple-core structures in cluster-central galaxies
- Build an image-analysis workflow for detecting compact sources near the galaxy center
- Use photometric criteria such as `petroR50` to define the central search region
- Support estimates of merger activity and late-stage stellar mass growth in BCGs

</div>

<div class="figure-stack">
  <figure class="figure-card">
    <img src="{{ '/assets/images/BCGs/SDSS.png' | relative_url }}" alt="SDSS Navigate interface used to inspect the morphology of a brightest cluster galaxy" />
    <figcaption class="media-caption">Figure 1. Example of the SDSS Navigate interface used to inspect the morphology and environment of a brightest cluster galaxy. This view was used for visual screening of candidate systems and for checking whether nearby light concentrations were plausible companion cores or unrelated neighboring objects.</figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/BCGs/building the model.png' | relative_url }}" alt="Workflow for constructing the image model of a brightest cluster galaxy" />
    <figcaption class="media-caption">Figure 2. Illustration of the image-modeling workflow. The panels show the original galaxy field, a smooth model of the central galaxy light distribution, and the residual image after subtraction, which helps reveal faint nearby structures and potential secondary cores embedded in the halo of the BCG.</figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/BCGs/BCGs_R50.png' | relative_url }}" alt="Comparison of source detection before and after applying the petroR50-based central selection region" />
    <figcaption class="media-caption">Figure 3. Comparison of source detection and the adopted central selection region based on `petroR50` in the SDSS `r` band. This criterion was used to define the inner region of the BCG and to separate candidate multiple cores near the galaxy center from more distant surrounding sources.</figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/BCGs/original_BCGs.png' | relative_url }}" alt="Original image of a brightest cluster galaxy and its surrounding field" />
    <figcaption class="media-caption">Figure 4. Original image of a brightest cluster galaxy and its local environment. The image shows the bright central galaxy embedded in a crowded cluster field, illustrating the observational challenge of identifying compact inner companions against diffuse galaxy light and nearby foreground or background sources.</figcaption>
  </figure>

  <figure class="figure-card">
    <img src="{{ '/assets/images/BCGs/detect_BCGs.png' | relative_url }}" alt="Detected sources overlaid on the brightest cluster galaxy image" />
    <figcaption class="media-caption">Figure 5. Source-detection result for the same BCG field. The overlaid markers indicate objects identified by the detection pipeline and illustrate how the analysis isolated compact sources around the galaxy center for subsequent classification as possible multiple-core candidates.</figcaption>
  </figure>

</div>
