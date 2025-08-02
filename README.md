# Deep Mental: AI-Powered Mental Health Risk Detection

Deep Mental is an AI-powered tool that analyzes Reddit posts for early warning signals of mental health risks. By leveraging transformer models, our system uncovers hidden distress signals and enables proactive support for individuals in need.

## Overview

Mental health issues affect 1 in 5 adults, often remaining undetected in online spaces. Deep Mental applies state-of-the-art AI to social media text, identifying subtle cues suggesting mental health risks. Our goal is to facilitate rapid, proactive care rather than reactive intervention.

## Features

- Multi-label classification of mental health risk signals in Reddit-like posts
- Automated support suggestions based on detected risks
- Live prediction demo for user-entered text
- High-performance transformer-based model (RoBERTa)

## Dataset & Risk Categories

- **Dataset:** CLPsych 2021 Reddit dataset
- **Risk Categories:**
  - Suicidal Thoughts
  - Depressive Language
  - Anxiety Markers
  - Substance Use Signals
  - Social Isolation Cues
  - Economic Stress Signs

## Model Architecture

- **Input:** Reddit posts (text)
- **Core:** Transformer-based RoBERTa architecture
- **Classification Head:** 2 dense layers with dropout, tuned thresholds
- **Output:** Simultaneous detection across all 6 categories

## Performance Metrics

- **Training Time:** ~3 hrs on GPU
- **ROC AUC:** Generally 0.85–0.98 across categories
- **F1 Scores:** Especially strong for Depressive Language and Economic Stress
- **Overfitting Prevention:** Dropout and early stopping
- **Class Imbalance:** Optimized classification thresholds
- **Text Handling:** Truncation to 256 tokens

**Support Suggestions:**  
Depressive Language: Journaling and CBT may help manage low mood.

## Challenges & Solutions

| Challenge         | Solution                |
|-------------------|------------------------|
| Class Imbalance   | Threshold optimization |
| Model Overfitting | Dropout, Early stopping|
| Long Text Inputs  | Truncation (256 tokens)|


**Empowering early intervention through AI: Let’s build a proactive mental health support system together.**

---
