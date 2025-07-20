# Facebook Ads Click Prediction

This project predicts whether a user will click on a Facebook ad based on their behavior and demographics using logistic regression.

## 📊 Dataset

- **File:** `Facebook_Ads_2.csv`
- **Features used:**
  - `Time Spent on Site`
  - `Salary`
  - `Clicked` (target variable: 0 = No, 1 = Yes)

## 🔍 Process

1. Load and inspect the data
2. Visualize behavior patterns using `seaborn` and `matplotlib`
3. Build a logistic regression model with scikit-learn
4. Evaluate model performance using accuracy, confusion matrix, and classification report

## ✅ Results

- Achieved ~92% accuracy
- Model is slightly better at predicting users who clicked (class 1)

## ⚙️ Requirements

```bash
pip install pandas seaborn matplotlib scikit-learn
