# 📚 Machine Learning Revision

> A structured, hands-on Machine Learning revision repository covering mathematical foundations, core ML algorithms, model evaluation, preprocessing, and practical implementation with Python and scikit-learn.

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikit-learn)](https://scikit-learn.org/)
[![Google Colab](https://img.shields.io/badge/Open%20in-Colab-F9AB00?logo=googlecolab)](https://colab.research.google.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 🎯 About

**Machine Learning Revision** is a practical study repository built to strengthen both the **theoretical understanding** and **implementation skills** required for Machine Learning.

The material follows a progressive path:

**Mathematics → ML Fundamentals → Supervised Learning → Advanced ML → Interview Preparation**

Each notebook is designed to connect concepts with implementation through explanations, mathematical intuition, Python code, experiments, and revision questions.

---

## 🗺️ Learning Roadmap

| Session | Topic | Google Colab |
|---|---|---|
| **Day 1** | Linear Algebra for ML | [Open in Colab](https://colab.research.google.com/github/shreya1111/ml-revision/blob/main/notebooks/Day01_Linear_Algebra_for_ML.ipynb) |
| **Day 2** | Calculus and Optimization | [Open in Colab](https://colab.research.google.com/github/shreya1111/ml-revision/blob/main/notebooks/Day02_Calculus_and_Optimization.ipynb) |
| **Day 3** | Probability and Statistics | [Open in Colab](https://colab.research.google.com/github/shreya1111/ml-revision/blob/main/notebooks/Day03_Probability_and_Statistics.ipynb) |
| **Day 4** | ML Fundamentals and Preprocessing | [Open in Colab](https://colab.research.google.com/github/shreya1111/ml-revision/blob/main/notebooks/Day04_ML_Fundamentals_and_Preprocessing.ipynb) |
| **Day 5** | Linear Regression and Regularization | [Open in Colab](https://colab.research.google.com/github/shreya1111/ml-revision/blob/main/notebooks/Day05_Linear_Regression_and_Regularization.ipynb) |
| **Day 6** | Classification Fundamentals | [Open in Colab](https://colab.research.google.com/github/shreya1111/ml-revision/blob/main/notebooks/Day06_Classification_Fundamentals.ipynb) |
| **Day 7** | Decision Trees and Random Forest | [Open in Colab](https://colab.research.google.com/github/shreya1111/ml-revision/blob/main/notebooks/Day07_Decision_Trees_and_Random_Forest.ipynb) |
| **Day 8** | SVM and Kernel Methods | [Open in Colab](https://colab.research.google.com/github/shreya1111/ml-revision/blob/main/notebooks/Day08_SVM_and_Kernel_Methods.ipynb) |
| **Day 9** | Ensemble Learning | [Open in Colab](https://colab.research.google.com/github/shreya1111/ml-revision/blob/main/notebooks/Day09_Ensemble_Learning.ipynb) |

---

## ☁️ Run in Google Colab

Every notebook can be opened directly in **Google Colab**, so you can study and execute the code without configuring a local Python environment.

> **Note:** Colab links use this repository's expected GitHub path: `shreya1111/ml-revision`. If you choose a different GitHub username or repository name, update the links in `README.md`.

---

## 🚀 Getting Started Locally

### 1. Clone

```bash
git clone https://github.com/shreya1111/ml-revision.git
cd ml-revision
```

### 2. Create a virtual environment

**Windows**
```bash
python -m venv .venv
.venv\Scripts\activate
```

**Linux / macOS**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter

```bash
jupyter notebook
```

Then open the required notebook from `notebooks/`.

---

## 🧠 Study Workflow

```text
Learn
  ↓
Close the Notes
  ↓
Active Recall
  ↓
Implement
  ↓
Experiment
  ↓
Debug
  ↓
Explain
  ↓
Interview Question
```

The objective is to move from **passive familiarity → active understanding → implementation ability**.

---

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- XGBoost
- Google Colab

---

## 📂 Repository Structure

```text
ml-revision/
│
├── notebooks/
│   ├── Day01_*.ipynb
│   ├── Day02_*.ipynb
│   ├── ...
│   └── Day09_*.ipynb
│
├── resources/
│   └── Machine Learning Revision.pdf
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## 📈 Core Topics

### Mathematical Foundations
- Linear Algebra
- Vectors and Matrices
- Matrix Operations
- Rank and Norms
- Derivatives and Gradients
- Chain Rule
- Optimization
- Gradient Descent
- Probability
- Bayes' Theorem
- Random Variables
- Variance and Covariance
- Probability Distributions

### Machine Learning Fundamentals
- AI vs ML vs Deep Learning
- Supervised and Unsupervised Learning
- Train / Validation / Test Splits
- Overfitting and Underfitting
- Bias–Variance Tradeoff
- Missing-Value Handling
- Outlier Detection
- Encoding
- Feature Scaling
- Feature Engineering
- Feature Selection
- Pipelines

### Supervised Learning
- Linear Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression
- Logistic Regression
- K-Nearest Neighbors
- Naive Bayes
- Decision Trees
- Random Forest
- Support Vector Machines

### Ensemble Learning
- Bagging
- Boosting
- AdaBoost
- Gradient Boosting
- XGBoost
- LightGBM
- CatBoost

### Model Evaluation
- MAE
- MSE
- RMSE
- R²
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC

---

## 🎓 Interview Preparation

Use the notebooks for interview revision around:

- Algorithm intuition
- Mathematical foundations
- Model assumptions
- Bias vs variance
- Model selection
- Hyperparameters
- Evaluation metrics
- Practical ML scenarios
- Common interview questions

---

## 📚 Reference Material

The `resources/` directory contains the consolidated Machine Learning revision PDF.

Use the **PDF for quick revision** and the **notebooks for hands-on learning and implementation**.

---

## 🤝 Contributing

Contributions are welcome.

You can contribute by:

1. Adding new ML topics
2. Improving explanations
3. Adding practical implementations
4. Fixing errors
5. Adding interview questions
6. Improving visualizations
7. Adding experiments or datasets

```bash
git checkout -b feature/new-topic
git add .
git commit -m "Add new ML revision topic"
git push origin feature/new-topic
```

Then open a Pull Request.

---

## 📜 License

This project is licensed under the **MIT License**.

See [`LICENSE`](LICENSE) for details.

---

## ⭐ Support

If this repository helps with your Machine Learning preparation, consider giving it a ⭐ on GitHub.

**Learn → Recall → Code → Debug → Explain → Repeat.**
