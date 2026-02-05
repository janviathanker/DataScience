# Tumor Detection using Machine Learning

## 📌 Project Overview
This project focuses on classifying tumors as **Malignant (M)** or **Benign (B)** using machine learning techniques.  
The objective is to analyze tumor characteristics, perform exploratory data analysis (EDA), preprocess the data, and build a classification model to accurately detect tumor type.

The project is implemented using **Python** in **Jupyter Notebook** and uses a **Random Forest Classifier** for prediction.

---

## 📂 Dataset Information
- Dataset Name: `Tumor_Detection.csv`
- Total Records: 569
- Total Features: 30 numerical tumor-related features
- Target Variable: `diagnosis`
  - `M` → Malignant
  - `B` → Benign

The dataset contains measurements such as radius, texture, perimeter, area, concavity, smoothness, and other tumor-related attributes.

---

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Project Workflow
1. **Data Loading**
   - Loaded dataset from CSV file using Pandas.

2. **Data Cleaning**
   - Removed irrelevant columns such as `id`.
   - Checked for missing values.

3. **Exploratory Data Analysis (EDA)**
   - Visualized tumor class distribution.
   - Analyzed feature correlations using a heatmap.

4. **Data Preprocessing**
   - Encoded target labels.
   - Applied feature scaling using StandardScaler.
   - Split data into training and testing sets.

5. **Model Building**
   - Implemented a Random Forest Classifier.
   - Trained the model on the training data.

6. **Model Evaluation**
   - Evaluated performance using accuracy score.
   - Generated confusion matrix and classification report.
   - Analyzed feature importance.

---

## 📊 Results
- Achieved **high classification accuracy (~97–99%)**
- The model effectively distinguishes between malignant and benign tumors
- Features related to tumor size and shape were the most influential

---

## 📁 Repository Structure
