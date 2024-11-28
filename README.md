
# **BigMart Sales Analysis and Prediction**

## **Overview**  
This project aims to improve demand forecasting and supply chain optimization for BigMart stores. By leveraging **machine learning models** such as Random Forest and Gradient Boosting, the solution provides accurate sales predictions. Additionally, an **interactive Power BI dashboard** delivers actionable insights for decision-making.

---

## **Project Development Phases**  

### 1. **Problem Understanding and Objective Definition**  
   - **Objective**: Forecast sales to help optimize inventory management and resource allocation.  
   - **Problem Scope**: Analyze historical sales data to identify trends, assess promotional impacts, and predict future sales.  

---

### 2. **Data Collection and Exploration**  
   - **Data Sources**: The project uses historical sales data, including product details, store attributes, and promotional information.  
   - **Exploratory Data Analysis (EDA)**: Key focus areas included:  
     - **Sales trends over time**  
     - **Product category performance**  
     - **Impact of promotions and discounts**  
     - **Identifying outliers and handling missing data**

   **Key Tools**:  
   - Jupyter notebooks for analysis  
   - Visualization using Matplotlib and Seaborn

---

### 3. **Data Preprocessing**  
   - **Steps Involved**:  
     - Handling missing values  
     - Encoding categorical variables (one-hot encoding)  
     - Feature scaling and transformation  
     - Data splitting (training and test sets)
---

### 4. **Feature Engineering**  
   - **Created new features** to enhance predictive performance:  
     - Seasonality indicators (e.g., holiday sales)  
     - Promotion effectiveness scores  
     - Product popularity indexes

---

### 5. **Model Building**  
   - **Models Used**:  
     - Random Forest  
     - Gradient Boosting (XGBoost)  

   - **Training Process**:  
     Hyperparameter tuning was performed using techniques like GridSearchCV to optimize model performance.  
   
---

### 6. **Model Evaluation**  
   - **Metrics Used**:  
     - Mean Absolute Error (MAE)  
     - Root Mean Squared Error (RMSE)  
     - R² Score  

   The models showed high accuracy and stability across various datasets, ensuring reliable predictions for real-world use cases.

---

### 7. **Sales Prediction**  
   Once trained, the models were used to predict future sales based on new input data.  

### 8. **Visualization and Dashboard Creation**  
   - A aimple**Power BI dashboard** was developed to visualize key insights, including:  
     - Sales trends over time   
     - Geographic sales distribution  

   **Steps**:  
   1. Open the `BigMart-Sales-Dashboard.pbix` file in Power BI Desktop.  
   2. Refresh data connections.  
   3. Explore different dashboard tabs for insights.

---

### 9. **Insights and Recommendations**  
   - **Top Insights**:  
     - Seasonal spikes in sales around holidays.  
     - Categories with the highest profit margins.  
     - Promotional campaigns driving significant sales uplift.  
   - **Recommendations**:  
     - Stock high-demand products during peak seasons.  
     - Optimize promotional strategies based on past performance.  
     - Focus on high-margin categories for profitability.

---

## **Technologies and Tools Used**  
- **Programming Languages**: Python  
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn  
- **Visualization**: Power BI  
- **Version Control**: Git  

---

## **How to Run the Project**  

### Prerequisites:  
- Python 3.8+  
- Power BI Desktop  

### Steps:  
1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/username/BigMart-Sales-Analysis.git
   cd BigMart-Sales-Analysis
   ```

2. **Set Up Virtual Environment** (Optional but recommended):  
   ```bash
   python -m venv env
   source env/bin/activate    # macOS/Linux
   env\Scripts\activate       # Windows
   ```

3. **Install Dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Data Preprocessing**:
5. 5. **Train the Model**:  
6. **Make Predictions**:  
   ```bash
   python scripts/predict.py --input data/new_data.csv --output predictions.csv
   ```

7. **Power BI Dashboard Sample**:
   ![BI](https://github.com/nirajsoft01/Big_Mart_sales_prediction_project/assets/70097083/4dcdca23-6f73-4663-aa46-7de37fb758cb)
 

---

## **Future Enhancements**  
- Implement deep learning models for improved forecasting accuracy.  
- Automate real-time data updates for dynamic dashboard insights.  
- Add predictive analytics and KPI tracking to the Power BI dashboard.

---


