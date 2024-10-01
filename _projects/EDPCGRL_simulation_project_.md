---
layout: page
title: EDPCGRL SpiderVR in Simulation
description: Adaptive Arachnophobia Therapy in Simulation Using Reinforcement Learning
img: assets/img/VR_Human_Spider.gif
importance: 3
category: work
related_publications: false
github: https://github.com/athar70/EDPCGRL
hashtags: [DL, RL]
---

## Overview

**EDPCGRL SpiderVR in Simulation** extends our work in personalized virtual reality exposure therapy for arachnophobia. Using **Experience-Driven Procedural Content Generation via Reinforcement Learning (EDPCGRL)**, the system adapts virtual spiders to match the stress responses of **simulated virtual humans**. This allows the system to personalize the experience based on physiological measures, without requiring therapist intervention.

The framework is tested in a simulated environment where virtual humans, based on prior psychological research on arachnophobia, respond to the spider’s attributes such as size, movement, and proximity. The goal is to automatically adjust these attributes in real-time to achieve the desired stress level in each simulation, outperforming traditional content generation approaches.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/system.png" title="proposed framework" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Key Features

- **Simulated Virtual Humans:** Virtual humans are used in the simulation, modeled on arachnophobia research, allowing for rapid testing and adaptation of the therapy system without direct human trials.
- **Multiple Optimization Methods:** Users can configure the simulation to run various optimization algorithms, including Random, Greedy, Genetic Algorithms (GA), Q-Learning, and Deep Reinforcement Learning (DQN, PPO, A2C).

- **Parameter Configuration:** The system allows flexible configuration of initial state (`StartState`) and target stress levels (`TargetStress`), enabling fine control over the simulated therapy.

## Human Study Simulation

In this simulation-based evaluation, **EDPCGRL SpiderVR** demonstrated superior performance compared to traditional search-based methods. The reinforcement learning system adapted more quickly to virtual human responses, presenting fewer spiders to achieve the desired stress levels with high accuracy.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/min_text.png" title="Calm Spider" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/avg_text.png" title="Moderate Spider" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/max_text.png" title="Intense Spider" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## GitHub Repository

Explore the full implementation and extend this project by visiting the [GitHub repository](https://github.com/athar70/EDPCGRL).

## Related Publication

For more detailed information, refer to the paper: [EDPCGRL SpiderVR in Simulation](https://arxiv.org/abs/2110.04146).

## Future Impact

**EDPCGRL SpiderVR in Simulation** highlights the potential for virtual human simulations in personalized therapy. As this research progresses, the framework can be applied to real patients, offering a scalable and adaptable solution for virtual reality therapy across various mental health conditions.
