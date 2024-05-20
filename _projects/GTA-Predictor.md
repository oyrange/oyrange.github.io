---
layout: page
title: Grand Theft Auto Analytics
description: Screen time analysis and predictor conducted from 1.25 million rows of data.
img: /assets/img/project-imgs/GTA-Analytics/playtime-per-day.png
importance: 1
category: Machine Learning
related_publications: true
---
The attached research report includes discussion about the ethicality of comprehensive playtime data.
This model achieved consistent 84%+ accuracy over four comprehensive data models and a thorough pipeline parsing 1.25 million lines of data.

[Repository](https://github.com/oyrange/GTA-Screentime)

[Report](/../assets/pdf/GTA_Final_Report.pdf)


<!--
To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->

<div class="col">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/project-imgs/GTA-Analytics/heatmap.png" title="Heat Map" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="caption">
        Heatmap used to parse initial feature correlations.
    </div>

    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/project-imgs/GTA-Analytics/playtime-per-day.png" title="Playtime per Day" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Approximated playtime per day for each player in the dataset.
</div>
