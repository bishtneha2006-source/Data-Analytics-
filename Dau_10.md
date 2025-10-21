# 📘 Day 10

## ✅ Topic Covered
Data Manipulation in R

## 🧠 Summary
Today’s session focused on **Data Manipulation in R**, which is a crucial step in **data analytics** for preparing and cleaning datasets.  
The **`dplyr` library** is widely used for efficient data manipulation, including filtering, selecting, sorting, renaming, mutating, and handling missing values.  

The session covered two major areas: **Data Manipulation on Data Frames** and **Data Manipulation on Datasets**, helping to transform raw data into meaningful formats for analysis.

## 🔍 New Concepts Learned
### **1. Data Manipulation on Data Frames**
Using the example data frame:  
`dataframe <- data.frame(st_id = c(1, 2, 3), St_name = c("john", "merry", "april"), age = c(20, 21, 23))`

Key functions learned:  
- **Filter data** → `filter(dataframe, age > 21)` or `filter(dataframe, St_name == "john")` : Selects rows based on conditions  
- **Select columns** → `select(dataframe, St_name)` : Chooses specific columns from the data frame  
- **Sort data** → `arrange(dataframe, age)` or `arrange(dataframe, St_name)` : Sorts rows based on a column  
- **Rename column** → `rename(dataframe, St_name = dist)` : Renames a column  
- **Mutate column** → `dataframe %>% mutate(speed_n = speed^2)` : Creates new columns or modifies existing ones

### **2. Handling Missing Values**
Example data frame with missing values:  
`employee <- data.frame(emp_id = c(1, 2, 4, 2, NA), emp_name = c("john","merry",NA,"henry","walter"), salary = c(NA,2000,5000,NA,2000), age = c(20,NA,NA,24,35))`

Key functions learned:  
- **Check missing values** → `missing_frame <- is.na(employee)` : Identifies missing entries  
- **Fill missing values** → `fill(employee, emp_name, .direction = "updown")`  
`fill(employee, age, .direction = "downup")` : Fills missing values based on specified direction

## 💻 Activity
- Created a sample **data frame** of students and employees  
- Applied **filter**, **select**, **arrange**, **rename**, and **mutate** functions on data frames  
- Checked for **missing values** using `is.na()`  
- Filled missing values using **`fill()`** with different directions

## 🤔 Challenges Faced
- Remembering the **correct syntax** for `dplyr` functions  
- Deciding the **best method to fill missing values** based on the dataset  
- Ensuring that **mutations and renaming** did not overwrite important data

## 🎯 Key Takeaway
- **`dplyr`** provides efficient and readable functions for **data manipulation**  
- Proper handling of **missing values** is critical for accurate data analysis  
- Mastering these functions enhances the ability to **clean, transform, and prepare data** for analytics
