# Exploratory Data Analysis and Machine Learning Models for Stroke Prediction

**Wei Fu** — published at the *International Conference on Data Analysis and Machine Learning (DAML 2023)*.
DOI: [10.5220/0000185700003885](https://doi.org/10.5220/0000185700003885) · ISBN: 978-989-758-705-4 · [Author homepage](https://barryway7.github.io)

Stroke is a leading cause of death and long-term disability worldwide. This study combines exploratory data analysis with machine learning models — Logistic Regression, Decision Tree, Random Forest, and XGBoost — to predict stroke risk from clinical features such as age, gender, BMI, and smoking habits.

## Results

| Model | Accuracy | F1 | Recall | Precision |
|---|---|---|---|---|
| **Random Forest** | **94.14%** | **0.9697** | 0.9880 | 0.9520 |
| XGBoost | 84.85% | — | — | 0.1813 |
| Logistic Regression | 72.86% | — | — | — |
| Decision Tree | 72.14% | — | — | — |

Random Forest performed best across all metrics. XGBoost reached a competitive accuracy but suffered from very low precision on the imbalanced data — a reminder that accuracy alone is a misleading metric for clinical prediction tasks.

## Repository contents

- `paper.pdf` — the published conference paper

## Citation

```bibtex
@inproceedings{fu2023stroke,
  author    = {Wei Fu},
  title     = {Exploratory Data Analysis and Machine Learning Models for Stroke Prediction},
  booktitle = {Proceedings of the International Conference on Data Analysis and Machine Learning (DAML 2023)},
  year      = {2023},
  isbn      = {978-989-758-705-4},
  doi       = {10.5220/0000185700003885}
}
```
