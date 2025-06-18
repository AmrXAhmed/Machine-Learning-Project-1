# Machine-Learning-Project-1
# 🧠 Credit Card Loan Repayment Classification

This project aims to classify clients as **{Good, Bad}** based on their loan repayment history using supervised machine learning models. The dataset includes client information and loan payment records.

## 📦 Dataset

- **Source:** [Credit Card Approval Prediction on Kaggle](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction/data)
- **Tables:**
  - `Table 1`: Client demographics and financial information (e.g., name, gender, marital status, income, etc.)
  - `Table 2`: Loan payment history per client

## 🧩 Project Steps

### 1. 📚 Understanding the Dataset
- Carefully explore both tables to understand available features and how clients are represented.
- Analyze the relationship between client information and loan repayment history.

### 2. 🏷️ Label Creation
- Create a binary label `{Good, Bad}` for each client using loan payment records from **Table 2**.
- Choose and justify your labeling criteria based on missed or delayed payments.

### 3. 🔗 Data Integration
- Merge the generated labels with **Table 1** to form a single dataset with features and target labels.

### 4. 🧼 Data Preprocessing
- Handle missing values and clean the data.
- Encode categorical variables appropriately.
- Apply preprocessing techniques such as:
  - Label/One-hot encoding
  - Scaling or normalization
  - Any other techniques used in lab sessions or found via Kaggle tutorials

### 5. 🤖 Modeling
- Train and evaluate at least **three** supervised models:
  - Random Forest
  - Support Vector Machine (SVM)
  - Logistic Regression

### 6. ⚙️ Hyperparameter Tuning
- Use **GridSearchCV** or a similar method to tune model parameters.
- Apply cross-validation to assess generalization performance.

### 7. 📊 Model Evaluation
- For each model, provide:
  - **Confusion matrix**
  - **Classification report** (precision, recall, F1-score)

### 8. 📈 Analysis and Justification
- Choose the best-performing model based on evaluation metrics.
- Justify your choice and discuss the insights obtained from your results.
