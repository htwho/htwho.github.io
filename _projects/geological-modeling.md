---
title: "Geological Modeling"
description: "Interactive three-dimensional hydrogeological modeling built from GMS output and rendered as an HTML-based geological viewer."
image: ""
github: ""
demo: "https://drive.google.com/file/d/1CWgwgOVV1dR9D8kaP0LpYrTP9XdBKk8M/preview"
stage: "work_applied_geology"
stage_title: "Work Studies in Applied Geology"
order: 1
period: "Feb. 2022 - Mar. 2024"
---

## Geological Modeling

<div class="project-meta-card" markdown="1">

**Period:** Feb. 2022 - Mar. 2024

**Advisor:** Prof. Wang, Shih-Jung  
**Affiliation:** Graduate Institute of Applied Geology, National Central University

**Keywords:** geological model, soil liquefaction, hydrogeology, TWD97

**Related link:** [Taiwan Geologic Knowledge Services](https://twgeoref.gsmma.gov.tw/GipOpenWeb/wSite/sp?xdUrl=/wSite/query/searchResult.jsp&pageSize=15&mp=6&queryField=fullText&queryWord=全臺土壤液化地下水文因子建立與受震行為分析)

</div>

<div class="project-panel" markdown="1">

<h3>Abstract</h3>

To present the hydrogeological model established in this project, Python open-source code was used to develop the frontend input interface. In the operating interface, users simply need to place the geographic data files (`.shp`) outputted by GMS into the specified path. These data files contain geological material and location information for all grid cells. Users can configure the desired number of cross-sections and the county range within the interface to present an interactive three-dimensional geological model. The colors of materials in the model are presented based on the four hydrogeological classifications at the Geological Survey and Mining Management Agency (MOEA), such as blue representing gravel, green representing coarse, medium, and fine sand, yellow representing fine and very fine sand, and orange representing silt, mud, and clay.

The final geological model and the boundaries of county administrative districts are drawn based on the TWD97 two-degree zoning coordinate system. When reading geographic data files, the system first reads the length, width, and height data of the geological model grid information, with the spacing between the centers of two adjacent grids serving as the horizontal resolution, and the spacing between the centers of upper and lower layer grids serving as the vertical resolution. For example, in the grid map of the Taipei and New Taipei area shown in the figure, the horizontal resolution is 200 x 200 meters, and the vertical resolution is 1 meter. After obtaining the grid resolution, the system constructs a cube of 200 meters x 200 meters x 1 meter, then places each cube's position and surface elevation based on the TWD97 system coordinates provided by the geographic data file, and assigns the corresponding material color to each cube.

The generated three-dimensional geological model can be rotated 720 degrees and zoomed in or out using the mouse to observe geological details from different angles and positions. Finally, the model is output in HTML webpage format and embedded into the project's database system for convenient browsing at any time, avoiding issues such as slow access speed caused by excessive numerical grid quantities or excessive time consumption waiting for redraw.

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
