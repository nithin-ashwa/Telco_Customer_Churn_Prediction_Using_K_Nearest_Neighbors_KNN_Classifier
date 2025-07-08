# 📊 Telco Customer Churn Prediction Using K-Nearest Neighbors (KNN) Classifier

This project uses the **K-Nearest Neighbors (KNN)** algorithm to predict customer churn based on the Telco Customer Churn dataset. The goal is to identify which customers are likely to discontinue their service, allowing for targeted retention strategies.

---

## 📁 Dataset

- **Dataset Name:** WA_Fn-UseC_-Telco-Customer-Churn.csv  
- **Source:** [IBM Sample Data](https://www.ibm.com/communities/analytics/watson-analytics-blog/guide-to-sample-datasets/)
- **Target Variable:** `Churn` (1 - customer left, 0 - customer stayed)

---

## 🔍 Project Workflow

### 1. 📥 Data Loading
- Dataset is loaded using `pandas` and the basic structure is explored using `.info()` and `.head()`.

### 2. 🔠 Categorical Encoding
- All categorical features are encoded using **Label Encoding**.

### 3. 🧪 Train-Test Split
- Data is split into training and testing sets using `train_test_split` from `sklearn.model_selection`.

### 4. 🤖 Model Training
- A **K-Nearest Neighbors (KNN)** classifier is trained on the training set.
- `n_neighbors=150` is used (can be tuned for better accuracy).

### 5. 📈 Model Evaluation
- The model is evaluated using:
  - **Accuracy Score**
  - **Confusion Matrix**

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

To install all required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
