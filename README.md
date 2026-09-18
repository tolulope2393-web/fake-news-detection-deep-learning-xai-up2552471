# Fake News Detection Using Deep Learning and Explainable AI

## Project Title

**Evaluating the Generalisation and Interpretability of Machine Learning and Deep Learning Models for Fake News Detection**

MSc Artificial Intelligence and Machine Learning  
University of Portsmouth

## Overview

This repository contains the source code developed for my MSc project on text-based fake news detection. The study evaluates three transformer-based deep learning models: BERT, RoBERTa and ELECTRA, using the WELFake dataset.

The models were evaluated using accuracy, precision, recall, F1-score, ROC-AUC and confusion matrices. Error analysis was also conducted to examine misclassified articles.

SHAP (SHapley Additive exPlanations) was applied to the strongest-performing model, RoBERTa, to examine the textual features influencing correct and incorrect predictions.

## Models

- BERT
- RoBERTa
- ELECTRA

## Dataset

WELFake

## Explainability

SHAP (SHapley Additive exPlanations)

## Implementation

The project was implemented in Python using Kaggle Notebooks. Key libraries include PyTorch, Hugging Face Transformers, scikit-learn, pandas, NumPy and SHAP.

## Source Code

The project implementation is available in:

`fakenewsdetection2 (1).ipynb`
