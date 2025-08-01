# 🎓 Final Project: Comprehensive Machine Learning Pipeline

## 📌 Project Overview

This project is the **final assignment for the Machine Learning course**, designed to demonstrate practical understanding and application of both **supervised and unsupervised learning techniques**. It involves a complete ML pipeline starting from classification, performance evaluation, and cross-validation to unsupervised clustering and post-cluster classification analysis.

---

## 🧠 Project Workflow

<img width="736" height="348" alt="image" src="https://github.com/user-attachments/assets/3d8c015f-8362-4bfe-97ca-d44ec0d9c0ee" />


1. **🔍 Supervised Classification**
   - Applied **6 different classification algorithms (Decision tree, K-nearest, SVM(Linear), SVM(Non-Linear, Naive Bias, Neural Network)** to the dataset.
   - Evaluated each model using key performance metrics:
     - **Accuracy**
     - **Precision**
     - **Recall**
     - **F1-Score**

2. **🔁 Cross-Validation**
   - Implemented **10-Fold Cross-Validation** for each classification algorithm.
   - Recorded and analyzed the performance metrics for **each fold**.

3. **🧩 Unsupervised Learning**
   - Converted the dataset into an **unsupervised format** by removing labels.
   - Applied **clustering algorithms** (e.g., K-Means, k-medoids, DBSCAN, and Hierarchical Clustering) to form clusters.
   - Stored the **clustered version of the dataset** for further analysis.

4. **🔁 Post-Clustering Classification**
   - Re-applied the same set of **classification algorithms** on the **clustered dataset**.
   - Collected performance metrics again for comparison.

5. **📊 Comparative Analysis**
   - Compared classification results **before and after clustering**.
   - Evaluated how clustering affected the performance of classifiers.

---

## 🎯 Key Objectives
- Understand and compare multiple **classification techniques**.
- Explore the effect of **cross-validation** on model performance.
- Analyze the influence of **unsupervised clustering** on classification.
- Develop insights into model **robustness and generalizability**.

---

## 🛠 Tools & Technologies
- **Language**: Python  
- **Environment**: Google Colab / Anaconda  
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  

---
PART-1 contains dataset preprocessing, only classifications on preprocessed data (with and without cross-validation), and clustering(saving the clustered dataset).
PART-2 contains classification without cross-validation and with cross-validation on the k-means clustered dataset.
PART-3 contains classification without cross-validation and with cross-validation on the k-medoids clustered dataset.
PART-4 contains classification without cross-validation and with cross-validation on the DBSCAN clustered dataset.
PART-5 contains classification without cross-validation and with cross-validation on the Hierarchy clustered dataset.
Let me know if you'd like to include visuals, plots, or performance summary tables as part of the final report or README.
