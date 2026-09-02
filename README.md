# Hybrid Intelligent IDS/IPS for Cyberattack Detection

## Overview

This project presents a hybrid Intrusion Detection and Prevention System (IDS/IPS) that combines traditional signature-based detection with Machine Learning and Deep Learning techniques.

The system integrates:

- Suricata for network monitoring and rule-based detection
- Random Forest for network traffic classification
- Bidirectional LSTM for temporal pattern analysis
- Hybrid decision fusion
- Automatic Suricata rule generation

## Architecture

Network Traffic
      ↓
   Suricata
      ↓
Data Processing
      ↓
┌──────────────────────────────┐
│      Hybrid Detection        │
├──────────────┬───────────────┤
│ Random Forest│ Bi-LSTM       │
└──────────────┴───────────────┘
      ↓
Decision Fusion
      ↓
Attack Detection / Prevention

## Technologies

- Python
- Suricata
- Random Forest
- Bidirectional LSTM
- Scikit-learn
- TensorFlow / Keras
- Linux
- CICIDS2017 Dataset

## Results

The system achieved:

- F1-Score: > 98%
- False Positive Rate: < 2%

## Author

Nabil Harir

Cybersecurity & Artificial Intelligence Graduate
