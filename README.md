# cancer-prognosis-ml
Cancer Patient Status Prediction using Machine Learning. Built with Python (Scikit-Learn, Ensemble Models) to classify patient survival outcomes (Alive/Deceased) based on clinical features like Cancer Type, Stage, and Treatment Modalities. Achieved ~72.5% accuracy with Gradient Boosting.
# Cancer Patient Status Prediction

An end-to-end Machine Learning project to predict cancer patient survival status (`Alive` or `Deceased`) using a large-scale clinical dataset (100,000 rows). This project explores data cleaning, feature engineering (handling categorical variables & scaling), and comprehensive model evaluation.

## Key Features
- **Exploratory Data Analysis (EDA):** Visualized distribution of patient counts across different cancer types and survival groups.
- **Data Preprocessing:** Handled high-cardinality features using One-Hot Encoding and applied feature scaling (`StandardScaler`) to prevent data leakage.
- **Model Training & Evaluation:** Implemented and compared multiple classifiers including Logistic Regression, Decision Trees, Random Forest, AdaBoost, and XGBoost.
- **Top Performer:** Finalized **Gradient Boosting Classifier**, achieving an **Accuracy of ~72.5%** and an **F1-Score of ~79.5%**.

## 📊 Feature Importance Insights
Based on the final model evaluation:
1. **Stage IV** emerged as the single most critical feature with an importance score of **0.36**.
2. **Lung Cancer** was the highest-weighted cancer type affecting patient status predictions.
3. Disease progression at the time of diagnosis (Stages II, III, and IV) holds the most significant predictive power.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib, XGBoost

## 📂 Project Structure
- `Cancer_Prediction.ipynb` - Core Jupyter Notebook with full code, analysis, and visualizations.
- `cancer_patient_data.csv` - Clinical dataset (Dropped/Ignored if >100MB).
