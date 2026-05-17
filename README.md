# Credit Default Risk Prediction Pipeline

## 📌 Project Overview
This project focuses on building a robust Machine Learning pipeline to predict **Credit Default Risk**. In financial lending, failing to identify a defaulting client (a False Negative) is significantly more expensive than misclassifying a good client. Therefore, this project evaluates multiple classification algorithms, prioritizing **Recall (Sensitivity)** and **F1-Score** to optimize risk management.

## 📊 Dataset Profile & Imbalance Challenge
The dataset used reflects a real-world financial scenario with a severe class imbalance:
* **Non-Defaulters (Class 0):** 91.2%
* **Defaulters (Class 1):** 8.8%

To prevent model bias toward the majority class, data balancing techniques (**SMOTE** and **Random Under-Sampling**) were incorporated and evaluated within the pipeline.

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Engineering & EDA:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning Frameworks:** Scikit-Learn, XGBoost, LightGBM
* **Imbalanced Data Handling:** Imbalanced-learn (SMOTE)

## 🚀 Pipeline Architecture
1. **Exploratory Data Analysis (EDA):** Analyzed feature distributions, detected correlations, and quantified the extent of class imbalance.
2. **Data Preprocessing:** Managed missing values, encoded categorical variables, and normalized features for model readiness.
3. **Resampling Strategies:** Applied Synthetic Minority Over-sampling Technique (SMOTE) combined with Random Under-Sampling to create an optimized training baseline.
4. **Model Exploration & Evaluation:** Trained and benchmarked a diverse set of classifiers:
   * Logistic Regression
   * Random Forest
   * LightGBM
   * XGBoost
5. **Hyperparameter Tuning:** Optimized decision thresholds to maximize the identification of true defaulters while balancing precision.

## 📈 Key Findings & Results
* Conventional accuracy metrics were discarded in favor of **Recall** and **F1-Score** due to the high business cost of missed defaults.
* Boosting algorithms (**XGBoost and LightGBM**) combined with resampling strategies yielded the most reliable decision boundaries, significantly capturing the minority default class compared to un-sampled baselines.
