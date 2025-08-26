# Comparative Analysis of Tree-Based Learning and Deep Learning Algorithms for STD Prediction: An Innovative Approach

## 📌 Project Overview
This project explores the effectiveness of **tree-based machine learning models** and **deep learning algorithms** in predicting **Sexually Transmitted Diseases (STDs)** based on health, demographic, and behavioral data.  

The study provides an **end-to-end analysis** — from data cleaning and feature engineering to model development, evaluation, and interpretation.  
Our objective is to determine whether **tree-based models** (Random Forest, XGBoost, etc.) or **deep learning (MLPs)** perform better, while also assessing interpretability and real-world usability in healthcare decision-making.

---

## 🔹 Motivation
- STDs continue to pose major public health challenges worldwide.  
- Early prediction enables **preventive measures, awareness campaigns, and timely treatment**.  
- Machine Learning (ML) and Deep Learning (DL) provide powerful tools to analyze complex health data.  
- The study compares **classical ML (tree-based models)** with **DL (ANN/MLP)** to evaluate performance trade-offs between **accuracy vs interpretability**.  

---

## 📊 Dataset
- **Source:** [Specify dataset source here, e.g., CDC, WHO, or Kaggle]  
- **Size:** XX,XXX records  
- **Features:**  
  - Demographic: Age, Gender, Education, Income  
  - Behavioral: Number of partners, condom use, drug/alcohol history  
  - Health: Previous diagnoses, symptoms, medical history  
- **Target:** Presence/absence of STD(s) (binary or multi-class depending on dataset).  

---

## 🛠️ Methodology

### 1. Data Preprocessing
- Missing value imputation (mean/mode strategy).  
- Outlier detection using IQR method.  
- Encoding categorical variables (One-Hot, Label Encoding).  
- Standardization/Normalization for deep learning models.  

### 2. Feature Engineering
- Derived risk scores (e.g., partner count × condom usage).  
- Grouped certain categorical responses (e.g., risk behavior categories).  
- Feature selection using correlation analysis and tree-based feature importance.  

### 3. Models Implemented
#### Tree-Based Models:
- **Decision Tree Classifier**  
- **Random Forest**  
- **XGBoost / Gradient Boosting Machines (GBM)**  

#### Deep Learning Models:
- **Artificial Neural Network (ANN/MLP)**  
  - Input layer → Hidden layers (ReLU) → Dropout → Output (Sigmoid/Softmax).  
  - Trained with Adam optimizer, BCE/CE loss.  

---

## 📈 Model Evaluation

### Metrics:
- Accuracy  
- Precision, Recall, F1-score  
- ROC-AUC, PR-AUC  
- Confusion Matrix  
- Computational efficiency (training/inference time)  

### Key Results:
- **Tree-Based Models:**  
  - Achieved high accuracy and strong interpretability.  
  - Feature importance analysis provided valuable insights into health/behavioral risk factors.  
- **Deep Learning Models:**  
  - Outperformed tree models slightly on larger feature sets.  
  - Captured non-linear interactions well.  
  - Required more tuning and lacked interpretability compared to trees.  

---

## 🔑 Insights
- **Tree-Based Models** are ideal for healthcare settings where **explainability** is crucial.  
- **Deep Learning Models** excel with **large, complex datasets**, though they act more like black-box predictors.  
- Key predictors of STD risk included:  
  - Number of sexual partners  
  - Inconsistent condom use  
  - History of other infections  
  - Certain demographic risk factors  

---

## 🩺 Business/Healthcare Impact
- Models can assist in **risk screening tools** at clinics.  
- Helps policymakers target **awareness campaigns** toward high-risk groups.  
- Hybrid approach (Tree models for interpretability + DL for accuracy) is recommended.  

---

## 📂 Repository Contents
- `std_prediction_ml_vs_dl.ipynb` → Jupyter Notebook with full code & analysis.  
- `requirements.txt` → Dependencies for reproducibility.  
- `data/` → (Optional) Dataset or link to dataset source.  
- `results/` → Plots, evaluation reports, confusion matrices.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/std-prediction-ml-vs-dl.git
   cd std-prediction-ml-vs-dl
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Launch Jupyter Notebook
   ```bash
   jupyter lab
4. Open and run std_prediction_ml_vs_dl.ipynb.

---

## 📚 References
- Ngai, E. W. T., Hu, Y., Wong, Y. H., Chen, Y., & Sun, X. (2011). *The application of data mining techniques in medical prediction.* Decision Support Systems.  
- Carcillo, F., Le Borgne, Y. A., Caelen, O., Bontempi, G. (2019). *Combining unsupervised and supervised learning for healthcare classification.* Information Sciences.  
- World Health Organization (WHO). *Global Health Sector Strategy on Sexually Transmitted Infections 2016–2021.*  
- Centers for Disease Control and Prevention (CDC). *Sexually Transmitted Disease Surveillance Reports.*  

---

## 👤 Author
- **Aaysha Sheikh**
- **Shruti Kondekar**
- Project: *Comparative Analysis of Tree-Based Learning and Deep Learning Algorithms for STD Prediction*  
- Year: 2025  
- LinkedIn: www.linkedin.com/in/aaysha-sheikh-b1118123a




