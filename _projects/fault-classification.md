---
title: "Machine Learning-Based Power System Fault Classification"
excerpt: "A research project exploring intelligent fault detection and classification using power system measurements and machine learning."
collection: projects
permalink: /projects/fault-classification/
date: 2026-07-08
layout: single
---

## Overview

Power system faults can threaten the stability, reliability, and safety of electrical networks. Rapid and accurate fault identification enables protective relays and system operators to isolate faults quickly, minimizing equipment damage and service interruptions.

This project investigates the use of machine learning techniques for automatic fault classification using electrical measurements collected from transmission and distribution systems. The objective is to develop intelligent models that improve the speed and accuracy of fault diagnosis while supporting the evolution of adaptive and data-driven protection systems.

## Motivation

Traditional protection schemes rely on fixed relay settings and deterministic algorithms. As modern power systems become more complex due to renewable energy integration, distributed generation, and bidirectional power flow, intelligent fault classification methods can enhance system awareness and operational reliability.

Machine learning offers the ability to learn complex relationships within operational data, enabling more robust fault identification under varying system conditions.

## Objectives

- Develop data-driven models for automatic fault classification.
- Compare conventional analytical methods with machine learning approaches.
- Investigate the influence of feature engineering on model performance.
- Evaluate classifier robustness under varying operating conditions.
- Support the development of intelligent protection systems.

## Fault Categories

The project considers common power system fault types, including:

- Single Line-to-Ground (SLG)
- Line-to-Line (LL)
- Double Line-to-Ground (LLG)
- Three-Phase (LLL)
- Three-Phase-to-Ground (LLLG)
- High-Impedance Faults (HIF)
- Temporary and permanent faults

## Methodology

The proposed workflow includes:

1. Data collection from simulations or historical fault records.
2. Data preprocessing and normalization.
3. Feature extraction from voltage and current waveforms.
4. Feature selection and dimensionality reduction.
5. Machine learning model development.
6. Performance evaluation and comparison.

## Candidate Features

Potential input features include:

- Three-phase voltages
- Three-phase currents
- Positive, negative, and zero-sequence components
- Voltage and current phasors
- Frequency deviation
- Harmonic distortion
- Wavelet transform coefficients
- Statistical time-domain features

## Machine Learning Algorithms

Models considered include:

- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- k-Nearest Neighbors (k-NN)
- Gradient Boosting
- XGBoost
- Artificial Neural Networks (ANN)
- Convolutional Neural Networks (CNN)
- Long Short-Term Memory (LSTM) Networks

## Data Sources

Possible datasets include:

- Simulated fault data generated using power system simulation software
- Digital Fault Recorder (DFR) data
- Protective relay event records
- Phasor Measurement Unit (PMU) data
- Public benchmark datasets

## Performance Evaluation

Model performance may be assessed using:

- Classification Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- Computational Efficiency

## Expected Outcomes

The project aims to develop intelligent classifiers capable of:

- Accurate fault type identification
- Fast response suitable for real-time applications
- Improved protection system reliability
- Enhanced situational awareness
- Better support for condition-based operation and maintenance

## Technologies

- Python
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / PyTorch
- Matplotlib
- Jupyter Notebook
- Git & GitHub

## Research Relevance

Machine learning-based fault classification is an active research area in modern power engineering. It supports the development of:

- Intelligent Protective Relays
- Smart Grids
- Wide-Area Monitoring Systems (WAMS)
- Digital Substations
- Distribution Automation
- Self-Healing Power Systems
- AI-Assisted Grid Operations

## Future Work

Potential extensions include:

- Fault localization using deep learning
- Real-time deployment on embedded protection devices
- Graph Neural Networks for network-wide fault analysis
- Explainable AI (XAI) for protection decision support
- Integration with IEC 61850 digital substations
- Hybrid physics-informed and machine learning models
