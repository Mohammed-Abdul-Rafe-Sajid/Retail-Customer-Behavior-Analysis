# 🛍️ Retail Customer Analytics and Prediction System

### 🎓 Course-End Machine Learning Project  

---

## 📘 Project Overview
This project focuses on analyzing retail customer data to uncover valuable insights through **data preprocessing**, **predictive modeling**, and **customer segmentation**.  
By leveraging supervised and unsupervised learning techniques, the project helps businesses:
- Predict future customer purchases  
- Identify key spending patterns  
- Segment customers for targeted marketing  

---

## 🧩 Project Objectives
1. **Data Preprocessing & Visualization**  
   Clean and prepare the dataset for accurate analysis. Visualize customer demographics and sales trends.  

2. **Customer Purchase Prediction**  
   Build a supervised classification model to predict whether a customer will make a purchase next month.  

3. **Customer Segmentation**  
   Apply clustering algorithms to identify distinct customer groups based on purchase behavior.  

---

## 🗂️ Dataset
The dataset (`Retail_Cleaned.csv`) contains 2000 retail transactions with the following columns:

| Feature | Description |
|----------|--------------|
| TransactionID | Unique identifier for each transaction |
| CustomerID | Unique identifier for each customer |
| Gender | Customer gender |
| Age | Customer age |
| City | City of residence |
| ProductCategory | Purchased product category |
| Quantity | Quantity of items purchased |
| Price | Unit price of the item |
| PurchaseDate | Date of transaction |
| PaymentMode | Payment method used |
| TotalAmount | Total transaction value |
| Month | Month derived from date |
| DayOfWeek | Day of the week of purchase |
| AgeGroup | Grouped age categories |

---

## 🧹 Task 1: Data Preprocessing & Visualization

### ✅ Steps Performed
- Handled missing values and duplicates  
- Standardized categorical data  
- Created new features: `TotalAmount`, `Month`, `DayOfWeek`, `AgeGroup`  
- Encoded categorical variables  
- Normalized numerical columns  

### 📊 Visualizations
- Age distribution of customers  
- Gender ratio  
- Top 10 cities by customer count  
- Total sales by product category  
- Monthly sales trend  
- Payment mode usage (Pie chart)

---

## 🤖 Task 2: Customer Purchase Prediction

### 🎯 Objective
Predict whether a customer will purchase again in the next month (`Will_Purchase_Next_Month`).

### 🔧 Model Used
- **Algorithm:** Decision Tree Classifier  
- **Features:** `Age`, `Gender`, `City`, `ProductCategory`, `Quantity`, `Price`, `TotalAmount`  
- **Data Split:** 70% Train, 30% Test  

### 📈 Evaluation Metrics
- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-score)

### 🖼️ Visualizations
- Confusion Matrix Heatmap  
- Decision Tree Plot  
- Feature Importance Bar Chart  

---

## 🎯 Task 3: Customer Segmentation

### 🧠 Objective
Group customers into segments based on purchase patterns using **K-Means clustering**.

### ⚙️ Model Details
- Features used: `Age`, `TotalAmount`, `Quantity`, and `Purchase Frequency`  
- Number of Clusters: **K = 3**  
- Evaluation Metrics:  
  - **Inertia** (Within-cluster sum of squares)  
  - **Silhouette Score**

### 📊 Visualizations
- Cluster Scatter Plot (`Age` vs `TotalAmount`)  
- Cluster Distribution Bar Plot  

### 🧾 Cluster Interpretation Example
| Cluster | Characteristics | Description |
|----------|-----------------|--------------|
| 0 | Young, low spenders | Discount-seekers |
| 1 | Middle-aged, moderate spenders | Regular buyers |
| 2 | Older, high-value spenders | Premium/frequent buyers |

---

## 🛠️ Technologies Used
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment:** Google Colab / Jupyter Notebook  

---

## 📦 Deliverables
- Cleaned dataset: `Retail_Cleaned.csv`  
- Purchase prediction model  
- Customer clustering results  
- Visual analytics dashboard (plots & charts)  

---

## 🧾 Conclusion
This project demonstrates how **machine learning can transform raw retail data into actionable insights**.  
It supports business decisions such as:
- Identifying potential customers for next-month campaigns  
- Understanding demographic-based purchase trends  
- Targeting specific customer groups with personalized offers  

---

## ✨ Future Improvements
- Use advanced models like Random Forest or XGBoost for purchase prediction  
- Incorporate time-series forecasting for sales trends  
- Build an interactive dashboard using Streamlit or Power BI  

---
