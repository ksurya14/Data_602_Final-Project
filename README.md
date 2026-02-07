## Vehicle Sales Data Analysis

This project focuses on **data preprocessing, cleaning, exploratory data analysis (EDA), and statistical analysis** of a large vehicle sales dataset containing over **550,000 vehicle records**. The objective is to transform raw transactional vehicle data into a clean analytical dataset and derive meaningful insights related to pricing, vehicle characteristics, and market trends. 

### Project Objectives

* Clean and preprocess raw vehicle sales data
* Handle missing values using imputation techniques
* Remove duplicates and detect outliers using IQR and Isolation Forest
* Perform exploratory data analysis to understand brand distribution and pricing patterns
* Conduct statistical hypothesis testing and correlation analysis
* Identify factors influencing vehicle selling price

### Dataset Features

The dataset contains vehicle-level information such as:

* Manufacturing year, brand, model, trim, and body type
* Transmission type and vehicle condition
* Odometer readings
* Market price and actual selling price
* State-level sales information 

### Methodology

1. **Data Cleaning & Preprocessing**

   * Standardized column names and categorical values
   * Handled missing values using mode/mean-based imputations
   * Removed duplicates using Vehicle Identification Number (VIN)
   * Reduced categorical dimensionality for rare car brands

2. **Outlier Detection**

   * Interquartile Range (IQR) method
   * Isolation Forest anomaly detection

3. **Exploratory Data Analysis**

   * Brand frequency and pricing distribution visualizations
   * State-wise vehicle sales distribution
   * Price variation across transmission types

4. **Statistical Analysis**

   * Pearson correlation analysis between Market Price and Selling Price (strong positive correlation observed)
   * Hypothesis testing comparing transmission types and price differences
   * Odometer-based price comparison

### Key Insights

* Market price strongly predicts selling price with very high correlation.
* Automatic transmission vehicles generally have higher market prices than manual vehicles.
* Lower odometer readings are associated with higher selling prices.
* Vehicle sales are concentrated in a few major states and dominated by a few leading brands.

### Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* SciPy

### Outcome

The project demonstrates a complete **end-to-end data analytics workflow**, including preprocessing, feature cleaning, statistical testing, and business-oriented insight generation that can support pricing strategies and automotive market analysis.

---

