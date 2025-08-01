# Income Predictor 📊💰

This project predicts whether an individual earns more or less than \$50K annually based on demographic features using machine learning models.

## 📁 Project Overview

This classification problem uses the [UCI Adult Income dataset](https://archive.ics.uci.edu/ml/datasets/adult) to predict income categories (`<=50K` or `>50K`) based on features like education, occupation, hours worked per week, and more.

The project was developed in **Jupyter Notebook** and includes:

- Data cleaning and preprocessing with **Pandas**
- Data visualization using **Seaborn** and **Matplotlib**
- Model building and evaluation using **scikit-learn**
- Model selection through comparison of **Logistic Regression**, **Decision Tree**, and **Random Forest**

## 🛠️ Tools and Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Logistic Regression, Decision Tree, Random Forest)
- Jupyter Notebook

## 📊 Key Results

| Model               | Accuracy | Precision | Recall |
|--------------------|----------|-----------|--------|
| Logistic Regression| 0.8160   | 0.6955    | 0.3842 |
| Decision Tree      | 0.7927   | 0.5773    | 0.4352 |
| Random Forest      | 0.8018   | 0.6037    | 0.4516 |

✅ **Logistic Regression** was chosen as the final model due to its balance of performance and interpretability.

## 📈 Visualizations

- Correlation heatmaps
- Boxplots for feature-label relationships
- Model evaluation metrics (log loss, accuracy, precision, recall)
