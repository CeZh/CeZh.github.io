---
layout: page
title: Autonomous Vehicle Sensor Perceptual Quality Assessment
description: Current project (2021-) P.I. Dr. Azim Eskandarian
img: assets/img/Sensor_reliability_title.jpg
importance: 1
category: Graduate
---
Perception is one the most fundamental but most important step for autonomous vehicle (AV). Few studies have been conducted for AV surrounding driving environment complexity and sensor perceptual quality. In this project, we studies the evalution method about driving environment complexity and sensor perceptual quality. Then, we developed deep learning-based algorithms to predict both the driving environment complexity and sensor perceptual quality factors.

---
Autonomous Vehicle Driving Environment Complexity Perception

paper: Attention-based Neural Network for Driving Environment Complexity Perception

Environment perception is crucial for autonomous vehicle (AV) safety. Most  existing  AV  perception  algorithms havenot  studiedthe surrounding  environment complexity and failed to include the environment complexity parameter. In this project, we propose a novel attention-based neural network model to predict thecomplexity level of thesurrounding driving environment.

<div class="row">
    <div class="col-sm mt-12 mt-md-0">
        {% include figure.html path="assets/img/project4_background.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Proposed perception method
</div>

The image is processed by a heat map generation algorithm
<div class="row">
    <div class="col-sm mt-12 mt-md-0">
        {% include figure.html path="assets/img/heat_results.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-12 mt-md-0">
        {% include figure.html path="assets/img/psuedocode.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Proposed Heat Map Generation Algorithm
</div>

The surrounding environment complexity label is generated through subjective labeling.
<div class="row">
    <div class="col-sm mt-12 mt-md-0">
        {% include figure.html path="assets/img/Label_Creation.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Environment Complexity Label Generation for the BDD100k Dataset
</div>
An attention network is devloped to predict the surrounding environment complexity label

<div class="row">
    <div class="col-sm mt-12 mt-md-0">
        {% include figure.html path="assets/img/propose_network.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Attention-based Neural Network Architecture
</div>

The network classification accuracy achieved over 90%
<div class="row">
    <div class="col-sm mt-12 mt-md-0">
        {% include figure.html path="assets/img/results.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Attention-based Neural Network Classification Accuracy Results
</div>


---
Our new research about sensor perceptual quality is about to be published soon! The future algorithms are going to be open-source in the future. Welcome to visit after the publication!

