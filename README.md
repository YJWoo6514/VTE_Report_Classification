# VTE_Report_Classification
**Automated classification of venous thromboembolism (VTE) from radiology reports using active learning and deep learning**

This repository contains the full codebase, documentation, and sample data configuration used in the study titled:
**"Detection and classification of venous thromboembolism through image test reports analysis using active learning and deep learning"** 


## Overview
This study investigates whether deep learning and machine learning combined with active learning strategies can accurately classify VTE (deep vein thrombosis and pulmonary embolism) findings from free-text radiology reports. The goal is to reduce manual labeling workload and enhance model performance under limited data conditions.


## Models
- ML: SVM, Random Forest, GBM
- Word Embedding: TF, Word2Vec, Doc2Vec
- Active Learning: Random, Uncertainty, Similarity-based
- DL: LSTM, Multi-Kernel 1D-CNN (GloVe), BERT, BioBERT, BioLinkBERT

## 🔓 Publicly Available Components
In accordance with our publication and institutional policy, this repository provides code related only to the deep learning (DL) components of the study. These include:
- Data preprocessing for DL pipelines (tokenization, padding, etc.)
- Model training and evaluation code for:
  - LSTM
  - Multi-Kernel 1D-CNN with GloVe
  - Transformer-based models (BERT, BioBERT, BioLinkBERT)
- Scripts for active learning applied to DL models
- Inference time measurement utilities
> ⚠️ Code related to traditional ML classifiers (e.g., SVM, Random Forest, GBM) and classical feature engineering (e.g., TF, Word2Vec) has not been included in this repository.


## 💻 Environment & Dependencies
This code was developed and tested in Google Colab using a T4 GPU environment.
