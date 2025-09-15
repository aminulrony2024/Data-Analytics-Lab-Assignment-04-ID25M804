# Assignment 04 - DA5401  
**Course:** DA5401 - Data Analytics Laboratory 

**Topic:** GMM-Based Synthetic Sampling for Imbalanced Data  

---

## Student Details  
- **Name:** Md Aminul Islam Rony  
- **Roll Number:** ID25M804  

---

## Documentation  

### 🔹 Objective  
The goal of this assignment is to **handle severe class imbalance** in a fraud detection dataset using **Gaussian Mixture Model (GMM)-based synthetic sampling**. We evaluate whether this approach improves classifier performance compared to a baseline model.  

---

### 🔹 Steps Implemented  

1. **Baseline Model (Part A)**  
   - Loaded and analyzed the dataset.  
   - Trained a Logistic Regression classifier on the imbalanced dataset.  
   - Evaluated using Precision, Recall, and F1-score (minority class focus).  

2. **GMM-Based Synthetic Sampling (Part B)**  
   - Fitted a Gaussian Mixture Model (GMM) on the minority class.  
   - Generated synthetic fraud samples to balance the dataset.  
   - Applied Clustering-Based Undersampling (CBU) on the majority class.  
   - Created a balanced dataset using both synthetic minority samples and reduced majority samples.  

3. **Performance Evaluation (Part C)**  
   - Retrained Logistic Regression on the GMM-balanced dataset.  
   - Compared results (Precision, Recall, F1-score) between the **baseline model** and the **GMM-augmented model**.  
   - Discussed improvements in fraud detection performance.  

---

### 🔹 How to Run  

1. Download the dataset from Kaggle:  
   [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
2. Place the dataset in your working directory.  
3. Open the Jupyter Notebook and run all cells in order.  
4. Evaluation metrics and plots will be displayed inline.  

---

### 🔹 Conclusion  

This project demonstrates how **GMM-based synthetic sampling** can generate realistic minority class samples, leading to better detection of fraudulent transactions compared to training on imbalanced data alone.  

---

📌 *Prepared by **Md Aminul Islam Rony (ID25M804)** as part of Assignment 04 for DA5401.*  