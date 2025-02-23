### **📊 Commercial Store Analysis – README**  

#### **📌 Project Overview**  
This project was undertaken as part of the Brainware Solutions Internship to analyze the sales performance, customer purchasing behavior, and revenue trends of a commercial store. Using data-driven insights, we assess product category performance, customer demographics, seasonal trends, and the impact of discounts. The analysis helps optimize business strategies for better revenue generation and customer engagement.

---

## **📂 Table of Contents**  
1. [Dataset Overview](#dataset-overview)  
2. [Tools & Libraries Used](#tools--libraries-used)
3. [Data Preprocessing](#Data-Preprocessing)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
5. [Key Business Insights](#key-business-insights)  
6. [Conclusion & Recommendations](#conclusion--recommendations)  

---

## **📊 Dataset Overview**  
The dataset contains sales transactions from a commercial store, covering details such as:  
- **Customer Demographics:** Age, gender.
- **Sales Data:** Product categories, transaction amounts,Price per Unit
- **Time-based Trends:** sales performance according to dates.  

The data is used to perform **analysis and visualization** for better decision-making.  

---

## **🛠️ Tools & Libraries Used**  

| Tool / Library    | Purpose |
|-------------------|--------------------------------------------------|
| **Python**       | Core programming language for analysis |
| **Jupyter Notebook** | Interactive environment for data exploration |
| **Pandas**       | Data manipulation and analysis |
| **NumPy**        | Numerical computing for statistical operations |
| **Matplotlib**   | Data visualization (charts, plots) |
| **Seaborn**      | Advanced statistical data visualization |
| **Plotly**       | Interactive visualizations |


---

## **⚙️ Data Preprocessing**  
To ensure accuracy, several data cleaning and transformation steps were performed:  
✅ **Handled missing values** by imputing appropriate replacements.  
✅ **Converted date columns** to datetime format for time-based analysis.  
✅ **Standardized categorical values** for consistency.  
✅ **Created new columns** such as revenue per category and discount impact.  

---

## **📈 Exploratory Data Analysis (EDA)**  
Several statistical and visual methods were used to derive insights:  

### **1️⃣ Customer Demographics Analysis**  
- **Gender distribution:** Male vs. Female spending trends.  
- **Age group segmentation:** Identified the most frequent and high-spending age groups.  

### **2️⃣ Product Category Performance**  
- **Sales distribution:** Analyzed transaction volume per category.  
- **Revenue per category:** Identified high-revenue product lines.  

### **3️⃣ Time-Series Analysis**  
- **Daily & Weekly trends:** Identified peak shopping days.  
- **Monthly revenue patterns:** Seasonal fluctuations in sales.  

### **4️⃣ Customer Spending Behavior**  
- **Average transaction value:** Identified high-value vs. low-value customers.  
- **Loyalty segmentation:** Analyzed customer retention based on spending patterns.  


### **Insights**
### ** 1.Customer Demographics & Behavior**
Gender distribution is nearly balanced, with **51.1%** male and **48.9%** female customers contributing to transactions.
The business has 1,000 unique customers, indicating a lack of repeat purchases.
Age distribution analysis suggests that the **26-35 and 46-55** age groups contribute the most sales, making them the primary target audience.

### **2. Customer Purchase Patterns (FM Analysis)**
**No repeat transactions were observed**, highlighting the need for a retention strategy.

**High-Spenders:**

**CUST002 (50% of revenue) and CUST004 (25%) are the most valuable customers.**

**Low-Spenders:**

**CUST003 (1.5% of revenue)** has the lowest spending, with **CUST001 and CUST005** also contributing less.
Recency Insights:
**CUST001 (most recent, 38 days ago)** presents a potential for repeat engagement.
**CUST003 (least recent, 353 days ago)** is at high risk of churn.

### **3. Sales Performance & Trends**

**Product category analysis:**

**Electronics (34.4%) and Clothing (34.1%)** drive the most sales, followed by **Beauty (31.5%).**
Sales peak on weekends, with **Saturday being the highest sales day (78.81K)**, while **Thursday records the lowest (53.83K).**

### **4. Customer Lifetime Value (CLV) Distribution**
**Right-skewed distribution** indicates that most customers have low CLV, with a few high-value customers driving revenue.

**Outliers present, suggesting a small segment of exceptionally high-spending customers.**

---

### **Conclusion & Recommendations**

**1. Improve Customer Retention**
**Loyalty programs, discount offers, and personalized campaigns** should be introduced to encourage repeat purchases.
**Targeted email campaigns** can re-engage one-time buyers.

**2. Focus on High-Value Customers (CUST002, CUST004)**
**Exclusive offers and premium services** should be designed to retain these top contributors.
**Proactive engagement (personalized emails, discounts)** can ensure repeat purchases.

**3. Reactivate Inactive Customers (CUST003, CUST004)**
**Win-back campaigns**, such as special discounts and reminders, can help bring back customers with older purchase dates.

**4. Leverage Peak Sales Days**
**Weekend promotions (especially on Saturdays)** can be used to further increase sales.
**Marketing efforts should focus on boosting midweek sales, especially Thursdays, by offering discounts or special deals.**

**5. Product Strategy**
**Since Electronics and Clothing contribute the highest revenue, more focus should be placed on promoting these categories.**

### **for further queries feel free to contact me via :**

✉ - priyanshikhandelwal2107@gmail.com 

### thankyou

Bundle offers and discounts for low-selling categories like Beauty can help improve sales.
  

---

This project provides **valuable data-driven insights** that can be applied to **real-world retail business optimization**. 🚀
