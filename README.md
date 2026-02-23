# XAI Hands-On Tutorials

This repository contains practical, hands-on tutorials for Explainable AI (XAI) using Python. The tutorials are structured to provide a progressive introduction to explainability methods across different machine learning modalities.

All notebooks are implemented so they can run **with or without GPU acceleration** and have been **tested on Linux** systems.

---

## Environment Setup

To ensure reproducibility, create the Conda environment using the provided YAML file:

```bash
conda env create -f environment.yml
conda activate xai-tutorials
```

Then launch Jupyter:

```bash
jupyter notebook
```

---

## Tutorials Overview

### 0 — XAI Recap & Tabular Classification (Warm Start)

`0_xai_tabular_classification.ipynb`

This notebook provides:

- A concise recap of core XAI concepts  
- A structured warm start into practical explainability workflows  
- A simple tabular classification example  

It introduces fundamental explanation methods and demonstrates how to apply them in a clear and interpretable way.

---

### 1 — Tabular Regression

`1_xai_tabular_regression.ipynb`

This tutorial extends the previous setup to a **tabular regression** task and explores:

- Differences between classification and regression explainability  
- Interpretation strategies for continuous target variables  
- Practical implementation of regression-specific explanation methods  

---

### 2 — Text Classification & Explainability

`2_xai_text_classification.ipynb`

This notebook focuses on **natural language processing (NLP)** and demonstrates:

- A complete text classification pipeline  
- Token-level and model-level explanation techniques  
- Interpretation of linguistic feature importance  

It illustrates how explainability methods adapt to sequential and high-dimensional textual data.

---

### 3 — Image Classification & Computer Vision Explainability

`3_xai_image_classification.ipynb`

This tutorial addresses **computer vision**, specifically image classification, and introduces:

- CNN-based image classification workflows  
- Gradient-based and perturbation-based explanation approaches  
- Visual attribution methods for interpreting model decisions  

---

## Technical Notes

- All notebooks are designed to run on **CPU-only systems**, but will automatically leverage **GPU acceleration if available**.  
- The codebase has been tested on **Linux environments**.  
- Dependencies are defined in `environment.yml`.

---

## Intended Audience

These tutorials are suitable for:

- Researchers and practitioners entering the XAI domain  
- Students seeking hands-on examples across different data modalities  
- Engineers integrating explainability into ML workflows  

---

## Contributions

Contributions and improvements are welcome.  
Feel free to open an issue or submit a pull request.
