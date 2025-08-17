# 🧠 Decision Tree Classifier – Customer Purchase Prediction  

This project builds a **Decision Tree Classifier** to predict whether a customer will purchase a product/service based on **demographic and behavioral data**.  
The dataset used is the **Bank Marketing dataset** from the UCI Machine Learning Repository.  

---

## 📂 Dataset
We used the dataset from [Prodigy InfoTech Data Science Datasets](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%203).  
The dataset includes customer details such as age, job, marital status, education, balance, contact type, and past campaign responses.  

---

## ⚙️ Steps Followed
1. **Data Loading** – Imported the dataset (`bank.csv`).  
2. **Data Preprocessing** – Dropped irrelevant columns (like `duration`), handled categorical data with one-hot encoding.  
3. **Train-Test Split** – 80% training, 20% testing.  
4. **Model Training** – Applied `DecisionTreeClassifier`.  
5. **Evaluation** – Checked accuracy score on the test data.  
6. **Visualization** – Created a **correlation heatmap** using Seaborn.  

---

## 📊 Results
- The Decision Tree classifier achieved a **good accuracy** in predicting whether a customer will subscribe to a product.  
- Helps businesses in **targeted marketing strategies**.  

---

## 🚀 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 🔮 Future Scope
- Hyperparameter tuning (max_depth, min_samples_split, etc.)  
- Feature importance analysis  
- Trying Random Forest & Gradient Boosting for comparison  

---

💡 This project is part of my **Data Science Internship at Prodigy InfoTech**.
