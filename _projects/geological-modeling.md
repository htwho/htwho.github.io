---
title: "3D Geological Modeling"
description: "Interactive three-dimensional hydrogeological modeling built from GMS output and rendered as an HTML-based geological viewer."
image: ""
github: ""
demo: "https://drive.google.com/file/d/1CWgwgOVV1dR9D8kaP0LpYrTP9XdBKk8M/preview"
stage: "work_applied_geology"
stage_title: "Work Studies in Applied Geology"
order: 1
period: "Feb. 2022 - Mar. 2024"
---

<div class="project-meta-card" markdown="1">

**Period:** Feb. 2022 - Mar. 2024

**Advisor:** Prof. Wang, Shih-Jung  
**Affiliation:** Graduate Institute of Applied Geology, National Central University

**Keywords:** geological model, hydrogeology, soil liquefaction, TWD97, 3D visualization

**Related link:** [Taiwan Geologic Knowledge Services](https://twgeoref.gsmma.gov.tw/GipOpenWeb/wSite/sp?xdUrl=/wSite/query/searchResult.jsp&pageSize=15&mp=6&queryField=fullText&queryWord=全臺土壤液化地下水文因子建立與受震行為分析)

</div>

<div class="project-panel" markdown="1">

### Abstract

This project developed an interactive three-dimensional geological modeling workflow for visualizing hydrogeological structures from GMS output files. The system reads geographic data exported as `.shp` files, reconstructs the subsurface grid in three dimensions, and presents the result as an HTML-based model that users can explore directly in a web browser.

The platform was designed to improve the accessibility of large geological models and reduce the difficulty of reviewing dense subsurface data. Instead of relying only on static figures or repeatedly redrawing heavy numerical grids, the final model can be opened online for faster browsing, zooming, and inspection from different viewing angles.

### Workflow

1. Import geographic data files exported from GMS.
2. Read the grid dimensions and spatial coordinates from the source files.
3. Reconstruct each grid cell as a three-dimensional block using TWD97 coordinates.
4. Assign geological materials to each block according to hydrogeological classification.
5. Export the model as an interactive HTML viewer for browser-based exploration.

### Model Characteristics

- Study area: Taipei and New Taipei City
- Coordinate system: TWD97 two-degree zoning system
- Horizontal resolution: 200 x 200 meters
- Vertical resolution: 1 meter
- Interaction: rotation and zoom for multi-angle geological inspection

### Material Classification

- Blue: Gravel
- Green: Coarse, medium, and fine sand
- Yellow: Fine and very fine sand
- Orange: Silt, mud, and clay

</div>

<p class="media-label">Demo Video</p>
<div class="media-embed">
  <iframe src="https://drive.google.com/file/d/1CWgwgOVV1dR9D8kaP0LpYrTP9XdBKk8M/preview"
          title="Geological modeling demonstration"
          allow="autoplay"
          frameborder="0"
          allowfullscreen>
  </iframe>
</div>
<p class="media-caption">Interactive demonstration of the three-dimensional geological modeling interface and web-based visualization workflow.</p>

<div class="figure-stack">
  <figure class="figure-card">
    <img src="{{ '/assets/images/Geo/Geo_model.png' | relative_url }}" alt="Three-dimensional geological model of the Taipei and New Taipei area" />
    <figcaption class="media-caption">Three-dimensional geological model and cross-section grid visualization for the Taipei and New Taipei area.</figcaption>
  </figure>
</div>
