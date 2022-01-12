---
layout: page
title: Brain Computer Interfact EEG-based Motor Imagery Prediction
description: Past project (2020-2021) P.I. Dr. Azim Eskandarian
img: assets/img/EEG_title.jpg
importance: 2
category: Graduate
---

Brain-computer interface (BCI) is a pathway for direct communication between human brains and external devices. EEG-based motor imagery is a no-invasive mental execution for body rehabilitation. The objective of this project is to implement conventional feature extraction methods and deep learning-based methods to estimate and predict human motor imagery resutls

---
Time-frequency Common Spatial Pattern Feature Extraction Algorithm
Paper: A Computationally Efficient Multiclass Time-Frequency Common Spatial Pattern Analysis on EEG Motor Imagery


<div class="row">
    <div class="col-sm mt-12 mt-md-0">
        {% include figure.html path="assets/img/EMBC_Architecture.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Time-Frequency Common Spatial Pattern Architecture. The EEG signal is decomposed by a short-time fourier transform algorithm for time-frequency analysis. Then, the optimal freqency and temporal band are processed by the common spatial pattern feature extraction algorithm. Finally, a classifier is applied to classify EEG motor imagery results 

</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Subject3_Left_C3_Channel.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Subject3_Left_C3_Channel1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    "Left hand" class C3 and C4 channel
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Subject3_Right_C3_Channel.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Subject3_Right_C3_Channel1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    "Right hand" class C3 and C4 channel
</div>

We used an open-source dataset BCI Compeition IV Dataset and the classification results outperform other popular motor imagery classification algorithms
<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/EMBC_table.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---
Deep learning-based method for motor imagery classification (EEG-Inception Network)
Paper: EEG-Inception: An Accurate and Robust End-to-End Neural Network for EEG-based Motor Imagery Classification

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/JEN_Architecture.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    EEG-Inception Network Architecture
</div>

To overcome data shortage and improve the algorithm robustness, we have developed a data augmentation method by applying EEG noises to the signal.
<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Figure 4a.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Figure 4b.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Data augmentation method. We extract the high frequency noises from the sample data and randomly applied them to other samples.
</div>

The classification results ranked 2nd place on the BCI Competition IV dataset 2a (binary classes) and SOTA and the BCI Competition IV Dataset 2b (multiple classes)

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Figure 12.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/Figure 13.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Classification accuracy at BCI Competition IV 2a and 2b dataset
</div>
<div class="row justify-content-sm-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/JNE_results1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.html path="assets/img/JNE_reuslts2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


