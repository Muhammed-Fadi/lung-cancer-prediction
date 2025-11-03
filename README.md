## 🩺 Lung Cancer Survival Prediction Using Diagnostic Data  

This project leverages **machine learning and data science** to forecast patient survival outcomes based on clinical and diagnostic information.  
It encompasses the complete workflow — from **data cleaning and exploration** to **model training, evaluation, and deployment** — ensuring robust and interpretable healthcare predictions.

---

### 🚀 Project Pipeline  

1. **Data Preprocessing**  
   - Addressed missing values using `SimpleImputer`  
   - Detected and capped outliers via the **IQR technique**  
   - Encoded categorical features using Label Encoding and One-Hot Encoding  
   - Handled class imbalance with **SMOTE** and random undersampling  

2. **Exploratory Data Analysis (EDA)**  
   - Generated descriptive statistics for numerical and categorical variables  
   - Visualized distributions and relationships through histograms, boxplots, and correlation heatmaps  
   - Examined class imbalance and key predictive features  

3. **Model Development**  
   - Built and tested multiple classification algorithms:  
     - Logistic Regression  
     - Random Forest  
     - Gradient Boosting  
     - Support Vector Machine (SVM)  
     - XGBoost  

4. **Model Evaluation**  
   - Used metrics including Accuracy, Precision, Recall, F1-score, and ROC–AUC  
   - Visualized performance with ROC curves  
   - Compiled results into a comprehensive model comparison table  

5. **Model Export**  
   - Saved the top-performing model as `best_model_pipeline.pkl`  
   - Stored evaluation metrics in `model_comparison.csv` for future reference  

---

### 🧠 Tools & Technologies  

- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, XGBoost  
- **Environment:** Jupyter Notebook  

---

### 📁 Project Structure  

| File Name                      | Description |
|--------------------------------|-------------|
| `dataset_med.csv`              | Contains patient diagnostic and treatment data |
| `lung_cancer_ml_pipeline.ipynb`| Main notebook for data analysis, model building, and evaluation |
| `best_model_pipeline.pkl`      | Serialized version of the best-trained model |
| `model_comparison.csv`         | Comparison summary of all tested models |
| `README.md`                    | Project overview document |

---

### 💡 Key Findings  

- The dataset required substantial preprocessing to handle missing values and class imbalance.  
- Ensemble models such as **Random Forest**, **Gradient Boosting**, and **XGBoost** provided the most accurate and stable results.  
- The final workflow ensures **reproducibility, interpretability, and scalability** for healthcare prediction systems.
