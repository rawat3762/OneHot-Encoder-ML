# OneHot-Encoder-ML

## 📌 Description
A hands-on Python project demonstrating One-Hot Encoding to preprocess categorical data and prepare clean datasets for machine learning models.

---

## 📌 What is One-Hot Encoding?
One-Hot Encoding is a technique where categorical variables are converted into numeric format by creating binary columns for each category, making the dataset suitable for ML models.

---

## ⚙️ Workflow
- Import required libraries (pandas, scikit-learn) 
- Load the dataset  
- Identify missing values (NaN)
- Fill missing values in Gender and Married with mode 
- Apply OneHotEncoder from Scikit-learn with drop='first' to avoid dummy variable trap
- Transform categorical columns into numeric format
- Combine encoded columns with original dataset

---

## 🚀 Features
- Efficient handling of missing categorical data
- Converts Gender and Married columns into numeric features
- Avoids dummy variable trap 
- Prepares datasets for machine learning models
- Beginner-friendly and easy-to-understand workflow  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- Scikit-learn (`OneHotEncoder`)  
- Jupyter Notebook  

---

## 📂 Project File
- `One Hot Encoder-04.ipynb`
