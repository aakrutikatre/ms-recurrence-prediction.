# Multiple Sclerosis Recurrence Prediction using LLaMA 3 & BERT

This project explores the use of large language models (LLMs) like **LLaMA 3** and **BERT** to predict **multiple sclerosis (MS) relapse** events. It combines transformer-based feature embeddings with classical and deep learning models to classify patients based on recurrence risk.

## 📁 Notebooks

- `Try_classification_llama.ipynb`  
  Initial version using LLaMA embeddings for classification tasks.

- `Try_classification_llama_text2.ipynb`  
  Added further feature extraction and early model comparison.

- `Try_classification_llama_text2_v2.ipynb`  
  Refined preprocessing, included CNN and RNN classifiers.

- `Try_classification_llama_text2_v3.ipynb`  
  Final version: integrated BERT, LLaMA 3, and comparative evaluation using XGBoost, CNN, and RNN; achieved an **8% improvement in F1 score** over classical ML baselines.

## 🧠 Model Overview

- **Embedding Models**: BERT, LLaMA 3
- **Classifiers Used**: XGBoost, CNN, RNN
- **Key Metric**: F1 Score
- **Result**: Transformer-based embeddings improved F1 by ~8% compared to traditional features.

## 🧪 Requirements

Install required Python packages:

```bash
pip install -r requirements.txt
