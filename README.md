# 🛡️ Intrusion Detection Using GANs for Synthetic Attack Data Generation

This project implements a Conditional Generative Adversarial Network (CGAN) to address **class imbalance** in intrusion detection systems. It focuses on generating realistic synthetic attack samples for minority classes using the **UNSW-NB15 dataset**, and evaluating the impact of data augmentation on IDS performance.

---

## 📌 Objectives

- Apply CGANs to generate synthetic attack data for rare attack categories.
- Balance class distribution to improve detection of minority attack types.
- Train and evaluate IDS classifiers (Random Forest, XGBoost) with and without synthetic data.
- Visualize improvements using F1-scores, accuracy.

---

## 🧠 Techniques Used

- **Conditional GAN (CGAN)** with TensorFlow/Keras
- **Data preprocessing**: One-hot encoding, normalization
- **Classifier training**: Random Forest, XGBoost (Scikit-learn, XGBoost)
- **Evaluation**: Accuracy, F1-score, Confusion Matrix
- **Dataset**: [UNSW-NB15](https://research.unsw.edu.au/projects/unsw-nb15-dataset)

---
