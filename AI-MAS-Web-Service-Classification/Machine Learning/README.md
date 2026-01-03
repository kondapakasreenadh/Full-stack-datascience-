Web Service Classification – AI
Overview
Objective: Establish baseline performance for web service classification.
Dataset: Top-N categories (50).
Models:
ML: Logistic Regression, Random Forest, XGBoost
DL: BiLSTM
RoBERTa: Small & Large
DeepSeek: Embedding + Semantic Features
Fusion: DeepSeek + RoBERTa + Classifier
Features: TF-IDF and SBERT embeddings.
Evaluation: Top-1, Top-3, Top-5 accuracy, Macro/Micro F1, confusion matrices.
Balanced Datasets: Fixed 80/10/10 train/validation/test splits.
Reproducibility: Configurations stored in YAML files.
Benchmarking: Leaderboards, Top-K curves, confusion matrices.
Total Models Trained: 18
(6 ML + 2 DL + 4 RoBERTa + 2 DeepSeek + 4 Fusion)
Analysis: Cross-model comparison, ranking quality, and category difficulty.
