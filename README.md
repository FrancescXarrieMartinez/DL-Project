# DL-Project: Initial Setting Time Prediction for Calcium Aluminatum Cement

This repository contains the full pipeline used to predict the **initial setting time** of calcium aluminatum cement using feature engineering, dimensionality reduction (PCA & Autoencoders), and deep learning (MLPs).

---

## 📁 Files

- `cement_concat_raw_final.pkl`: Raw dataset with ~60 features.
- `cement_concat_enhanced_final.pkl`: Feature-engineered dataset with ~500 features.
- `DL_Pipeline_Final.ipynb`: Complete, Colab-compatible notebook. Already executed with full visual outputs.
- `Data_Codes.ipynb`: Draft notebook with scattered code snippets related to data processing and feature engineering. **Not a runnable pipeline** — executing it will likely break. It serves only as a reference to inspect fragments of the logic used during dataset preparation, but **should not be seen as a step-by-step guide**.


---

## 🔐 Data Privacy Notice

Due to confidentiality agreements with Cementos Molins, the raw data and full preprocessing code **cannot be shared**. However, for transparency and educational purposes, we include:

🔎 `Data_Codes.ipynb`: A collection of code snippets and partial outputs used during data cleaning, compositional transformations, augmentation, and feature engineering.  
Note: This notebook is **not executable as a pipeline** but serves as a reference to understand the preprocessing workflow.

---

## 🚀 Quick Start

> **✅ Notebook is already executed with results and plots.**
>
> To reproduce the pipeline from scratch:

1. Download:
   - `DL_Pipeline_Final.ipynb`
   - `cement_concat_raw_final.pkl`
   - `cement_concat_enhanced_final.pkl`

2. Open the notebook in [Google Colab](https://colab.research.google.com/).

3. Follow the instructions to upload both `.pkl` files when prompted.

4. Run all cells (runtime: **30–40 minutes**, depending on hardware).

---

## 🛠️ Environment & Dependencies

Colab installs required libraries automatically:

```bash
!pip install --quiet umap-learn torch scikit-learn matplotlib seaborn statsmodels
