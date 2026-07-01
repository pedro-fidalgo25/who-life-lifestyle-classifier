# Global Initiative to Understand Worldwide Lifestyle Patterns (WHO-LIFE)

## 📌 Project Overview
An end-to-end Machine Learning pipeline built on the World Health Organization (WHO-LIFE) dataset. The project analyzes, segments, and predicts global citizen profiles based on behavioral, financial, and health characteristics — uncovering geographic and social lifestyle trends to support data-driven, culturally-aware public health and wellness interventions.

## 📊 Methodology & Key Highlights
1. **Data Engineering:** Exploratory Data Analysis (EDA), structural missing-value handling, outlier detection, and feature engineering.
2. **Descriptive Modeling (Clustering):** K-Means (3 clusters) and Self-Organizing Maps (SOM, 6 sub-profiles) to uncover latent lifestyle archetypes, e.g. *"Digital Socialites"*.
3. **Predictive Modeling:** Multi-class classification benchmarking:
   - Gradient Boosting (Optuna-tuned)
   - Random Forest
   - Multi-Layer Perceptron (MLP)
   - Logistic Regression

## 📈 Results & Performance
- **Best model:** Gradient Boosting with Optuna hyperparameter tuning
- **Score:** Kaggle score of 0.82079, indicating low overfit risk and strong generalization
- **Strategic output:** Data-driven action plan recommending targeted digital media marketing, regional financial wellness bundling, and dynamic public-health dashboards

## 🛠️ Tech Stack
- **Language:** Python
- **Data & Visualization:** Pandas, NumPy, Matplotlib, Seaborn
- **ML Frameworks:** Scikit-Learn, LightGBM, Gradient Boosting
- **Optimization:** Optuna

## 📂 Repository Structure
- `project_ML.ipynb` — full pipeline: EDA, clustering, classification, evaluation

## 🎓 Context
Developed for the Machine Learning course, BSc in Information Management, Nova IMS.
