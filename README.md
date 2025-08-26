# Comparative Analysis of Tree-Based vs Deep Learning Algorithms for STD Prediction

This project presents a comparative study between **tree-based machine learning algorithms** and **deep learning models** for predicting sexually transmitted diseases (STDs). The work was carried out in two phases:  
- Phase I: Random Forest on the original dataset (baseline).  
- Phase II: SMOTE balancing and additional models (Random Forest, Gradient Boosting, MLP, and 1D-CNN).  

---

## 🧪 Methodology
1. **Data Preprocessing**  
   - Encoded categorical variables  
   - Standardized features using `StandardScaler`  

2. **Data Balancing**  
   - Applied **SMOTE (Synthetic Minority Oversampling Technique)**  
   - Ensured balanced distribution of STD-positive and STD-negative cases  

3. **Models Implemented**  
   - 🌲 Random Forest (baseline & resampled)  
   - 🌳 Gradient Boosting  
   - 🤖 Multilayer Perceptron (MLP)  
   - 📊 1D Convolutional Neural Network (1D-CNN)  

4. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-Score  
   - Confusion Matrix  
   - ROC-AUC  
   - 5-Fold Cross Validation  

---

## 📈 Results Summary

| Model                    | Accuracy | Precision | Recall | F1-Score |
|---------------------------|----------|-----------|--------|----------|
| Random Forest (Imbalanced)| 96%      | 0.94      | 0.94   | 0.94     |
| Random Forest (SMOTE)     | 93%      | 0.93      | 0.93   | 0.93     |
| Gradient Boosting         | 84%      | 0.85      | 0.85   | 0.84     |
| MLP                       | 72%      | 0.72      | 0.72   | 0.72     |
| 1D-CNN                    | 76%      | 0.76      | 0.76   | 0.76     |

✅ **Random Forest** (after SMOTE) consistently delivered the best results, while deep learning models showed potential but were limited by dataset size.  

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





