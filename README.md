# **Sonar Rock vs Mine Classification using Logistic Regression**

## 📄 **Overview**
This project aims to classify objects as either **Rock** or **Mine** using a **Logistic Regression** model. The dataset contains sonar signal attributes, helping distinguish between the two classes. The primary objective is to develop a predictive system that achieves **high accuracy** for real-world sonar signal classification applications.

---

## 🛠️ **Workflow**

### 1. **Data Preprocessing**
- Loaded the dataset (`sonar_data.csv`) and analyzed its structure.
- Checked for missing values (none were found).
- The dataset includes **208 samples** with **61 columns**.

### 2. **Exploratory Data Analysis**
- Generated statistical summaries of the dataset using `.describe()`.
- Examined class distribution:
  - **111 samples classified as Mine (M)**.
  - **97 samples classified as Rock (R)**.

### 3. **Feature Engineering**
- Separated features (`X`) from the target column (`y`).
- Dropped the target column (column `60`) from the dataset.
- Applied stratified splitting to balance class representation in training and testing sets.

### 4. **Model Training**
- Split the dataset into:
  - **Training set:** 90%
  - **Testing set:** 10%
- Trained a **Logistic Regression** model using `scikit-learn`.
- Achieved:
  - **Training Accuracy:** **83.42%**
  - **Testing Accuracy:** **76.19%**

### 5. **Prediction System**
- Built a pipeline to classify new sonar signals.
- Example input: `(0.0262, 0.0582, ..., 0.6473)`
- Prediction: `['M']` (Mine)

---

## 🧰 **Technologies Used**
- **Programming Language:** Python
- **Key Libraries:**
  - `pandas` for data manipulation.
  - `numpy` for numerical computations.
  - `matplotlib` and `seaborn` for data visualization.
  - `scikit-learn` for model training and evaluation.

---

## 📊 **Results**
- **Training Accuracy:** **83.42%**
- **Testing Accuracy:** **76.19%**
- Visualizations confirm a clear separation between the classes in the dataset.

---

## 🔍 **Key Insights**
- Logistic Regression demonstrated effectiveness in classifying sonar signals with reasonable accuracy.
- The balanced dataset and absence of missing values contributed to the model's performance.
- The prediction system can be extended for real-time sonar signal classification.

---

## 📁 **Project Files**
- 📂 **pdf:** https://github.com/Parththapliyal/Sonar-Rock-vs-Mine-Classification-using-Logistic-Regression-/blob/main/sonar%20rock%20vs%20mine.pdf
- 📂 **Jupyter Notebook:** https://github.com/Parththapliyal/Sonar-Rock-vs-Mine-Classification-using-Logistic-Regression-/blob/main/sonar%20rock%20vs%20mine%20using%20logistic%20regression%20(1).ipynb

---

