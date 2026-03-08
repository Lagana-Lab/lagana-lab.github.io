---
layout: page
title: project 1
description: with background image
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

Molecular Heterogeneity & Network Biology
Multiple myeloma is not one disease but many, driven by diverse genetic and transcriptional events that shape prognosis and treatment response. Our goal is to dissect this heterogeneity, refine risk stratification, and uncover the mechanisms that drive myeloma onset and progression. Ongoing work is integrating single-cell data into the same framework so we can track subclonal niches and their interactions with the tumour microenvironment, further sharpening patient stratification and generating new mechanistic hypotheses.

MMNet
We integrated genomic, transcriptomic, and clinical data from 450 newly diagnosed patients to construct a disease network that links alterations to stage, clonality, and early progression. We validated CDC42BPA and CLEC11A as new regulators and derived a four-gene signature that stratifies high-risk myeloma. [more]

MM-PSN
We built the first multi-omics patient-similarity network for 655 myeloma cases, integrating five data layers to define 12 molecular subgroups. Our model revealed that t(4;14) with 1q gain marks an ultra-high-risk subset and showed 1q gain alone outperforms ISS/R-ISS for relapse prediction. [more]

Ongoing projects
Deep-learning tumor/TME fusion
We are developing a network model that merges bulk genomics with single-cell profiles from both tumor and micro-environment. The model aims to quantify how TME features shift patient sub-types and risk, highlighting immune and stromal targets for novel therapies.

​

Single-cell clonal reconstruction workflow

Our multi-modal pipeline integrates gene expression, inferred CNVs, and mutation signals from scRNA-seq to reconstruct patient clonal landscapes. We are now applying it in a high-risk cohort to track subclone dynamics tied to relapse and therapy resistance.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
