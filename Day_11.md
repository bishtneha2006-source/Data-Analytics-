# 📘 Day 11

## ✅ Topic Covered
Data View Manipulation in R using `tidyr` and `reshape2`

## 🧠 Summary
Today’s session focused on **view manipulation in R**, specifically converting between **wider and longer views** using the **`tidyr`** and **`reshape2`** libraries. Reshaping data is essential for creating **tidy datasets** suitable for analysis, visualization, and modeling. The session covered two main tasks: **Wider view to Longer view** and **Longer view to Wider view**, helping to reshape student marks data efficiently.

## 🔍 New Concepts Learned
### **1. Using `tidyr` Library**
Example data frame of student marks:  
```r
st_test1 <- data.frame(
  id = c(1,2,3),
  name = c("alice","bob","john"),
  test1 = c(92,91,85),
  test2 = c(98,80,87),
  test3 = c(92,93,90)
)
```

Key functions learned:

* **Wider view to Longer view** →
```r
pivot_longer(st_test1, cols = starts_with("test"), names_to = "test", values_to = "score")
```
This converts multiple test columns into a **single column of test names and scores**.

* **Longer view to Wider view** →
```r
st_test2 %>% pivot_wider(names_from = "test", values_from = "score")
st_test3 <- spread(st_test2, test, score)
```
This reshapes the data back to the **original wide format** with separate test columns.

### **2. Using `reshape2` Library**

Example data frame (same as above):
```r
st_test1 <- data.frame(
  id = c(1,2,3),
  name = c("alice","bob","john"),
  test1 = c(92,91,85),
  test2 = c(98,80,87),
  test3 = c(92,93,90)
)
```

Key function learned:

* **Wider view to Longer view** →
```r
melt(st_test1, id.vars = c("id","name"), variable.name = "test", value.name = "score")
```
This converts wide-format test columns into a **long-format table**, similar to `pivot_longer()` in `tidyr`.

## 💻 Activity

* Created a **student marks data frame**
* Converted data from **wider view to longer view** using both `tidyr` and `reshape2`
* Converted data back from **longer view to wider view** using `pivot_wider()` and `spread()`
* Compared outputs to understand **differences between the two libraries**

## 🤔 Challenges Faced

* Remembering the **correct syntax** for `pivot_longer`, `pivot_wider`, and `melt`
* Ensuring that **column names and values** were correctly mapped during reshaping
* Managing intermediate data frames when converting between **longer and wider views**

## 🎯 Key Takeaway

* Both **`tidyr`** and **`reshape2`** provide efficient tools for **reshaping datasets** in R
* Converting between **longer and wider views** is essential for **tidy data analysis**
* Mastering these functions enhances **data cleaning, preparation, and analysis**
