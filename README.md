 
# Disease Risk Prediction using RFMiD Dataset

This project explores machine learning techniques to predict disease risk levels based on retinal eye conditions using the **Retinal Fundus Multi-Disease (RFMiD)** dataset.

## 📌 Project Overview

Our research focuses on evaluating the risk of diseases like:
- Diabetic Retinopathy (DR)
- Age-Related Macular Degeneration (ARMD)
- Retinitis Pigmentosa
- Glaucoma
- And other retinal diseases

We apply various classification models such as:
- Decision Trees
- Naive Bayes
- Random Forest
- Gradient Boosting
- KNN
- Stacking Classifier

Explainability techniques like **SHAP** and **LIME** were used to enhance model transparency.

## 📂 Repository Structure

- `notebooks/` – Jupyter Notebooks for training, preprocessing, and model comparison
- `figures/` – Visualizations: Decision Trees, ROC Curves, SHAP, etc.
- `data/` – CSV file with labels (limited due to data policy)
- `presentation/` – PPT and flowchart used for internal or academic presentation

## 📈 Results

- Top-performing model: **Naive Bayes**
- Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, ROC AUC
- SHAP helped interpret disease importance based on features

## 🧪 Requirements

To run the notebooks:

```bash
pip install -r requirements.txt
