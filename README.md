# Sperm Morphology XAI SQS

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Publication](https://img.shields.io/badge/Publication-Springer-green)
![XAI](https://img.shields.io/badge/XAI-ExplainableAI-success)

## Automated Sperm Morphology and Quality Scoring Using Explainable EfficientNet-B0 Driven Framework

This repository presents an AI-powered framework for automated sperm morphology classification and sperm quality scoring using EfficientNet-B0 and Explainable AI techniques.

The framework classifies:
- Normal sperm
- Abnormal sperm
- Non-sperm cells

using the Sperm Morphology Image Dataset (SMIDS).

The project integrates:
- EfficientNet-B0 transfer learning
- Explainable AI using Integrated Gradients
- Sperm Quality Score (SQS) generation
- Comparative DenseNet+CBAM evaluation

---

# Overview

Sperm morphology is a critical factor in male fertility assessment and provides important insights into functional competence. Traditional manual evaluation methods are often:
- time-consuming
- observer-dependent
- prone to human error
- difficult to standardize

This work proposes an AI-driven framework for automated sperm morphology analysis using deep learning and explainable AI techniques.

The framework utilizes a fine-tuned EfficientNet-B0 architecture trained on the Sperm Morphology Image Dataset (SMIDS) to classify:
- normal sperm
- abnormal sperm
- non-sperm cells

Additionally, the framework introduces:
- Explainable AI interpretation using Integrated Gradients
- Sperm Quality Score (SQS) generation
- Comparative evaluation with DenseNet+CBAM

The proposed framework aims to support affordable, scalable, and accessible AI-assisted fertility assessment systems.

---

# Abstract

Sperm morphology provides vital insights into functional competence, a key factor in male fertility assessment. Standard manual evaluation is often slow, time-consuming and observer-dependent, making it prone to human error.

This study develops an AI-powered framework for automated sperm morphology evaluation using a fine-tuned EfficientNet-B0 model trained on the Sperm Morphology Image Dataset (SMIDS). The framework classifies normal sperm, abnormal sperm and non-sperm images while incorporating Explainable AI using Integrated Gradients to highlight important predictive regions.

The proposed model achieved an accuracy of **84.75%**, outperforming the DenseNet+CBAM architecture. Additionally, a novel Sperm Quality Score (SQS) was introduced to convert model predictions into an interpretable fertility assessment metric.

This framework paves the way for affordable, scalable and accessible AI-assisted male fertility assessment systems.

---

# Publication

Published in Springer Nature.

## Citation

Vijayakumar, R., Venkatesan, N. (2026).

**Automated Sperm Morphology and Quality Scoring Using Explainable EfficientNet-B0 Driven Framework**

In:
Karsh, R.K., Murugan, R., Laskar, R.H., Schuller, B.W. (eds)

*Advances on Signal Processing and Computer Vision.*

SIPCOV 2025.

Communications in Computer and Information Science, vol 2848.

Springer, Cham.

DOI:
https://doi.org/10.1007/978-3-032-15809-3_11

Published:
02 February 2026

Publisher:
Springer Nature

---

# Keywords

- Sperm Morphology
- Male Fertility Assessment
- EfficientNet-B0
- Explainable AI
- Integrated Gradients
- Transfer Learning
- Sperm Quality Score
- Deep Learning
- Biomedical Image Analysis

---

# Technical Contributions

## Automated Morphology Classification
- Normal sperm classification
- Abnormal sperm classification
- Non-sperm identification

## Explainable AI
- Integrated Gradients visualization
- Model interpretability
- Prediction explanation

## Fertility Assessment
- Sperm Quality Score (SQS)
- AI-assisted evaluation framework
- Transfer learning pipeline

## Comparative Analysis
- EfficientNet-B0 evaluation
- DenseNet+CBAM comparison
- Performance benchmarking

---

# Model Performance

| Model | Accuracy |
|---|---|
| EfficientNet-B0 | 84.75% |
| DenseNet + CBAM | Lower than proposed model |

---

# Repository Contents

```text
Sperm-Morphology-XAI/

│
├── notebooks/
│   ├── efficientnetb0_xai_sqs.ipynb
│   ├── DenseNet_CBAM.ipynb
│   ├── Integrated_Gradients.ipynb
│   └── Evaluation.ipynb
│
├── images/
├── results/
├── models/
├── README.md
├── requirements.txt
└── LICENSE
```

---

# Technologies Used

- Python
- TensorFlow
- Keras
- EfficientNet-B0
- DenseNet
- CBAM
- Integrated Gradients
- NumPy
- Pandas
- OpenCV
- Matplotlib
- Google Colab

---

# Dataset

Dataset used:
- Sperm Morphology Image Dataset (SMIDS)

The dataset contains sperm microscopy images categorized into:
- Normal sperm
- Abnormal sperm
- Non-sperm cells

Note:
The dataset may be subject to licensing or research restrictions and is therefore not directly uploaded in this repository.

---

# Workflow

1. Dataset preprocessing
2. Image augmentation
3. EfficientNet-B0 fine-tuning
4. Morphology classification
5. Integrated Gradients interpretation
6. Sperm Quality Score generation
7. Comparative evaluation

---

# Explainable AI Results

Integrated Gradients visualization demonstrates that the model focuses on:
- sperm head morphology
- tail structures
- cellular boundaries
- morphological abnormalities

These interpretations improve model transparency and support trustworthy AI-assisted fertility assessment.

---

# Applications

- AI-assisted fertility diagnostics
- Automated sperm morphology analysis
- Clinical reproductive health systems
- Biomedical image analysis
- Explainable medical AI
- Laboratory automation

---

# Future Scope

- Real-time sperm analysis systems
- Clinical fertility assessment tools
- Mobile-assisted diagnostics
- Multi-class morphology grading
- Edge AI deployment
- Clinical validation studies

---

# Authors

- Reshmma Vijayakumar
- Nandakumar Venkatesan

---

# License

This repository is intended for academic and research purposes only.

---

# Acknowledgement

The authors acknowledge Springer Nature and SIPCOV 2025 for supporting the dissemination of this research work.
