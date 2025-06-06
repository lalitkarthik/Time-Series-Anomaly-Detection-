# Time Series Anomaly Detection: TS2Vec and DCDetector

This repository presents a comparative reproduction study of two research papers focused on **unsupervised time series anomaly detection**:

- **TS2Vec**: A universal time series representation learning model based on hierarchical contrastive learning.
- **DCDetector**: A dual-branch attention-based contrastive model specifically designed for anomaly detection.

---

## 🧠 Overview of the Papers

### 📌 TS2Vec: Universal Time Series Representation

TS2Vec introduces a **hierarchical contrastive learning** approach to learn timestamp-level representations across multiple temporal resolutions. It provides robust embeddings suitable for tasks like classification, forecasting, and anomaly detection — without requiring labeled data.

### 📌 DCDetector: Dual Attention Contrastive Anomaly Detection

DCDetector is tailored for anomaly detection using a **dual-branch architecture**. It applies **temporal and feature attention mechanisms** with contrastive learning to distinguish between normal and abnormal time series patterns, achieving high precision and recall across various benchmark datasets.

---

## 🔗 Official GitHub Repositories

- **TS2Vec:** [https://github.com/zhihanyue/ts2vec](https://github.com/zhihanyue/ts2vec)
- **DCDetector:** [https://github.com/DAMO-DI-ML/KDD2023-DCdetector](https://github.com/DAMO-DI-ML/KDD2023-DCdetector)

---

## 📁 Repository Structure

- **📂 `code/`** – Contains implementation of both models (`ts2vec/` and `dcdetector/`).
- **📂 `results/`** – Includes all evaluation metrics and training logs.
- **📂 `original_papers/`** – Contains PDFs of the original TS2Vec and DCDetector research papers.
- **📄 `Deakin_FTP.pdf`** – Our complete literature review, reproduction experiments, comparisons, and findings.

---

## 📌 Notes

- All results were obtained following the official paper configurations as closely as possible.
- Experiments were run on Google Colab with NVIDIA Tesla T4 GPU support.

---
