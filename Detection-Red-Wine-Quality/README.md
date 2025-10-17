# 🍷 Red Wine Quality Detection using Machine Learning

## 📘 Overview  
This project focuses on **predicting the quality of red wine** based on its **physicochemical features** such as acidity, sugar content, pH, alcohol percentage, and others.  
Using **Machine Learning algorithms**, the goal is to classify wine samples into different quality levels (e.g., low, medium, high).

---

## 🧠 Objective  
Build a **classification model** that can predict the **quality score** of red wine based on various chemical attributes.

---
## 🧩 Dataset  
📊 **Dataset Name:** Wine Quality – Red Wine  
📥 **Source:** [Kaggle - Red Wine Quality Dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al)

- Total Samples: 1,599  
- Features: 11 independent variables  
- **Target Column:** `quality` (ranging from 0 to 10)  

**Main Features include:**
- Fixed acidity  
- Volatile acidity  
- Citric acid  
- Residual sugar  
- Chlorides  
- Free sulfur dioxide  
- Total sulfur dioxide  
- Density  
- pH  
- Sulphates  
- Alcohol  

---

## ⚙️ Workflow  
1. **Import Libraries** → `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`  
2. **Load & Explore Data** → Understand data structure and check for missing values  
3. **Data Preprocessing** →  
   - Normalize or scale features  
   - Handle imbalanced target values  
4. **Train-Test Split** → Divide data into training and testing sets  
5. **Model Building** → Train multiple algorithms such as:  
   - `Logistic Regression`  
   - `Random Forest Classifier`  
   - `Decision Tree Classifier`  
   - `Support Vector Classifier (SVC)`  
   - `K-Nearest Neighbors (KNN)`  
6. **Model Evaluation** → Compare performance using metrics:  
   - Accuracy  
   - Precision / Recall / F1-score  
---

## 📈 Results  
- The **Random Forest Classifier** gave the best performance with an accuracy around **~93%**.  
- The model successfully identified patterns between chemical composition and wine quality.  
- Further tuning could improve precision for medium-quality wines.

---

## 📊 Visuals  
- **Correlation Heatmap** → to show relationships between features.  
- **Feature Importance Graph** → to highlight which factors most influence wine quality.  

---

## 🧰 Technologies Used  
Language : Python    
Libraries : pandas, numpy, matplotlib, seaborn, scikit-learn     
nvironment : Jupyter Notebook / VS Code / Kaggle 

---

## 👨‍💻 Author
**Farid Ghattas** - Aspiring Data Analyst    
📧 **farid.ghattas84@gmail.com**    
💼 **https://www.linkedin.com/in/farid-ghattas-43356923b/**

