---
layout: page
title: Emotion Recognition with MLSTM-FCN
description: Predicting Emotional States Using Physiological Signals with Multivariate LSTM-FCN
img: assets/img/Emotions.gif
importance: 4
category: work
related_publications: false
github: https://github.com/athar70/MLSTM
hashtags: [DL, SP]
---

## Overview

**Emotion Recognition with MLSTM-FCN** leverages **Multivariate LSTM-FCNs** for time series classification to predict emotion-related features such as **valence** and **arousal** from **physiological signals** like Galvanic Skin Response (GSR), Respiration, Photoplethysmography (PPG), and Temperature. Using the DEAP dataset, which contains data from **32 subjects** watching **40 video clips**, this project demonstrates how machine learning can be used to classify emotional states based on physiological responses.

This project applies **Multivariate LSTM-FCNs**, a model architecture designed for **time series classification**, to continuous ratings for **valence** and **arousal**, showcasing how physiological data can provide deep insights into emotion recognition.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MLSTM-FCN.png" title="MLSTM-FCN" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Key Features

- **Emotion Recognition from Physiological Signals:** The project uses **Multivariate LSTM-FCNs** to predict **valence** and **arousal** using signals like GSR, PPG, respiration, and temperature, demonstrating how time series models can interpret physiological data for emotion recognition.

- **MLSTM-FCN Model with Oversampling:** The **MLSTM-FCN** model, tailored for time series classification, was trained on the DEAP dataset and enhanced by oversampling techniques to address class imbalance. The oversampling improved classification accuracy, achieving **75.36% for arousal** and **77.81% for valence**.

- **Data Segmentation & Preprocessing:** Data was segmented into 5-second overlapping windows with a 2-second overlap, sampled at 128Hz. Preprocessing included normalization and feature extraction to ensure the data was suitable for the model input.

- **TensorBoard Visualization:** The training process, including metrics like loss, accuracy, and confusion matrices, was logged and visualized using **TensorBoard** for detailed analysis of the model’s performance.

## Study Details

- **Participants:** 32 subjects watched 40 one-minute-long videos while their physiological responses were recorded.
- **Data Processing:** The data was segmented into 25,600 data points with 2-second overlap between 5-second windows. Preprocessing involved normalization using a MinMaxScaler and oversampling to handle class imbalance.
- **Model Training:** The **MLSTM-FCN** model, designed for time series classification, was trained with a **70/30 train-test split**, using the **Adam optimizer** with a learning rate schedule that reduced the learning rate every 100 epochs. The model was trained for **2000 epochs** with batch sizes of **64** and **128**.

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/arousal_confusion_matrix.png" title="Confusion Matrix for Arousal" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/valence_confusion_matrix.png" title="Confusion Matrix for Valence" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## GitHub Repository

Explore the full implementation, including the **MLSTM-FCN model** for time series classification, preprocessing pipeline, and training scripts, by visiting the [GitHub repository](https://github.com/athar70/MLSTM). The repository includes notebooks for both data processing and deep learning methods.

## Acknowledgments

The **Multivariate LSTM-FCN** model used in this project is based on an existing implementation by [Titu1994](https://github.com/titu1994/MLSTM-FCN). Modifications were made to adapt the model to the DEAP dataset and improve performance for emotion recognition using physiological signals.

## Future Impact

This project demonstrates the potential of using **Multivariate LSTM-FCNs** to predict emotional states from physiological signals. These methods can be applied to **emotion recognition systems** in real-time, allowing for personalized and adaptive experiences in domains such as **virtual reality therapy**, **healthcare**, and **entertainment**.
