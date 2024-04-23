---
layout: page
title: Spam
description: A machine learning model parsing emails into spam or legitimate interest emails. 85% accuracy consistently achieved on unseen test data.
img: /assets/img/project-imgs/Spam-Ham/roc-curve.png
importance: 3
category: Machine Learning
related_publications: true
---

<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/project-imgs/Spam-Ham/roc-curve.png" title="ROC Curve" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="/assets/img/project-imgs/Spam-Ham/tpr-fpr.png" title="TPR, FPR Graph" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, the ROC Curve to visualise optimal threshold. To the right, the true and false positive rates respectively, for each threshold.
</div>
