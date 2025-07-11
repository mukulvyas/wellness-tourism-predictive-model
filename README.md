# 🧳 Wellness Tourism Package Prediction

A machine learning project to help "Trips & Travel.Com" reduce marketing costs and identify potential customers for a newly launched **Wellness Tourism Package** — an offering designed to enhance customers' well-being through travel.

---

## 🚀 Objective

To build a predictive model that determines the likelihood of a customer purchasing a holiday package, enabling **targeted marketing** instead of random outreach.

---

## 🗃️ Dataset

- **Source**: [Kaggle - Holiday Package Purchase Prediction](https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction/data)
- **Rows**: 4888
- **Columns**: 20 (Customer demographics, behavior, and interactional data)

---

## 🧼 Data Processing

- Handled missing values and duplicates
- Converted data types where required
- Applied label encoding and one-hot encoding
- Performed feature selection
- Train-test split (80-20)

---

## 📊 Exploratory Data Analysis (EDA)

- Visualized distributions of age, salary range, marital status, etc.
- Checked balance of the target variable
- Explored feature importance with respect to the target

---

## 🤖 Model Used

Used a **Random Forest Classifier**, which achieved approximately **93% accuracy** in predicting package purchases.

---

## 🏁 Conclusion

The model helps identify potential buyers with high accuracy, enabling better customer targeting and reduced marketing costs.

---

## 🔧 Tech Stack

- Python
- Pandas, NumPy
- Scikit-Learn
- Seaborn, Matplotlib

---

## 📂 File Structure

```bash
📦Wellness_Tourism_Model
 ┣ 📜Wellness_Tourism_Model.ipynb
 ┣ 📜README.md
```

---

## 💡 Future Improvements

- Try other models like XGBoost or Logistic Regression for comparison
- Apply hyperparameter tuning (GridSearchCV, RandomizedSearchCV)
- Build a Streamlit or Flask dashboard for demo deployment


