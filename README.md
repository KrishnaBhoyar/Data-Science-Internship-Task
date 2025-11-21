# 🍽️ Data Science Internship Task — Restaurant Rating Analysis

This project is part of a Data Science Internship assignment.  
The goal is to perform **EDA (Exploratory Data Analysis)**, **Feature Engineering**, and build a **Machine Learning model** to predict restaurant ratings using the provided dataset.

---

## 📌 **Project Goals**
- Understand the dataset structure  
- Perform data cleaning & preprocessing  
- Explore key patterns in restaurant ratings  
- Create useful derived features  
- Build a predictive model  
- Evaluate model performance  
- Present insights through visualizations  

---

## 📊 **Steps Performed**

### **1. Data Loading**
- Loaded the dataset (`Dataset .csv`)
- Inspected shape, columns, missing values, and data types

### **2. Exploratory Data Analysis (EDA)**
- Summary statistics  
- Missing value analysis  
- Top cuisines, top cities  
- Rating distribution visualization  
- Price range vs rating analysis  

### **3. Feature Engineering**
Created new features:
- `name_len` → length of restaurant name  
- `num_cuisines` → number of cuisines  
- Binary conversion for:
  - Table booking availability  
  - Online delivery availability  

### **4. Model Building**
Machine Learning model used:
- **RandomForestRegressor**

Features used:
- `name_len`
- `num_cuisines`
- `Price range`
- `Votes`
- `Has Table booking_bin`
- `Has Online delivery_bin`

Target:
- `Aggregate rating`

### **5. Model Evaluation**
Metrics obtained:
- **MAE:** _approximately_ 1.18 (may vary based on preprocessing)  
- **RMSE:** calculated using √MSE  
- **R² Score:** measured to evaluate variance explained  

---

## 📈 **Visualizations Included**
- Rating distribution histogram  
- Bar chart of top cuisines  
- Boxplot of price range vs rating  

---

## 🚀 **How to Run the Notebook**
1. Open the notebook in Google Colab:  
   - Click: **Open in Colab** (GitHub automatically adds the button)  
2. Upload the dataset (Dataset .csv)  
3. Run all cells in order  
4. Review:
   - EDA outputs  
   - Visualizations  
   - Model performance metrics  

---

## 📁 **Project Files**
- `Data-Science-Internship-Task.ipynb` → Full analysis notebook  
- `Dataset .csv` → Dataset used  
- `README.md` → Project documentation (this file)

---

## ✔️ **Status**
🎉 Completed and ready for internship submission.

---

## 🙌 **Author**
Krishna Bhoyar  
Data Science Intern Enthusiast  
