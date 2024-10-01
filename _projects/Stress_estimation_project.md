---
layout: page
title: Stress Estimation in VRET Using PPG
description: Detecting Stress Levels in Virtual Reality Therapy with Photoplethysmography Signals
img: assets/img/stressful.gif
importance: 2
category: work
related_publications: false
github: https://github.com/athar70/Stress-Estimation
hashtags: [ClassicalML, DL, SP, VR]
---

## Overview

**Stress Estimation in VRET Using PPG Signals** is a project designed to detect and estimate stress levels in subjects during **Virtual Reality Exposure Therapy (VRET)** by analyzing **Photoplethysmography (PPG) signals**. This platform uses machine learning and deep learning to classify mental states—**relaxed or stressed**—in real-time, providing a foundation for adaptive, personalized therapy.

In this study, **19 subjects** were exposed to relaxing and stressful VR environments. The system automatically processes PPG data and demographic information to estimate stress levels, making it a non-invasive solution for real-time stress monitoring and therapy adjustment. The recent update includes a **deep learning method** and **subject information embedding** for improved accuracy and adaptability.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Relaxing.gif" title="Relaxing VR Environment" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/stressful.gif" title="Stressful VR Environment" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Key Features

- **PPG Signal Stress Detection:** The platform uses PPG signals to estimate the subject’s mental state, which can be used to provide real-time feedback to personalize therapy sessions based on the subject's stress levels.

- **Machine Learning and Deep Learning Models:** The platform uses both traditional machine learning methods (e.g., SVM, Random Forest, LDA) and deep learning models to classify stress states with **up to 65% accuracy**. The **deep learning method** enables better detection of stress levels by utilizing more complex patterns in the data.

- **Human Representation:** Demographic data, including age, gender, VR and gaming experience, and time since last stimulant intake, is embedded to enhance the model’s performance and provide more personalized predictions.

- **Adaptive Therapy Potential:** This stress estimation system can be integrated into VRET platforms to dynamically adapt the therapy environment based on the patient’s real-time stress levels, enhancing its effectiveness.

## Study Details

- **Participants:** 19 healthy subjects were exposed to a relaxing and a stressful VR environment, and their PPG signals were collected.
- **Signal Processing:** The PPG data was segmented into windows with overlapping intervals. Machine learning models were trained using **Leave-One-Subject-Out (LOSO) cross-validation** to ensure the system’s generalization to unseen subjects.
- **Results:** The **Deep Learning** model achieved a **62% accuracy**, which increased to **65%** when demographic information was incorporated into the model through embedding.

## GitHub Repository

Explore the full implementation and extend this project by visiting the [GitHub repository](https://github.com/athar70/Stress-Estimation). The repository includes code and instructions for running the signal classification system, including both machine learning and deep learning models.

## Related Publication

For more detailed information, refer to the paper: [Stress Estimation in VRET Using PPG Signals](https://arxiv.org/abs/2409.17427).

## Future Impact

By enabling real-time stress detection using non-invasive PPG sensors, this platform offers new possibilities for **adaptive therapy systems**. These systems can automatically adjust the VR environment based on the patient’s mental state, providing a more tailored and effective therapeutic experience.
