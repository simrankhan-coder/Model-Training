# 🤖 Model Training — ML Algorithms Collection

A comprehensive collection of Machine Learning model implementations
trained on real-world datasets using Python and Scikit-learn.
Covers supervised, unsupervised learning, and ensemble methods.

---

## 📂 Repository Structure

| # | Notebook | Algorithm Type | Dataset Used |
|---|----------|---------------|--------------|
| 1 | `linear_regression.ipynb` | Supervised — Regression | data.csv |
| 2 | `Logistic_regression_naive_bias_KNN.ipynb` | Supervised — Classification | diabetes.csv |
| 3 | `Project_Based_on_Logistic_Regression.ipynb` | Supervised — Classification | diabetes.csv |
| 4 | `Random_Forest_Implementation.ipynb` | Ensemble — Classification | winequality-white.csv |
| 5 | `Gradient_Boosting.ipynb` | Ensemble — Boosting | winequality-white.csv |
| 6 | `adaboost_implementation.ipynb` | Ensemble — Boosting | winequality-white.csv |
| 7 | `stacking.ipynb` | Ensemble — Stacking | diabetes.csv |
| 8 | `cross_validationo.ipynb` | Model Evaluation | diabetes.csv |
| 9 | `K_means_Clustering.ipynb` | Unsupervised — Clustering | data.csv |
| 10 | `Agglomerative_DBSCAN_clustering.ipynb` | Unsupervised — Clustering | data.csv |

---

## 📊 Datasets Used

### 1. 🩺 Diabetes Dataset (`diabetes.csv`)
- **Source:** Pima Indians Diabetes Dataset (Kaggle/UCI)
- **Task:** Binary Classification
- **Features:** Pregnancies, Glucose, BloodPressure, Insulin, BMI, Age, etc.
- **Target:** Diabetic (1) or Non-Diabetic (0)
- **Models Applied:** Logistic Regression, Naive Bayes, KNN, Stacking, Cross Validation

### 2. 🍷 Wine Quality Dataset (`winequality-white.csv`)
- **Source:** UCI Machine Learning Repository
- **Task:** Classification / Regression
- **Features:** Fixed acidity, Volatile acidity, Citric acid, Residual sugar, pH, Alcohol, etc.
- **Target:** Wine Quality Score (0–10)
- **Models Applied:** Random Forest, Gradient Boosting, AdaBoost

### 3. 📄 Custom Dataset (`data.csv`)
- **Task:** Regression & Clustering
- **Models Applied:** Linear Regression, K-Means, Agglomerative, DBSCAN

---

## 🤖 Models Implemented

### ✅ Supervised Learning
| Model | Type | Notebook |
|-------|------|----------|
| Linear Regression | Regression | `linear_regression.ipynb` |
| Logistic Regression | Classification | `Logistic_regression_naive_bias_KNN.ipynb` |
| Naive Bayes | Classification | `Logistic_regression_naive_bias_KNN.ipynb` |
| K-Nearest Neighbors (KNN) | Classification | `Logistic_regression_naive_bias_KNN.ipynb` |

### ✅ Ensemble Methods
| Model | Type | Notebook |
|-------|------|----------|
| Random Forest | Bagging | `Random_Forest_Implementation.ipynb` |
| Gradient Boosting | Boosting | `Gradient_Boosting.ipynb` |
| AdaBoost | Boosting | `adaboost_implementation.ipynb` |
| Stacking | Meta-Learning | `stacking.ipynb` |

### ✅ Unsupervised Learning
| Model | Type | Notebook |
|-------|------|----------|
| K-Means | Clustering | `K_means_Clustering.ipynb` |
| Agglomerative Clustering | Hierarchical | `Agglomerative_DBSCAN_clustering.ipynb` |
| DBSCAN | Density-Based | `Agglomerative_DBSCAN_clustering.ipynb` |

### ✅ Model Evaluation
| Technique | Notebook |
|-----------|----------|
| Cross Validation (K-Fold) | `cross_validationo.ipynb` |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.x | Core Language |
| Scikit-learn | ML Model Building |
| Pandas | Data Manipulation |
| NumPy | Numerical Computation |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Development Environment |

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/simrankhan-coder/Model-Training.git
cd Model-Training
```

### 2. Install Dependencies
```bash
pip install scikit-learn pandas numpy matplotlib seaborn jupyter
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

### 4. Open any `.ipynb` file and run all cells

---

## 📁 Folder Structure
