---
layout: page
title: EDPCGRL SpiderVR
description: Personalized VR Arachnophobia Therapy Using Reinforcement Learning
img: assets/img/VR_Spider.gif
importance: 1
category: work
related_publications: false
github: https://github.com/athar70/EDPCGRL4Spider
hashtags: [RL, SP, VR]
---

## Overview

Arachnophobia, the intense fear of spiders, affects millions worldwide. Exposure therapy is one of the most effective treatments for this phobia, but traditional methods require manual intervention from therapists to select specific stimuli for each patient. To address this challenge, **SpiderVR**, a novel framework utilizing **Experience-Driven Procedural Content Generation via Reinforcement Learning (EDPCGRL)**, was developed to automatically adapt virtual spiders in real-time based on user feedback, optimizing anxiety levels to enhance the therapeutic process.

This framework personalizes exposure therapy by dynamically adjusting the attributes of virtual spiders, like size, color, movement, and proximity, to match the user’s anxiety responses. By incorporating reinforcement learning, the system learns which spider attributes trigger the most effective anxiety response for each individual, providing a highly tailored therapeutic experience without the need for manual therapist intervention.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/spider0.png" title="Calm Spider" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/spider1.png" title="Moderate Spider" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/spider2.png" title="Intense Spider" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Key Features

- **Personalization:** The framework adapts in real-time based on physiological feedback such as skin conductance, ensuring the spider attributes (e.g., size, color, movement) are tailored to each user’s anxiety response.
- **Reinforcement Learning:** Unlike traditional rule-based systems, SpiderVR utilizes reinforcement learning to improve its adaptation, learning the user’s anxiety triggers and optimizing the exposure process over time.

- **Therapist Intervention:** The system automates what was previously a manual and time-consuming task, freeing therapists from having to constantly adjust the virtual environment. Instead, they set a target anxiety level, and the system manages the rest.

## Human Study

A human study was conducted to evaluate SpiderVR’s effectiveness in comparison to a traditional rules-based approach. The study demonstrated that the reinforcement learning method more accurately reached the desired anxiety levels, providing a more personalized therapy experience. The **EDPCGRL** framework was able to adapt virtual spider attributes dynamically and provide a better match to individual anxiety levels compared to the rules-based method, which relied on pre-defined rules.

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Relaxing.gif" title="Relaxing Environment" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/VR_Spider.gif" title="Spider Adaptation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## GitHub Repository

To explore the code and see the implementation details of this project, visit the [GitHub repository](https://github.com/athar70/EDPCGRL4Spider).

## Related Publication

You can also find the full details of this research in the paper: [Personalized VR Arachnophobia Therapy Using Reinforcement Learning](https://arxiv.org/abs/2409.17406).

## Future Impact

SpiderVR represents a significant leap in personalized therapy, particularly for phobia treatments. As it continues to evolve, there is potential for the framework to be adapted to other anxiety disorders, offering an adaptable and scalable solution for virtual reality exposure therapy across different phobias and mental health conditions.
