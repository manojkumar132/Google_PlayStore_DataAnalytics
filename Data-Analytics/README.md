# 📱 Real-Time Google Play Store Data Analytics - Python

## 👨‍💻 Internship Project - NullClass

**Intern Name**: Manoj Kumar J  
**Branch**: Artificial Intelligence and Data Science  
**Institution**: Nitte Meenakshi Institute of Technology  
**Project Duration**: 19-03-2025 to 19-04-2025  
**Tool Used**: Python (with Pandas, Matplotlib, Seaborn, Plotly, datetime, pytz)  

---

## 📌 Project Overview

This project focuses on building a real-time analytics dashboard for Google Play Store apps using Python. The analysis includes sentiment trends, app ratings, installs, revenue, and category-wise comparisons, with advanced filtering and time-based graph rendering.

---

## 📂 Folder Structure

📁 project-folder/ ├── Task1_Analysis_Sentiment_Bar_Chart.py ├── Task2_Dual_Axis_Install_Revenue.py ├── Task3_Violin_Rating_Distribution.py ├── google_play_store_dataset.csv ├── README.md └── Internship_Report.pdf

markdown
Copy
Edit

---

## 🧪 Tasks Overview

### ✅ Task 1: Sentiment Distribution Bar Chart

- **Goal**: Visualize sentiment distribution (positive, neutral, negative) of user reviews.
- **Grouped by**: Ratings (1–2, 3–4, 4–5 stars).
- **Filter**: Apps with more than 1,000 reviews.
- **Top 5 Categories** only.
- **Output**: A **stacked bar chart** of sentiment vs rating group.

### ✅ Task 2: Dual Axis Chart - Free vs Paid Apps

- **Goal**: Compare average installs and revenue of free vs paid apps.
- **Filter**:
  - Installs ≥ 10,000
  - Revenue ≥ $10,000
  - Android Version > 4.0
  - Size > 15MB
  - Content Rating = "Everyone"
  - App Name ≤ 30 characters
- **Top 3 Categories**
- **Time Restriction**: Graph visible **only between 1 PM to 2 PM IST**
- **Output**: **Dual-axis chart** using bar and line plots.

### ✅ Task 3: Violin Plot of Ratings

- **Goal**: Visualize rating distributions using a violin plot.
- **Filter**:
  - App name contains the letter “C”
  - Reviews ≥ 10
  - Rating < 4.0
  - Categories with more than 50 apps
- **Time Restriction**: Graph visible **only between 4 PM to 6 PM IST**
- **Output**: **Violin plot** by category.

---

## ⚙️ Technologies Used

- **Language**: Python  
- **Libraries**:
  - Pandas
  - Matplotlib
  - Seaborn
  - Plotly
  - Datetime
  - Pytz (timezone support)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/google-playstore-analytics.git
   cd google-playstore-analytics
Make sure google_play_store_dataset.csv is in the same folder as the .py files.

Run each task file:

bash
Copy
Edit
python Task1_Analysis_Sentiment_Bar_Chart.py
python Task2_Dual_Axis_Install_Revenue.py
python Task3_Violin_Rating_Distribution.py
⏰ Time-Based Conditions
Task 2 will run only between 1 PM – 2 PM IST

Task 3 will run only between 4 PM – 6 PM IST

If run outside these times, a message will be displayed instead of the graph.


📄 Internship Report
A detailed internship report is provided in this repository which includes:

Introduction

Learning Objectives

Tasks and Activities

Skills Gained

Challenges and Solutions

Results and Visualizations

Conclusion

🏁 Final Submission Checklist
 Code files for all 3 tasks

 README.md

 Internship report

 Dataset

 Time-based graph restrictions implemented

📬 Contact
If you have questions regarding the project:

Email: manumanoj50333@gmail.com
