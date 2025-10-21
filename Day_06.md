# 📘 Day 06

## ✅ Topic Covered
R-Charts in R

## 🧠 Summary
Today’s session focused on **data visualization in R**, particularly using **Graphs** and **Pie Charts**.  
R is a powerful tool for **data analytics and statistical representation**, and charts play a key role in presenting complex datasets in an easy-to-understand format.  
We explored how different chart types can be used to analyze relationships, proportions, and patterns visually.

**Graphs** help represent data through **scatter plots** and **line plots**, which are useful for identifying trends, correlations, and outliers.  
**Pie Charts**, on the other hand, display **categorical data distribution** — showing how parts contribute to a whole.  
Both tools are essential for making data-driven insights more interpretable in analytics.

## 🔍 New Concepts Learned
### **1. Graphs**
Graphs are used to visualize relationships between two numeric variables.  
Key functions explored:  
- `plot(x, y)` → Plots a basic graph  
- `plot(x, y, xlab=, ylab=)` → Adds axis labels  
- `plot(x, y, main=)` → Provides a graph title  
- `plot(x, y, col=)` → Adds colors to points or lines  
- `plot(x, y, cex=)` → Defines point size (default = 1)  
- `plot(x, y, pch=)` → Changes point shape (1–25 range)  
- `plot(x, y, type="l")` → Draws line plots  
- `plot(x, y, lwd=)` → Adjusts line width (default = 1)  
- `lines(line_coords, type="l")` → Adds multiple lines  
- `points(x, y)` → Combines multiple points on a single graph  

These features make graphs flexible for visualizing patterns in datasets — a crucial step in **data exploration and analytics**.

### **2. Pie Chart**
A **Pie Chart** is a circular chart divided into segments that represent proportions of a whole.  
It’s ideal for visualizing **categorical data distribution** or **percentage comparisons**.

Key functions explored:  
- `pie(x)` → Plots a pie chart  
- `pie(x, init.angle=)` → Changes the starting point of the chart (default = 0°)  
- `pie(x, radius=)` → Adjusts the pie chart size  
- `pie(x, main=)` → Adds a chart title  
- `legend(position, labels, fill=color, inset=(x, y))` → Adds legends for clarity  

These visual elements enhance the storytelling aspect of data analytics, helping analysts and audiences interpret data more intuitively.

## 💻 Activity
- Created **scatter plots** and **line graphs** using `plot()` and `lines()` functions  
- Customized charts by adding **labels**, **colors**, **titles**, and **legends**  
- Designed **pie charts** to represent categorical data visually  
- Experimented with **graph parameters** like `pch`, `lwd`, and `cex` to improve readability  

## 🤔 Challenges Faced
At first, managing multiple customization parameters (like color, size, and type) in a single plot was a bit confusing.  
Understanding how to combine **multiple lines and points** on one graph required practice.

## 🎯 Key Takeaway
Today’s class strengthened my understanding of **data visualization in R**.  
Graphs and Pie Charts are not just tools for representation — they are essential for uncovering patterns and insights in data analytics.  
Visualizing data effectively helps communicate findings clearly and supports informed decision-making.
