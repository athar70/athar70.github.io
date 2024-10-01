---
layout: page
title: Detecting Autism Using a Video Game
description: Early Autism Screening Through Hand-Eye Coordination in Gameplay
img: assets/img/bee-faster.gif
importance: 6
category: work
related_publications: false
hashtags: [ClassicalML, VG]
---

## Overview

**Detecting Autism Using a Video Game** is a project designed to automatically screen children for Autism Spectrum Disorder (ASD) through a simple, interactive game. The game monitors and analyzes children's motor patterns, specifically hand-eye coordination, and compares these patterns to those of typically developing peers. By analyzing key features like speed, accuracy, and motor control, the system identifies potential indicators of ASD.

The project was developed in **close collaboration with psychologists**, and data was gathered during gameplay to analyze differences in motor patterns between children with ASD and typically developing peers.

A preliminary version of this work was published in the paper: ["The Differences Between Children with Autism and Typically Developed Children in Using a Hand-Eye Coordination Video Game"](https://link.springer.com/chapter/10.1007/978-3-319-67585-5_27). The paper demonstrated that just two features extracted from the game were sufficient to clearly distinguish children with autism from typically developing children.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bee_easy.png" title="An example of easy level" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bee_meduim.png" title="An example of medium level" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bee_hard.png" title="An example of hard level" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bee_veryhard.png" title="An example of very hard level" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Key Features

- **Game Development and Data Analysis:** The game captures and analyzes motor coordination data to allow early screening of children showing signs of ASD. Data collected during gameplay was used to assess behavioral patterns.

- **Behavioral Feature Extraction:** The game collects data such as movement velocity, acceleration, and trajectory deviation. These features help identify deviations in hand-eye coordination between typically developing children and those with autism.

- **Game Design:** The game tasks children with controlling a bee character along a path of flowers using their index finger. Levels range in difficulty, from easy to very hard, testing different aspects of motor control.

## Study Details

- **Participants:** The study involved children diagnosed with Autism Spectrum Disorder (ASD), Down Syndrome, typically developing children, and adults with Alzheimer's disease.
- **Data Collection and Analysis:** Data was automatically sent to a server for analysis. Features such as distance between points, velocity, and time spent in each level were extracted and analyzed to identify motor coordination patterns.

## Methodology

- **Classifiers:** Machine learning classifiers such as **Support Vector Machines (SVM)**, **Decision Trees**, and **Neural Networks** were applied to classify children into four groups: Autism, Down Syndrome, Alzheimer's, and typically developing.
- **Validation:** A 10-fold cross-validation was used to evaluate the accuracy of the classifiers.
- **Best Performance:** The **Decision Tree** classifier achieved the highest accuracy of **93%**, with a **precision of 83%** and **specificity of 94%** in distinguishing the four groups.

## Results

- **Accuracy:** The Decision Tree classifier delivered a 93% accuracy rate in classifying children into different groups based on their motor coordination during gameplay.
- **Potential Applications:** This game offers a low-cost, non-intrusive screening tool for early autism detection. It is simple enough to be used by non-experts and does not require specialized equipment, making it accessible for wider use.

## Acknowledgments

This project was completed as part of my **Master's Thesis** at **Shahid Beheshti University**, under the supervision of **Dr. Hadi Moradi**. I would like to express my gratitude to the psychologists and collaborators who guided the project, as well as the children and families who participated in the study.

## Future Impact

This game-based screening tool highlights the potential of using **gameplay patterns** to detect autism and other coordination disorders. It opens up possibilities for **non-intrusive diagnostic tools** in broader healthcare applications, potentially improving early detection and intervention strategies for children with developmental disorders.
