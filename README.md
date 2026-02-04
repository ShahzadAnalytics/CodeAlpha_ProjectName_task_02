# Supermarket Sales Analysis

## Project Overview
This project analyzes supermarket sales data to uncover trends, patterns, and insights. The goal is to help store managers make data-driven decisions, optimize sales, and improve customer satisfaction.

---

## Dataset
- **Source:** Supermarket Sales Dataset (`SupermarketSales.csv`)  
- **Columns:**  
  - `Invoice ID` – Unique transaction ID  
  - `Branch` – Store branch  
  - `City` – City location  
  - `Customer Type` – Member or Normal  
  - `Gender` – Male or Female  
  - `Product line` – Type of product sold  
  - `Unit price`, `Quantity`, `Total` – Sales details  
  - `Payment` – Cash, Credit Card, Ewallet  
  - `Date`, `Time` – Transaction date and time  

---

## Task 2: Exploratory Data Analysis (EDA)
EDA was performed to understand the data and answer meaningful business questions.

### **Steps Taken:**
1. **Understand dataset structure:**  
   - Checked shape, column types, and missing values  
   - Identified numeric vs categorical variables  

2. **Ask meaningful questions:**  
   - Which product lines generate the most sales?  
   - Does customer gender affect total sales?  
   - Which branch or city performs best?  
   - Which payment methods are most popular?  

3. **Detect trends and patterns:**  
   - Calculated total sales per branch, product line, and gender  
   - Analyzed peak sales hours  
   - Checked correlation between quantity and total price  

4. **Validate assumptions:**  
   - Used descriptive statistics (mean, median, sum)  
   - Confirmed patterns with visualizations  

5. **Address data issues:**  
   - Checked for duplicates or missing values  
   - Cleaned inconsistent data entries  

---

## Task 3: Data Visualization
Visualization helps transform raw sales data into actionable insights.

### **Techniques Used:**  
- **Libraries:** Matplotlib, Seaborn, Pandas  
- **Charts and Graphs:**  
  - Bar charts for product line sales comparison  
  - Pie charts for payment method distribution  
  - Heatmaps for correlation analysis  
  - Line charts for sales trends over time  

### **Key Insights:**  
- Certain product lines like **Health & Beauty** and **Electronic accessories** generate higher revenue  
- Branch **B** had the highest overall sales  
- Male and Female customers show similar buying patterns, but preferences vary by product line  
- Credit Card and Ewallet are the most used payment methods  

### **Data Storytelling:**  
- Visualizations highlight high-performing branches and product lines  
- Supports managers in stock planning, promotions, and resource allocation  

---

## Tools & Libraries
- Python 3.x  
- pandas, numpy  
- matplotlib, seaborn  
- Jupyter Notebook or VS Code  

---

## How to Run
1. Install required libraries:  
   ```bash
   pip install pandas numpy matplotlib seaborn
