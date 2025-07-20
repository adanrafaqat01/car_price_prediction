🚗 Car Price Prediction using Machine Learning

This project predicts the *resale price of used cars* using supervised regression models. It includes full data cleaning, visualization, feature engineering, model training, and evaluation steps — all done in a beginner-friendly and professional format.

---

## 📌 Objective

To build a machine learning model that can predict the selling price of a used car based on various features like fuel type, kilometers driven, transmission type, and car age.

---

## 📂 Dataset

The dataset file is included in this repository as:  
📄 car data.csv  

It contains key columns such as:
- Present_Price
- Kms_Driven
- Fuel_Type
- Seller_Type
- Transmission
- Owner
- Year (used to create car_age)
- Selling_Price (Target)

---

## ⚙ Workflow

### 1. Data Cleaning
- Removed unnecessary columns (Car_Name)
- Renamed inconsistent column names
- Created new column: car_age
- Removed duplicates and handled categorical data

### 2. Exploratory Data Analysis (EDA)
- Visualized distribution of selling prices
- Barplots for fuel type vs selling price
- Correlation heatmap

### 3. Model Building
- Features selected: car_age, kms_driven, fuel, seller_type, transmission, owner
- Models used:
  - Linear Regression
  - Random Forest Regressor

### 4. Model Evaluation
- Compared using R² score
- Plotted actual vs predicted prices
- Analyzed feature importance

---

## 📊 Results

| Model               | R² Score |
|--------------------|----------|
| Linear Regression  | 0.60     |
| Random Forest      | 0.83     ✅ Best

---

## ▶ How to Run This Project

1. Clone or download this repository.
2. Open the notebook Car_Price_Prediction.ipynb in Google Colab or Jupyter Notebook.
3. Ensure car data.csv is placed in the same directory.
4. Run each cell step by step.

---

## 🧰 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📈 Visualizations Included

- Histogram of selling price
- Fuel type vs selling price (Barplot)
- Heatmap of correlations
- Feature importance barplot

---

## ✅ Internship Project

This project was created as a part of a *Data Science Internship* offered by *DataZenix Solution*, focused on hands-on ML implementation with real-world datasets.
