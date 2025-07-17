##  Data Analysis Using Heart Disease Dataset

This project performs **Exploratory Data Analysis (EDA)**, **Feature Engineering**, and applies **Machine Learning models** on a publicly available **Heart Disease dataset** to predict the presence of heart disease in patients.

### 📌 Project Objectives

* Understand the distribution and correlation of features related to heart disease.
* Visualize important trends and relationships using data visualization tools.
* Apply and evaluate classification models like:

  * **Logistic Regression**
  * **K-Nearest Neighbors (KNN)**
  * **Random Forest**
* Interpret model results using metrics like:

  * Accuracy
  * Confusion Matrix
  * Precision, Recall, F1-score

---

### 📁 Files

* `DataAnalysis_Using_Heart_Disease_dataset.ipynb` – Main Jupyter notebook with code and analysis.
* `heart.csv` – Dataset used (replace/add if required).

---

### 🧰 Technologies Used

* Python
* NumPy, Pandas – Data handling
* Matplotlib, Seaborn – Data visualization
* Scikit-learn – Machine learning models & metrics

---

### 📊 Key Insights

* EDA helped identify key features affecting heart disease like cholesterol, resting ECG results, exercise-induced angina, etc.
* Feature scaling and correlation analysis improved model accuracy.
* Among all models, **Random Forest** performed the best in terms of overall accuracy and robustness.

---

### ⚙️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/heart-disease-analysis.git
   cd heart-disease-analysis
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook:

   ```bash
   jupyter notebook DataAnalysis_Using_Heart_Disease_dataset.ipynb
   ```

---

### 📌 Future Enhancements

* Add more models like XGBoost or SVM.
* Implement cross-validation and hyperparameter tuning.
* Build a simple web app using Streamlit or Flask to input user data and predict heart disease risk.

---

### 📚 Dataset Source

Available at: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

---


