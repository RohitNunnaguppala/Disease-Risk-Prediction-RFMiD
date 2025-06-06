# Disease Risk Prediction using RFMiD Dataset

This project explores machine learning techniques to predict disease risk levels based on retinal eye conditions using the **Retinal Fundus Multi-Disease (RFMiD)** dataset.

## 📌 Project Overview

Our research focuses on evaluating the risk of diseases like:
- Diabetic Retinopathy (DR)
- Age-Related Macular Degeneration (ARMD)
- Retinitis Pigmentosa
- Glaucoma
- Other retinal diseases

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

To run the notebooks, install dependencies:

```bash
pip install -r requirements.txt
```

Includes: pandas, numpy, matplotlib, seaborn, scikit-learn, shap, lime, xgboost

## 🧠 Publication

This project was published as part of an academic paper:  
*"Leveraging Machine Learning to Predict Disease Risk Levels from Multiple Eye Condition Indicators"*

## 👨‍💻 Authors

- Rohit Nunnaguppala
- Mudumala Varnika Narayani
- Tejashwini Vadeghar
- Naga Ruthvika Durupudi
- Aiswariya Milan K
- Dr. Jyotsna C.

## 📜 License

This project is licensed under the MIT License.