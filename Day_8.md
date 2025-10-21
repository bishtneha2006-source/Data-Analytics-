# 📘 Day 08

## ✅ Topic Covered
Built-in Datasets in R-Studio

## 🧠 Summary
Today’s session focused on **Built-in Datasets in R-Studio**, which are preloaded collections of structured data available for analysis and practice.  
These datasets are widely used in **data analytics**, **data visualization**, and **machine learning** for testing and experimenting with different models and functions.  

In R, datasets are treated just like **data frames**, meaning all the data frame functions can be applied directly to them.  
Exploring these datasets helps us understand how real-world data is structured, cleaned, and analyzed for insights.

Some of the most popular datasets include **iris**, **mtcars**, **airquality**, and **AirPassengers**, each designed for different analytical tasks like classification, regression, and time-series forecasting.

## 🔍 New Concepts Learned
### **1. Built-in Datasets**
R provides more than **180 built-in datasets**, each containing meaningful and structured data.  
A few common examples discussed in class were:

- **`iris`** – Contains measurements of three species of iris flowers (used in classification).  
- **`mtcars`** – Provides data on 1973–74 car models, including features like horsepower and fuel efficiency (used in regression & clustering).  
- **`airquality`** – Records New York City’s air quality data (used in time-series and environmental analysis).  
- **`AirPassengers`** – A classic time-series dataset showing monthly airline passenger data from 1949–1960 (used for forecasting).

### **2. Key Functions**
Essential functions to explore and analyze datasets in R:

- **Accessing Datasets:** `data()` → Loads built-in datasets  
- **Listing All Datasets:** `data(package = .packages(all.available = TRUE))`  
- **Dimensions of Dataset:** `dim(iris)` → Shows number of rows and columns  
- **View Column Names:** `names(iris)` → Displays column names  
- **Dataset Summary:** `summary(iris)` → Provides statistical summary  
- **Help Information:** `?iris` → Displays dataset documentation  
- **Minimum Value:** `min(iris$Sepal.Length)` → Finds minimum in a column  
- **Maximum Value:** `max(iris$Sepal.Length)` → Finds maximum in a column  
- **Mean:** `mean(iris$Sepal.Length)` → Calculates mean value  
- **Median:** `median(iris$Sepal.Length)` → Calculates median value  
- **Mode:** `names(sort(-table(iris$Sepal.Length)))[1]` → Finds mode manually  

## 💻 Activity
- Explored **built-in datasets** like `iris` and `mtcars` using the `data()` function  
- Applied **summary and dimension functions** to understand dataset structure  
- Calculated **mean, median, and mode** for specific columns in the `iris` dataset  
- Listed all available datasets in R using the `data(package=...)` command  

## 🤔 Challenges Faced
Understanding how to manually find the **mode** without a direct function was slightly confusing at first.  
Also, exploring dataset documentation through `?dataset_name` required some practice to interpret the information effectively.

## 🎯 Key Takeaway
Built-in datasets in R provide a great foundation for learning **data manipulation and analysis**.  
They allow beginners to practice data exploration, apply statistical functions, and prepare for more advanced analytics tasks like **model building** and **visualization**.
