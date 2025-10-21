# 📘 Day 9

## ✅ Topic Covered
Statistical Analysis in R

## 🧠 Summary
Today’s session focused on **Statistical Analysis in R**, which is essential for **data analytics** and research.  
R is an **open-source statistical programming language** widely used in academia, research, and industry. Its strengths include a **wide variety of statistical packages**, with **over 18,000 packages available on CRAN** for specialized analysis.  

The session covered two major topics: **Basic Statistical Analysis** and **Statistical Hypothesis Testing**. These techniques help summarize data, detect patterns, and make data-driven decisions.

## 🔍 New Concepts Learned
### **1. Basic Statistical Analysis**
Basic statistical functions help summarize and understand numerical data. Using the example vector:  
`y_vector <- c(3, 4, 23, 67, 23, 78, 68, 34)`

Key functions learned:  
- Mean: `mean(y_vector)` → Calculates the average value  
- Median: `median(y_vector)` → Finds the middle value  
- Standard Deviation: `sd(y_vector)` → Measures data spread  
- Variance: `var(y_vector)` → Shows data variability  
- Mode: `names(sort(-table(y_vector)))[1]` → Finds the most frequent value  
- Quantiles (Q values): `quantile(y_vector)` or `quantile(y_vector, 0.75)` → Provides distribution at specific points

### **2. Statistical Hypothesis Testing**
Hypothesis testing compares **two opposing claims** about a population using sample data. Example vectors:  
`vector1 <- c(34, 23, 67, 34, 12, 67)`  
`vector2 <- c(78, 23, 45, 36, 28, 90, 16, 37)`

Key techniques learned:  
- T-Test: `t.test(vector1, vector2)` → Compares means of two groups  
- Chi-Square Test: `chisq.test(vector1)` → Tests goodness of fit for one vector  
- F-Test: `var.test(vector1, vector2)` → Compares variances of two vectors  
- Correlation Test: `cor.test(vector1, vector3)` → Determines relationship between two paired samples

## 💻 Activity
- Calculated **mean, median, standard deviation, variance, and quantiles** for sample data  
- Computed **mode** using a custom function  
- Applied **t-test, chi-square test, F-test, and correlation test** on example vectors  
- Explored how **R functions simplify statistical analysis** for decision-making

## 🤔 Challenges Faced
- Identifying which **statistical test to use** in different scenarios  
- Computing **mode manually** without a built-in function using `table()` and `sort()`

## 🎯 Key Takeaway
- **Statistical analysis in R** allows effective **data summarization and comparison**  
- **Hypothesis testing** provides a framework for **making data-driven decisions**  
- Mastering these functions strengthens the ability to **analyze, interpret, and present results**
