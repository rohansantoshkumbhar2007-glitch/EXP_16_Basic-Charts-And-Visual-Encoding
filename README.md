# 📊 Experiment 16: Basic Charts and Visual Encoding
👨‍🎓 Student Information

# Name: Rohan Kumbhar
# PRN: 25070123141
# Experiment No.: 16

# 📌 Objective

The objective of this experiment is to understand the fundamentals of data visualization by creating basic charts and applying visual encoding techniques. The goal is to represent raw data in a graphical format that enhances readability, interpretation, and decision-making.

# 📖 Introduction

Data visualization is a key aspect of data analysis that transforms raw data into meaningful insights through graphical representation. Instead of analyzing large tables of numbers, charts allow users to quickly identify patterns, trends, and relationships.

This experiment focuses on:

Creating commonly used charts
Understanding when to use each chart
Applying visual encoding principles to improve clarity

# 📊 Types of Charts Implemented
1. Bar Chart
Used to compare values across discrete categories
Best suited for categorical data
Easy to interpret differences between groups
2. Line Chart
Represents data over a continuous interval or time
Helps in identifying trends and patterns
Commonly used in time-series analysis
3. Pie Chart
Displays proportional data as parts of a whole
Useful for percentage distribution
Best used when categories are limited
4. Scatter Plot
Shows relationship between two variables
Helps in identifying correlation or clustering
Widely used in statistical analysis

# 🎨 Visual Encoding Techniques

Visual encoding improves the effectiveness of charts by using visual cues:

Position: Determines where elements are placed on axes
Color: Highlights categories or differences
Size: Indicates magnitude or importance
Shape: Differentiates between data groups
Labels: Provide context and improve readability

Proper use of these elements ensures that the visualization is both informative and visually appealing.

# 🛠️ Tools & Technologies Used
Programming Language: Python
Libraries: Matplotlib, Seaborn
Environment: Jupyter Notebook / VS Code

# ⚙️ Implementation Details
📌 Sample Dataset
categories = ['A', 'B', 'C', 'D']
values = [10, 20, 15, 25]

# 📊 Bar Chart Example
import matplotlib.pyplot as plt

plt.bar(categories, values, color='skyblue')
plt.title("Bar Chart Example")
plt.xlabel("Categories")
plt.ylabel("Values")
plt.show()

# 📈 Line Chart Example
plt.plot(categories, values, marker='o', color='green')
plt.title("Line Chart Example")
plt.xlabel("Categories")
plt.ylabel("Values")
plt.show()
🥧 Pie Chart Example
plt.pie(values, labels=categories, autopct='%1.1f%%')
plt.title("Pie Chart Example")
plt.show()
🔵 Scatter Plot Example
plt.scatter(categories, values, color='red')
plt.title("Scatter Plot Example")
plt.xlabel("Categories")
plt.ylabel("Values")
plt.show()
▶️ How to Run the Project

Install required libraries:

pip install matplotlib seaborn

Clone or download the repository:

git clone <repository-link>

Navigate to the project directory:

cd project-folder

Run the Python file:

python experiment16.py
Observe the generated charts.

# 📈 Observations
Bar charts are best for comparisons.
Line charts effectively show trends.
Pie charts clearly represent proportions but can become cluttered.
Scatter plots help in identifying relationships between variables.
Proper use of color and labels significantly improves understanding.

# ✅ Result

The experiment successfully demonstrated how different types of charts can be used to represent data and how visual encoding enhances the clarity and effectiveness of visualizations.

# 🧠 Conclusion

Basic charts combined with effective visual encoding techniques play a crucial role in data visualization. They simplify complex datasets, making it easier to interpret and communicate insights efficiently.

# 🌍 Applications
Business Analytics and Reporting
Data Science and Machine Learning
Financial Analysis
Academic Research
Dashboard and UI Design
