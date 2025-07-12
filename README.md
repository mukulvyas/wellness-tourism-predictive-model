# 🧳 Wellness Tourism Package Prediction

A machine learning project to help "Trips & Travel.Com" reduce marketing costs and identify potential customers for a newly launched **Wellness Tourism Package** — an offering designed to enhance customers' well-being through travel.

---

## 🚀 Objective

To build a predictive model that determines the likelihood of a customer purchasing a holiday package, enabling **targeted marketing** instead of random outreach.

---

## 🗃️ Dataset

- **Source**: [Kaggle - Holiday Package Purchase Prediction](https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction/data)
- **Rows**: 4888  
- **Columns**: 20  
- Customer demographics, behavior, and interactional data were used.

---

## 🧼 Data Processing

- Handled missing values and duplicates
- Converted data types where required
- Applied encoding techniques for categorical features
- Train-test split (80-20)

---

## 📊 Exploratory Data Analysis (EDA)

- Visualized age, salary range, marital status, etc.
- Checked balance of the target variable
- Explored relationships and correlations

---

## 🤖 Models Evaluated

- Random Forest
- AdaBoost
- Gradient Boosting
- XGBoost

---

## 🏁 Final Results

| Model              | Accuracy | Recall  | Precision | F1 Score | ROC AUC |
|--------------------|----------|---------|-----------|----------|---------|
| Random Forest      | 93.25%   | 67.54%  | 96.99%    | 92.77%   | 83.52%  |
| AdaBoost           | 83.64%   | 22.51%  | 78.18%    | 79.77%   | 60.49%  |
| Gradient Boosting  | 95.60%   | 79.58%  | 97.44%    | 95.43%   | 89.54%  |
| XGBoost            | 95.19%   | 78.53%  | 96.15%    | 95.00%   | 88.89%  |

**Best Model: Gradient Boosting**, offering the highest overall performance in terms of accuracy and F1 score.

---

## 🔧 Tech Stack

- Python
- Pandas, NumPy
- Scikit-Learn
- XGBoost, Seaborn, Matplotlib

---

## 📂 File Structure

```bash
📦Wellness_Tourism_Model
 ┣ 📜Wellness_Tourism_Model.ipynb
 ┣ 📜README.md
 ┗ 📜Travel.csv
```

---

## 💡 Future Improvements

- Perform advanced feature engineering
- Deploy the model using Streamlit or Flask
- Integrate it with a CRM system for real-time predictions
