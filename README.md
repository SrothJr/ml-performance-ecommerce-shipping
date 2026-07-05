# Comparative Performance Analysis of Machine Learning Models on E-Commerce Shipping Data

## 📌 Project Overview
This project performs a comparative analysis of various Machine Learning models to predict shipment delays based on E-Commerce shipping data. By predicting whether a package will reach its destination on time, e-commerce companies can optimize supply chain operations and improve customer satisfaction. 

This project was developed for the **CSE422** course at **Brac University**.

## 👤 Author
* **Md. Nazim Hossain** ## 📊 Dataset Description
The model is trained on the **E-Commerce Shipping Dataset**. It contains 10,999 records and 12 columns of customer and shipping information, including:
* `Warehouse_block`, `Mode_of_Shipment`, `Customer_care_calls`, `Customer_rating`, `Cost_of_the_Product`, `Prior_purchases`, `Product_importance`, `Gender`, `Discount_offered`, `Weight_in_gms`.
* **Target Variable:** `Reached.on.Time_Y.N` (1 = Reached on time / 0 = Delayed).

## 🛠️ Preprocessing & Exploratory Data Analysis (EDA)
To prepare the data for training, several rigorous preprocessing steps were implemented to ensure the models performed optimally:
* Handling Null / Missing Values
* Outlier Detection and Removal
* Dataset Splitting
* Categorical Encoding and Feature Scaling
* Handling Class Imbalance

## 🤖 Models Used
Both Supervised and Unsupervised learning techniques were applied and hypertuned for this analysis:

### Supervised Learning
1. **Logistic Regression**
2. **Decision Tree**
3. **Neural Network**
4. **K-Nearest Neighbors (KNN)**

### Unsupervised Learning
1. **K-Means Clustering**

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone [https://github.com/SrothJr/ml-performance-ecommerce-shipping.git](https://github.com/SrothJr/ml-performance-ecommerce-shipping.git)
   cd ml-performance-ecommerce-shipping
   pip install pandas numpy matplotlib seaborn scikit-learn
   jupyter notebook ML_models_performance_analysis.ipynb```

## 📄 Documentation
For detailed insights into the methodology, model tuning, preprocessing struggles, and accuracy comparisons, please refer to the attached Report.pdf.
