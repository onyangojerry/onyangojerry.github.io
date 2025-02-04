---
layout: default
title: Methodology
---

# 🏗️ Methodology

## Data Pipeline
1. Logs are collected from a **relational database**.
2. Features include:
   - **Timestamps**
   - **IP addresses**
   - **Request types**
   - **Geolocation data**
3. Data is cleaned to remove duplicates and irrelevant logs.

## Neural Network Architecture
### Model Selection:
- **LSTMs (Long Short-Term Memory)** for **sequential pattern detection**.
- **CNNs (Convolutional Neural Networks)** for **pattern-based anomaly detection**.

### Training Process:
- **Supervised Learning**: Labeled logs for attack/non-attack detection.
- **Unsupervised Learning**: Autoencoders for detecting unknown attack patterns.

## Deployment Plan
- **Model integrates with a dashboard**.
- Real-time anomaly alerts.
- API for external monitoring tools.

🚀 **Stay tuned for more updates!**
