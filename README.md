# 🧬 Chemotherapy Resistance Predictor

🎓 Final project for the **Integrative Data Analysis** course at Freie Universität Berlin.

## 🧠 Overview

This project leverages **multi-head attention mechanisms** — inspired by Transformer architectures—to predict whether a patient will be resistant or sensitive to chemotherapy, using **proteomics data** as input.

## 🛠 Technologies Used

| Category     | Tools / Libraries                       |
|--------------|------------------------------------------|
| Language     | Python                                   |
| ML/DL        | PyTorch, Scikit-learn, NumPy, Pandas     |
| Visualization| Seaborn, Matplotlib                      |
| Architecture | Multi-Head Attention Network             |


## 📊 Dataset

The dataset consists of **proteomic profiles of patients**, annotated with their response to chemotherapy (resistant or sensitive). Preprocessing steps include:

- Normalization
- Label encoding
- Train/test split

## 🧠 Model Architecture

- Input: Protein expression vectors
- Layers:
  - Multi-Head Self-Attention
  - Fully connected layers
  - Dropout layers
  - Output layer with sigmoid activation
- Loss: Binary Cross Entropy
- Optimizer: Adam

## 📈 Results

Training and evaluation metrics including accuracy, ROC-AUC, and confusion matrix are visualized in the notebook.

