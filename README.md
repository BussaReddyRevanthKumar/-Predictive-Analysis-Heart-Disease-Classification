

# 🧠 Predictive Analysis: Heart Disease Classification

This project demonstrates **feature selection**, **model training**, and **evaluation** using a **machine learning model** to predict heart disease presence.

---

### 🚀 Deliverables

* **Notebook**: `predictive_analysis_notebook.ipynb`
* **Dataset**: UCI Heart Disease Dataset (sourced from [here](https://raw.githubusercontent.com/plotly/datasets/master/heart.csv))

---

### 📊 Problem Statement

Predict whether a patient has **heart disease** based on clinical features.

---

### 🔍 Process

1. **Feature Selection**:

   * Correlation heatmap and RandomForest feature importance.

2. **Model Training**:

   * Logistic Regression (baseline)
   * Random Forest Classifier (primary model)

3. **Evaluation**:

   * Accuracy, Precision, Recall, F1-Score
   * Confusion Matrix
   * ROC-AUC Score

---

### 📈 Key Insights

* RandomForestClassifier achieved \~85% accuracy.
* Important features: `cp`, `thalach`, `exang`, `oldpeak`.
* The model shows a balanced performance between precision and recall.

---

### 🏗️ Setup

#### Requirements

* Python 3.x
* Libraries:

  * pandas
  * numpy
  * scikit-learn
  * matplotlib
  * seaborn

Install the dependencies with:

```bash
pip install -r requirements.txt
```

---

### 📂 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git
   ```
2. Navigate to the directory:

   ```bash
   cd heart-disease-prediction
   ```
3. Open the notebook:

   ```bash
   jupyter notebook predictive_analysis_notebook.ipynb
   ```
4. Run cells step-by-step.

---

### 📚 References

* [UCI Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
* [scikit-learn Documentation](https://scikit-learn.org/stable/)
