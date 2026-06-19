# 💊 PHEMS Hackathon — Pediatric Sepsis Early Prediction

![Healthcare](https://img.shields.io/badge/-Healthcare-1a1b26?style=flat-square&logoColor=c0caf5) ![ICU](https://img.shields.io/badge/-ICU-1a1b26?style=flat-square&logoColor=c0caf5) ![Early Warning Systems](https://img.shields.io/badge/-Early%20Warning%20Systems-1a1b26?style=flat-square&logoColor=c0caf5) ![Classification](https://img.shields.io/badge/-Classification-1a1b26?style=flat-square&logoColor=c0caf5) ![LightGBM](https://img.shields.io/badge/-LightGBM-1a1b26?style=flat-square&logoColor=c0caf5)

![Banner](./banner.png)

> [!IMPORTANT]
> **Host:** `PHEMS Consortium`  
> **Platform Link:** [Kaggle Competition](https://www.kaggle.com/competitions/phems-hackathon)  
> **Dataset Link:** [Kaggle Dataset](https://www.kaggle.com/competitions/phems-hackathon/data)  
> **Domain:** `ICU & Critical Care AI`

## 📖 Overview

Early warning system for pediatric sepsis in the ICU. The goal is to detect sepsis onset hours before clinical diagnosis using EHR telemetry.

## ⚙️ Standard Pipeline Workflow

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'background': '#0f0f12', 'primaryColor': '#1a1b26', 'edgeLabelBackground':'#11111b', 'tertiaryColor': '#1a1b26'}}}%%
flowchart LR
    A[Data Gathering] --> B[Preprocessing & EDA]
    B --> C[Model Training]
    C --> D[Inference & Submission]
    style A fill:#1e1e24,stroke:#7aa2f7,stroke-width:2px,color:#c0caf5
    style B fill:#1e1e24,stroke:#bb9af7,stroke-width:2px,color:#c0caf5
    style C fill:#1e1e24,stroke:#f7768e,stroke-width:2px,color:#c0caf5
    style D fill:#1e1e24,stroke:#9ece6a,stroke-width:2px,color:#c0caf5
```

## 🗂️ Notebook Architecture & Inventory

### 📂 Inference & Submission
*Prediction pipeline and Kaggle submission file generation.*

| Script / Notebook | Type | Versions | Average Size | Core Stack / Techniques |
|:------------------|:-----|:---------|:-------------|:------------------------|
| 📄 [LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_Inference](./Inference%20%26%20Submission/LightGBM_LightGBM_XGBoost_XGBoost_CatBoost_SVM_Inference.ipynb) | Single Notebook | `v1` | `29 KB` | `LightGBM, XGBoost, CatBoost` |

---

## 🚀 Navigation & Usage Guidelines

> [!TIP]
> 1. **EDA & Preprocessing**: Verify data loaders, actigraphy or DICOM image transformations before model training.
> 2. **Training & Optimization**: Check model definition parameters and training logs to reproduce network weights.
> 3. **Inference & Post-Processing**: Run final pipelines to verify predictions and check submission formats.


---

> *"Sepsis is a silent predator; the algorithm races against the fading pulse."*
>
> — **Vigneshwaran S**
