# Open Set Cattle Identification using MobileNetV2 and ArcFace

## Overview
This project presents an Open Set Cattle Identification System based on cattle muzzle biometrics. The system uses MobileNetV2 with ArcFace Loss to learn discriminative embeddings and performs identity matching through Prototype Gallery Matching.

## Features
- MobileNetV2 Backbone
- ArcFace Loss
- 512-D Feature Embeddings
- Prototype Gallery Matching
- Open Set Recognition
- Threshold Optimization
- FAR / FRR Analysis
- ROC-AUC Evaluation
- EER Evaluation
- Grad-CAM Explainability

## Workflow
Dataset → MobileNetV2 + ArcFace → Embedding Extraction → Prototype Gallery → Similarity Matching → Open Set Decision

## Results

| Metric | Value |
|----------|----------|
| AUC | 0.9847 |
| EER | 6.19% |
| Optimal Threshold | 0.55 |
| FAR | 14.98% |
| FRR | 0.17% |

## Explainability
Grad-CAM visualization confirms that the model focuses on discriminative muzzle texture patterns rather than background regions.

## Technologies Used
- Python
- PyTorch
- MobileNetV2
- ArcFace
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib

## Author
Chetan Vedi
MSc Data Science
Amity University Rajasthan
