# Doctoral-Showcase-SC25
# 🧠 OAAgent: A Multimodal AI Assistant for Precision Osteoarthritis Care

![OAAgent System Overview](workflow.png)

[![SC25 Doctoral Showcase](https://img.shields.io/badge/SC--2025-Doctoral_Showcase-blue.svg)](https://sc25.supercomputing.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![Model Type](https://img.shields.io/badge/Model-Multimodal_Late_Fusion-red.svg)](https://huggingface.co/)
[![Clinical Domain](https://img.shields.io/badge/Domain-Medical_AI--Osteoarthritis-orange.svg)]()

---

## 🎯 Project Overview

**OAAgent** is an interactive, multimodal deep learning framework designed to predict **knee osteoarthritis progression** by integrating clinical variables and radiological data (X-ray, MRI). This system is designed for **early intervention**, **model explainability**, and **trustworthy decision support** in real-world clinical settings.

This work is a collaboration between **Kent State University** and the **Cleveland Clinic**, presented at the **Doctoral Showcase of SC25**.

---

## 🧪 Methodology

- **Data Sources**: FNIH OAI X-ray, MRI, and Clinical data  
- **Task**: 4-class classification of OA progression (`CASE`: JSL+Pain, JSL-only, Pain-only, Non-progressor)
- **Model**: Late Fusion of ResNet image embeddings with clinical MLP
- **Loss Function**: Focal Loss for class imbalance
- **Interpretability**: SHAP decomposition by modality and patient

---

## 📊 Key Results

| Metric               | Value   |
|----------------------|---------|
| **Test Accuracy**     | 75.36%  |
| **F1 Score (Avg.)**   | 0.75    |
| **Modality Analysis** | Adaptive, patient-specific contributions |
| **SHAP Insights**     | Clinical features dominate predictive power in ~60% patients |

---

## 🔍 Contributions

- 📌 Personalized modality weighting via SHAP  
- 📌 Improved performance on minority class with Focal Loss  
- 📌 Clear alignment between individual modality prediction and fused output  
- 📌 Full interpretability pipeline included

---

## 📁 Repository Structure
To be updated
