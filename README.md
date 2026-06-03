# 📊 DecodeLabs Data Cleaning Project – E-commerce Dataset

## 📌 Project Overview

This project was completed as part of the DecodeLabs Data Analytics Internship Program.  
It focuses on cleaning and preparing a raw e-commerce dataset using Microsoft Excel and Power Query.  

The goal was to improve data quality by handling missing values, correcting data types, removing inconsistencies, and preparing the dataset for analysis and visualization.

---

## 🎯 Project Objectives

- Identify and handle missing values  
- Clean and standardize raw transactional data  
- Remove duplicate records where necessary  
- Correct and format data types  
- Ensure consistency across all fields  
- Prepare dataset for further analysis  

---

## 📁 Dataset Information

- **Rows:** 1,200  
- **Columns:** 14  
- **Dataset Type:** E-commerce transaction data  

### Key Columns
OrderID, Date, CustomerID, Product, Quantity, UnitPrice, PaymentMethod, CouponCode, TotalPrice

---

## 🧹 Data Cleaning Process

The dataset was cleaned using Microsoft Excel and Power Query through the following steps:

1. Imported raw dataset into Power Query for cleaning and inspection  
2. Identified missing values in the CouponCode column (309 records)  
3. Replaced all missing CouponCode values with "No Coupon"  
4. Checked for duplicate records using OrderID  
5. Standardized data types (Date, numeric, and text fields)  
6. Ensured consistency across categorical fields such as Product and PaymentMethod  
7. Loaded the cleaned dataset back into Excel for final validation  

---

## ⚠️ Missing Values Handling

- Column affected: CouponCode  
- Missing values found: 309  
- Treatment applied: Replaced null values with "No Coupon" using Power Query  

---

## 📊 Data Visualization

### Raw Dataset (Before Cleaning)
https://github.com/Annozo-data/Decodelabs-data-cleaning-project/blob/Images/Dirty%20data_PJ1.JPG

### Cleaned Dataset (After Cleaning)
https://github.com/Annozo-data/Decodelabs-data-cleaning-project/blob/Images/Cleaned%20Data_PJ1.JPG

---

## 🛠 Tools Used

- Microsoft Excel  
- Power Query  
- Data Cleaning Techniques  

---

## 💡 Skills Demonstrated

- Data Cleaning and Transformation  
- Power Query (ETL process)  
- Handling Missing Values  
- Data Type Standardization  
- Data Quality Assessment  
- E-commerce Data Preparation  

---

## 📌 Key Outcome

This project demonstrates the ability to transform raw and messy datasets into clean, structured, and analysis-ready data using Excel-based tools, supporting better decision-making and visualization.
