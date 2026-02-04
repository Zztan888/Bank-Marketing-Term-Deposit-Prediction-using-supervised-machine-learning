# 🏦 Bank Marketing Term Deposit Prediction

This project implements an AI-driven solution to predict whether a client will subscribe to a term deposit based on the **Bank Marketing** dataset. This analysis helps banking institutions optimize their telemarketing strategies.

---

## 📑 Project Components
* **Dataset:** [UCI Bank Marketing (bank-additional.csv)](https://archive.ics.uci.edu/dataset/222/bank+marketing)
* **Goal:** Binary Classification (Yes/No subscription)
* **Solution:** Machine Learning Classification with Hyperparameter Optimization
* **Language:** Python (Jupyter Notebook)

---

## 📂 Quick Links
* 📓 **Implementation (Code):** [Project1_Subscribe_term_deposit.ipynb](./Project1_Subscribe_term_deposit.ipynb)
* 📄 **Full Analysis Report:** [Project_Report_1.pdf](./Project_Report_1-git.pdf)
* 📊 **Dataset Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing)

---

## 🛠️ Project Tasks & Implementation

### 1. AI Solution Identification
The problem is addressed using supervised machine learning. Various classification models (such as Random Forest, XGBoost, or Logistic Regression) were evaluated to determine the most effective predictor for client behavior.

### 2. Parameter Optimization
To maximize performance, hyperparameter tuning was performed (using techniques like Grid Search or Random Search). Key parameters optimized include:
* Learning rates
* Tree depth / Estimators
* Regularization strengths

### 3. Implementation Workflow
The solution in `Project1_Subscribe_term_deposit.ipynb` follows these steps:
* **Exploratory Data Analysis (EDA):** Visualizing client demographics and contact history.
* **Feature Engineering:** Encoding categorical variables and scaling numerical features.
* **Model Training:** Implementing the optimized classification algorithm.
* **Evaluation:** Assessing performance via Accuracy, Precision, Recall, and F1-Score.

---

## 📈 Results & Analysis
The model's performance reveals key indicators that drive term deposit subscriptions, such as:
* **Duration:** The length of the last contact highly correlates with success.
* **Economic Indicators:** Impact of employment variation rates and consumer confidence.

---

## 💡 Future Improvements
To further enhance the prediction accuracy, the following improvements are proposed:
1. **Handling Class Imbalance:** Implementing SMOTE (Synthetic Minority Over-sampling Technique) to better represent the "Yes" subscription cases.
2. **Feature Selection:** Utilizing Recursive Feature Elimination (RFE) to remove noisy data.
3. **Ensemble Methods:** Combining multiple models to reduce variance and bias.

---

## 🚀 How to Run
1. Download the `bank-additional.csv` from the UCI link above.
2. Install the required Python libraries:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
