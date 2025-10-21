# 📘 Day 05

## ✅ Topic Covered
Data Frames and Factors in R

## 🧠 Summary
Today’s session focused on two important **data structures in R** — **Data Frames** and **Factors**.  
These are fundamental tools for organizing, analyzing, and categorizing data efficiently, especially in **data analytics** and **statistical modeling**.

A **Data Frame** is like a spreadsheet in R, where data is stored in rows and columns. Each column can hold different data types, making it ideal for real-world datasets.  
A **Factor**, on the other hand, is used to handle **categorical data** — such as gender, city names, or departments — by storing unique levels for better classification and analysis.

Both structures are key for **data cleaning, transformation, and visualization**, forming the base for advanced R programming and analytics tasks.

## 🔍 New Concepts Learned
- **Data Frames:** Two-dimensional structures that store data in tabular form.  
  - Created using `data.frame()`  
  - Key functions:  
    - `summary()` → Provides data summary  
    - `length()` → Returns number of columns  
    - `dim()` → Returns number of rows and columns  
    - `nrow()` / `ncol()` → Count rows and columns  
    - `cbind()` / `rbind()` → Add new columns or rows  
  - Accessing data using `[ ]`, column names, or `$` operator  

- **Factors:** Used to represent **categorical data** with unique levels.  
  - Created using `factor()`  
  - Key functions:  
    - `levels()` → Shows unique categories  
    - `length()` → Returns number of elements  
    - Supports modification and addition of levels  

## 💻 Activity
- Created and manipulated **Data Frames** using `data.frame()`, `cbind()`, and `rbind()`  
- Practiced **data access methods** using indices, column names, and `$` operator  
- Summarized data using `summary()` and analyzed rows/columns with `nrow()` and `ncol()`  
- Built **Factors** to represent categorical data and explored `levels()` and `length()` functions  

## 🤔 Challenges Faced
It was a bit tricky to understand the difference between **numeric** and **factor levels** while adding new elements. Managing **data frames with mixed data types** also required careful handling to avoid mismatched structures.

## 🎯 Key Takeaway
Learning about **Data Frames** and **Factors** deepened my understanding of how R organizes and categorizes data. These structures are vital for **data preprocessing** in analytics — helping prepare raw data for meaningful insights and visualizations.
