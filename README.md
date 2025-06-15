# Supply-chain-data-analysis-python-

# 📦 Supply Chain Delivery Performance Analysis (Python)

## 📖 Project Overview

Hi, I’m Shashi Gaddam — a data analyst passionate about transforming raw operational data into clear, actionable business insights. In this project, I’ve conducted an exploratory and predictive analysis on a real-world *Supply Chain Delivery dataset*, focusing on delivery time patterns and late delivery risks across various operational parameters.

The goal was two-fold:

1. *Uncover key factors affecting delivery performance*.
2. *Build a predictive model to estimate late delivery risks based on order and shipping details*.

This README explains my approach, methodologies, and insights in a way that's accessible to both technical and business stakeholders.


## 📊 Tools & Technologies Used

* *Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)*
* *Logistic Regression (for predictive modeling)*
* *Data Visualization* for storytelling and stakeholder presentations
* *Exploratory Data Analysis (EDA)* to uncover operational bottlenecks


## 📝 Business Questions Addressed

✅ What is the overall distribution of delivery times?
✅ How do delivery times vary by *Shipping Mode*, *Region*, *Product Type*, and *Order Quantity*?
✅ Are there significant correlations between numeric variables affecting deliveries?
✅ Can we predict *Late Delivery Risk* based on known order and shipping details?


## 🔍 Methodology

### 📌 Data Cleaning

* Handled missing values in customer last names by imputing ‘Unknown’.
* Dropped non-essential columns like *Order Zipcode* and *Product Description* to simplify analysis.

### 📌 Feature Engineering

* Created a new feature: *delivery\_time* (days between order date and shipping date).
* Converted categorical variables using *one-hot encoding* for machine learning modeling.

### 📌 Exploratory Data Analysis

* *Histograms* for delivery time distribution.
* *Box plots* and *scatter plots* to visualize delivery patterns across shipping modes and order quantities.
* *Heatmap of correlations* between numeric operational variables.

### 📌 Predictive Modeling

* Built a *Logistic Regression model* to classify deliveries as ‘late’ or ‘on-time’ using:

  * *Shipping Mode*
  * *Order Region*
  * *Product Name*
  * *Order Item Quantity*

* Evaluated model accuracy and recall via a *classification report*.


## 📈 Key Findings

* *Delivery times varied significantly by shipping mode* — certain modes consistently delivered faster than others.
* *Regions* and *product categories* influenced delivery performance.
* A moderate correlation was observed between *order quantity and delivery time*.
* The *Logistic Regression model* demonstrated good potential in predicting *late delivery risk*, providing a foundation for proactive supply chain management.

## 📣 Why This Project Matters

Supply chain delays directly impact customer satisfaction, operating costs, and vendor performance metrics. Through this analysis, I showcased how:

* *Data-driven insights* can uncover operational inefficiencies.
* Predictive models can empower businesses to *proactively mitigate delivery risks*.
* Clear, *visual storytelling* bridges the gap between raw data and executive decision-making.
