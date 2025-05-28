# ProbDefault_LogisticRegression

[![GitHub stars](https://img.shields.io/github/stars/Chengyueminga/ProbDefault_LogisticRegression?style=social)](https://github.com/Chengyueminga/ProbDefault_LogisticRegression/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Chengyueminga/ProbDefault_LogisticRegression?style=social)](https://github.com/Chengyueminga/ProbDefault_LogisticRegression/network/members)

### A transparent baseline model for default prediction – built for teaching and evaluation.

---

### Overview

This project explores the application of **logistic regression** to credit scoring, using data from Kaggle’s [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk) competition. The focus is on building a simple and interpretable **Probability of Default (PD)** model, suitable for classroom instruction and for demonstrating threshold-based tradeoffs in binary classification.

The notebook is structured as a complete teaching module, with well-labeled sections, model interpretation, and visualizations. Code blocks are annotated in an appendix that links back to the main notebook content.

---

### Teaching Objectives

This project is designed for students and early-career analysts interested in:

- Modeling PD using logistic regression with imbalanced classes
- Understanding how threshold choice affects precision and recall
- Using ROC curves and confusion matrices for evaluation
- Practicing real-world model building from public credit data

---

### Notebook Structure

| Section | Description |
|---------|-------------|
| **1.1** | Introduction and teaching context |
| **1.2** | Data overview and target variable |
| **2.1** | Preprocessing and initial inspection |
| **2.2** | Feature selection and transformations |
| **2.3.1** | Logistic regression with `class_weight='balanced'` |
| **2.3.2** | Threshold tuning and ROC visualization |
| **3.3** | PD distribution and confusion matrix |
| **Appendix A** | Annotated code blocks linked to each section |

---

### Model Highlights

- Transparent logistic model structure  
- Threshold tuning with clear recall/precision tradeoffs  
- Probability plots to simulate loan approval cutoff scenarios  
- ROC curve and AUC for performance tracking

---

### Dataset Citation

> Sergey Kharitonov. (2018). *Home Credit Default Risk*. Kaggle.  
> [https://www.kaggle.com/competitions/home-credit-default-risk](https://www.kaggle.com/competitions/home-credit-default-risk)

---

### External Links

- [Kaggle Dataset](https://www.kaggle.com/competitions/home-credit-default-risk)  
- [SSRN Working Paper (coming soon)](#)

---

### License

This project is released under the MIT License and intended for educational and non-commercial use.

---

### Disclaimer

This project was conducted in a personal capacity as an **independent researcher**. All views, analyses, and interpretations presented here are my own and do not represent the views of any current or former employer. The project is for educational and non-commercial use only.

---

### Contribute & Engage

If you find this notebook helpful, feel free to **fork** the repository or give it a ⭐️.  
Feedback and suggestions are always welcome — contributions to improve the educational value are especially appreciated.
