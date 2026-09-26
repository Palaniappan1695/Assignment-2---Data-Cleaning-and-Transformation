# 📊 Excel Data Cleaning & Exploration

## 📌 Project Overview

This project focuses on **data cleaning, preparation, transformation, and formatting using Microsoft Excel**.

The objective was to take a raw **Product Dataset** containing potential missing values, inconsistent text, duplicate records, and poorly structured fields, and prepare it for further data analysis.

This project demonstrates fundamental **Data Analyst skills in Excel**, particularly data quality management and preprocessing.

---

## 🎯 Project Objective

The main objective of this project was to transform a raw dataset into a **clean, standardized, and analysis-ready dataset**.

The project covers:

* Handling missing values
* Standardizing inconsistent text
* Correcting category errors and typos
* Identifying and removing duplicate records
* Splitting and merging columns
* Applying number and date formatting
* Using conditional formatting to highlight patterns

---

## 📂 Dataset

The project uses a **Product Dataset** containing the following attributes:

| Column       | Description                                       |
| ------------ | ------------------------------------------------- |
| Product ID   | Identifier containing product-related information |
| Product Name | Name of the product                               |
| Brand Name   | Brand associated with the product                 |
| Quantity     | Available quantity                                |
| Category     | Product category                                  |
| Price        | Product price                                     |

---

## 🧹 Data Cleaning & Preparation

### 1. Missing Value Handling

The dataset was checked for missing values, particularly in:

* `Price`
* `Category`

Appropriate strategies were considered for handling missing values before further analysis.

The objective was to ensure that missing information did not negatively affect the quality of the dataset.

---

### 2. Data Standardization

The `Product Name` column was examined for inconsistent text formats.

The `Category` column was also checked for:

* Typos
* Misspellings
* Inconsistent category names

Excel's **Find & Replace** functionality was used to standardize the text and correct inconsistencies.

---

### 3. Duplicate Removal

The dataset was checked for duplicate records based on the **entire row**.

Duplicate records were identified and removed to improve data quality and prevent duplicate information from affecting future analysis.

---

### 4. Data Transformation

The `Product ID` column was transformed by splitting it into:

* `Manufacturing Date`
* `Country Code`

Unnecessary characters were removed where required.

The `Brand Name` and `Product Name` columns were also merged into a new column:

**`Product Brand`**

This demonstrates the use of Excel for basic data transformation and restructuring.

---

### 5. Number & Date Formatting

The dataset was formatted to improve readability and consistency.

#### Price

The `Price` column was converted into a **currency format**.

#### Manufacturing Date

The `Manufacturing Date` column was formatted using:

**DD-MM-YYYY**

---

### 6. Conditional Formatting

Conditional formatting was applied to improve visual analysis.

#### Price

Data bars or color scales were applied to the `Price` column to visually identify differences in product prices.

#### Category

A custom conditional formatting rule was created to highlight products belonging to the:

**Electronics**

category.

---

## 🛠️ Tools & Techniques Used

### Tools

* Microsoft Excel
* GitHub

### Excel Features

* Find & Replace
* Remove Duplicates
* Text/Data Transformation
* Column Splitting
* Column Merging
* Currency Formatting
* Date Formatting
* Conditional Formatting
* Data Cleaning
* Data Standardization

---

## 📈 Data Analyst Skills Demonstrated

This project demonstrates the following beginner-level Data Analytics skills:

| Skill                   | Application                                 |
| ----------------------- | ------------------------------------------- |
| Data Cleaning           | Handling missing values and inconsistencies |
| Data Quality Management | Identifying and removing duplicates         |
| Data Standardization    | Correcting text formats and category names  |
| Data Transformation     | Splitting and merging columns               |
| Data Formatting         | Applying number and date formats            |
| Data Visualization      | Using conditional formatting                |
| Excel Proficiency       | Using Excel tools for data preparation      |

The assignment specifically evaluates these areas as core Data Analyst skills.
