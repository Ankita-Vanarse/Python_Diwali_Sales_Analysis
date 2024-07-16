# Python_Diwali_Sales_Analysis

## Project Overview

This project involves analyzing Diwali sales data to gain insights and improve customer experience and sales. The analysis covers various aspects such as gender, age, state, marital status, occupation, and product category, to understand the purchasing behavior and preferences of customers.

## Dataset

The dataset used for this project is `Diwali Sales Data.csv`, which contains the following columns:

- User_ID
- Cust_name
- Product_ID
- Gender
- Age Group
- Age
- Marital_Status
- State
- Zone
- Occupation
- Product_Category
- Orders
- Amount
- Status (dropped)
- unnamed1 (dropped)

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn

## Project Structure

The project is structured as follows:

1. **Data Loading and Preprocessing**
   - Load the dataset
   - Drop unrelated/blank columns
   - Handle missing values
   - Change data types and rename columns

2. **Exploratory Data Analysis (EDA)**
   - Analyze data distribution based on gender
   - Analyze data distribution based on age group
   - Analyze data distribution based on state
   - Analyze data distribution based on marital status
   - Analyze data distribution based on occupation
   - Analyze data distribution based on product category

3. **Conclusion**
   - Summarize key findings from the analysis

## Steps to Run the Project

1. **Clone the Repository**
   ```bash
   git clone <repository_url>
   ```
2. **Navigate to the Project Directory**
   ```bash
   cd diwali-sales-analysis
   ```
3. **Install Required Libraries**
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```
4. **Run the Analysis**
   Open and run the Jupyter Notebook or Python script containing the analysis.

## Key Findings

1. **Gender Analysis**
   - Most buyers are females, and their purchasing power is greater than males.

2. **Age Group Analysis**
   - Most buyers are aged between 26-35 years, and females in this age group have higher purchasing power.

3. **State Analysis**
   - Most orders and total sales are from Uttar Pradesh, Maharashtra, and Karnataka.

4. **Marital Status Analysis**
   - Most buyers are married women, and they have high purchasing power.

5. **Occupation Analysis**
   - Most buyers work in IT, Healthcare, and Aviation sectors.

6. **Product Category Analysis**
   - Most sold products are from Food, Clothing, and Electronics categories.

## Conclusion

Married women aged 26-35 years from Uttar Pradesh, Maharashtra, and Karnataka working in IT, Healthcare, and Aviation are more likely to buy products from Food, Clothing, and Electronics categories.


