# TACNet: Temporal Attention Convolutional Network for IoT/IIoT Intrusion Detection

## Overview
TACNet is a novel deep learning framework designed for intrusion detection in IoT (Internet of Things) and IIoT (Industrial Internet of Things) networks. It integrates multi-scale Convolutional Neural Networks (CNN) for spatial feature extraction, Long Short-Term Memory (LSTM) layers for capturing temporal dependencies, and temporal and channel attention mechanisms to prioritize critical features and time steps. TACNet effectively handles high-dimensional network traffic data and class imbalance, achieving state-of-the-art performance across multiple benchmark datasets.

## Features
- Multi-scale CNN for feature extraction across multiple temporal scales.
- LSTM for modeling sequential dependencies in network traffic.
- Temporal and channel attention mechanisms for feature and time-step prioritization.
- Class weight computation to handle imbalanced datasets.
- Evaluation on multiple datasets including:
  - DNN-EdgeIIoT
  - CICIDS 2018
  - N-BaIoT
  - CIC IoT-DIAD 2024
  - TabularIoTAttack-2024
- Supports metrics logging: Accuracy, Precision, Recall, F1-Score.
- Includes adversarial attack evaluation (FGSM & PGD).
