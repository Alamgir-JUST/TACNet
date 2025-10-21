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

## Architecture of the Proposed Approach

<p align="center"> <img src="https://github.com/Alamgir-JUST/TACNet/blob/4ad5373fbb27db8ad5930cb59de69623d12534ee/Architectural%20Diagrm.png"/> </p>

## Algorithm of the Proposed Approach

<p align="center"> <img src="https://github.com/Alamgir-JUST/TACNet/blob/4ad5373fbb27db8ad5930cb59de69623d12534ee/Algorithm.png"/> </p>

## Contact
Md. Alamgir Hossain,
MSc in ICT, IICT, BUET; BSc in CSE, JUST. 
Director, Skill Morph Research Lab., Skill Morph, Dhaka, Bangladesh
Mail: alamgir.cse14.just@gmail.com

Google Scholar: https://scholar.google.com/citations?user=P-_d2XsAAAAJ&hl=en&oi=sra
