# **Customer Insights & Sales Prediction 📊**  
🚀 **Predict future sales trends and analyze customer insights using data analytics and machine learning**  

![Sales Forecast](https://img.shields.io/badge/Sales-Forecasting-blue) ![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Regression-red) ![Python](https://img.shields.io/badge/Python-3.8+-yellow)

---

## 📌 **Project Overview**
This project analyzes **customer transaction data** to uncover **sales trends and build predictive models** for forecasting future sales. The dataset used is the **Superstore Sales Dataset (Kaggle)**.  

### **Key Objectives:**
- 🛒 **Understand Customer Behavior:** Analyze purchasing patterns and high-performing products.
- 📈 **Identify Sales Trends:** Use time series analysis to track revenue changes over time.
- 🔮 **Predict Future Sales:** Train **ARIMA-based machine learning models** to forecast upcoming sales.
- 📊 **Visualize Data:** Create **interactive dashboards (Tableau/Power BI)** for insights.

---

## ⚙️ **Tech Stack**
- **Programming Languages:** Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Data Processing:** SQL, Pandas, Data Preprocessing
- **Machine Learning:** Auto ARIMA, Time Series Forecasting (Statsmodels)
- **Data Visualization:** Matplotlib, Tableau/Power BI
- **Version Control:** Git, GitHub


## 🔧 **Setup Instructions**
### **1️⃣ Clone Repository**
```bash
git clone https://github.com/yourusername/Customer-Insights-Sales-Prediction.git
cd Customer-Insights-Sales-Prediction
```

### **2️⃣ Create a Virtual Environment**
```bash
python3 -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate  # Windows
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4️⃣ Run Jupyter Notebook**
```bash
jupyter lab
```

---

## 📊 **Exploratory Data Analysis (EDA)**
- **Top 10 states with highest sales**
- **Customer segments contributing most revenue**
- **Category-wise sales distribution**
- **Time series trend of total sales**  

📌 **Key Findings:** *To be updated after analysis*

---

## 🤖 **Sales Forecasting Model**
- **Model Used:** ARIMA (Auto ARIMA for best parameter selection)
- **Performance Evaluation:** RMSE Score (To be updated)
- **Forecasting Horizon:** Next 30 days

---

## 📌 **Results & Insights**
- 📈 *Predicted sales growth for the next month*.
- 🛒 *Identified best-selling product categories*.
- 📊 *Dashboard created for interactive analysis*.

---

### **✅ 1. Implemented Prophet Model for Forecasting**  
- Added **Prophet model** as an alternative to ARIMA.
- **Why?** Prophet handles seasonality better and is more robust.

🔹 **Changes to `README.md`:**
```md
- **Machine Learning:** Auto ARIMA, Prophet, Time Series Forecasting (Statsmodels)
```
```md
## 🤖 **Sales Forecasting Models**
We implemented **two time series forecasting models**:
1. **ARIMA (Auto ARIMA)**
   - **Performance Metrics:** RMSE, MAE, and MSE evaluated.
   - **Best Parameters:** Auto-selected using **pmdarima**.
   - **Forecasting Horizon:** Next 30 days.

2. **Facebook Prophet**
   - **Advantages over ARIMA:** Better handling of seasonality.
   - **Performance Evaluation:** Compared against ARIMA.
   - **Visualization:** Trend and confidence intervals plotted.
```

---

### **✅ 2. Evaluated Model Performance (MAE, RMSE, MSE)**  
- Evaluated **both ARIMA and Prophet** using **MAE, RMSE, MSE**.
- **Why?** Helps compare which model gives better predictions.

🔹 **Changes to `README.md`:**
```md
## 📌 **Results & Insights**
- 📈 *Predicted sales growth for the next month using Prophet & ARIMA.*
- 🛒 *Identified best-selling product categories and customer segments.*
- 📊 *Created a Tableau/Power BI dashboard to visualize forecasts.*
```
```md
## 🤖 **Sales Forecasting Models**
- **Model Evaluation Metrics:** RMSE, MAE, and MSE used to measure accuracy.
- **ARIMA vs Prophet:** Compared models to select the best for forecasting.
```

---

### **✅ 3. Exported Forecast Results to CSV for Tableau/Power BI**  
- Saved **Predicted Sales** into a **CSV file** (`sales_forecast_results.csv`).
- **Why?** Allows visualization in **Tableau & Power BI**.

🔹 **Changes to `README.md`:**
```md
## 📊 **Interactive Dashboard**
The final forecast results have been exported to a **CSV file for visualization in Tableau & Power BI**.

### **Steps to Use in Tableau/Power BI:**
1️⃣ **Download `sales_forecast_results.csv`** from the repo.  
2️⃣ **Load into Tableau or Power BI** as a data source.  
3️⃣ **Create line charts with "Date" vs "Predicted Sales"**.  
4️⃣ **Share interactive reports online**.
```

---

### **✅ 4. Updated Project Structure**
- Added new Jupyter notebooks & results folder.
You're right! The **Project Structure** in the `README.md` must match the actual files in your GitHub repository. Let's **fix the structure** to correctly reflect what’s present in your repo.

---

### **📌 Updated Project Structure in `README.md`**
Here’s the **corrected project structure** based on the files currently in your GitHub repo:

```md
## 📂 **Project Structure**
```

```
📁 SalesPrediction/
│── 📄 README.md             # Project Documentation
│── 📄 .gitignore            # Ignoring unnecessary files
│── 📄 Superstore.csv        # Raw dataset (Kaggle)
│── 📄 cleaned_superstore.csv  # Preprocessed dataset (Cleaned version)
│── 📄 sales_forecast_results.csv  # Final forecast results for visualization
│── 📄 storeanalysis.ipynb   # Jupyter Notebook (Data Cleaning, EDA, Forecasting)
```

---

### **✅ Summary of Changes**
1️⃣ **Added Prophet Model** 📈  
2️⃣ **Evaluated ARIMA vs Prophet (RMSE, MAE, MSE)** 📊  
3️⃣ **Saved forecast results to CSV** 📁  
4️⃣ **Updated README.md structure (New Notebooks & Results Folder)** 📝  

## 🤝 **Contributing**
Want to contribute? **Fork the repo**, create a branch, and submit a pull request.

---

## 🏆 **Credits**
- **Dataset:** [Superstore Sales Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Author:** [Jayaram Kumarapu](https://linkedin.com/in/jayaramkumarapu-i4m3f2)

---

## ⭐ **Support & Connect**
If you like this project, please ⭐ the repo and follow for more updates! 🚀  
