---
layout: page
title: Pulse Sensing
description: Interactive graphic using nutritional data
img: assets/img/finalVis_Cover.png
importance: 3
category: work
---

<b>Work in progress</b>

<b>Timeline:</b> March 2022 - May 2022

For this project, I used Altair, a statistical visualization library for Python, to create an interactive scatter plot containing nutritional data about a number of foods in certain categories.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/finalVis_Functions.gif" title="Visualization functionality demonstration" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    A gif showcasing the visualization's functionality, including a drop-down menu and interactive tooltips.
</div>

<p><b>Data information and source</b></p>
<ul>
    <li>For this project, I used <a href="https://www.ars.usda.gov/northeast-area/beltsville-md-bhnrc/beltsville-human-nutrition-research-center/methods-and-application-of-food-composition-laboratory/mafcl-site-pages/sr11-sr28/">food nutrition data published by the USDA</a>, which I condensed and sorted into related food groupings. I then used the Altair library's functions to map these groups and the associated nutritional data onto a scatter plot.</li>
</ul>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/finalVis_Concept.png" title="Original visualization concept drawing" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    A rough concept sketch of the visualization to be created. The design's functionality was eventually modified, as seen above.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/finalVis_Full.png" title="Finished visualization" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    A static version of the finished visualization.
</div>