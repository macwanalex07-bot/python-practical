📘 Project Overview

The Smart Expense Tracker Application is a Python-based tool that helps users log, analyze, and visualize their expenses over time.
It uses:

Control Structures for input validation

OOP (Object-Oriented Programming) to structure functionality

NumPy & Pandas for efficient data handling

Matplotlib & Seaborn for clear visual insights

This project demonstrates strong Python fundamentals and data analysis skills.

🎯 Objectives

Allow users to record daily expenses.

Analyze spending habits using summaries and category-wise breakdowns.

Filter expenses by date, category, or amount.

Generate attractive visual reports (bar charts, line graphs, pie charts).

⚙️ Features

✅ Add new expenses with date, amount, category, and description
✅ Validate inputs (positive amounts, correct date format)
✅ Filter data by category, date range, or amount
✅ View summary of total, average, and category-wise spending
✅ Generate charts for spending trends using Matplotlib and Seaborn

🧩 Technologies Used
Component	Purpose
Python	Core programming language
Pandas	Data storage & analysis
NumPy	Numerical computations
Matplotlib	Data visualization
Seaborn	Advanced, aesthetic plotting
OOP	Class-based design and modularity
📂 Project Structure
SmartExpenseTracker/
│
├── expense_tracker.py       # Main Python script
├── expenses.csv              # Dataset (auto-created if missing)
└── README.md                 # Project documentation

🧠 Setup Instructions
1️⃣ Prerequisites

Make sure you have Python 3.8+ installed.
Then install the required libraries:

pip install pandas numpy matplotlib seaborn

2️⃣ Run the Application
python expense_tracker.py

3️⃣ When prompted:

Enter the expense date (format: YYYY-MM-DD)

Enter the amount (must be positive)

Enter the category (e.g., Food, Travel, Rent)

Add a short description

Your expenses will be saved to expenses.csv automatically.

📊 Example Charts

The program generates:

Bar Chart → Spending by Category

Line Graph → Monthly Spending Trend

Pie Chart → Category-wise Percentage

All charts include proper titles, labels, and legends.

💡 Future Enhancements

Add income tracking and budget goals

Export reports to PDF or Excel

Build a simple GUI using Tkinter or Streamlit

👨‍💻 Author

Name: Macwan Alex
Project Title: Smart Expense Tracker Application
Course / Subject: Python Data Analysis & Visualization Project
