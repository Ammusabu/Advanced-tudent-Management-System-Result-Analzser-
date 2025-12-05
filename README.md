Advanced Student Management System (Result Analyzer)

A web-based system to manage students, analyze marks, generate performance charts, and track section-wise analytics.

🔗 Live App: https://student-result-analysis.netlify.app/

📌 Overview

The Advanced Student Management System is designed for schools and teachers to:

Add and manage students

Create and manage sections

Analyze class performance

Visualize data using interactive charts

Import and export student records

Built using HTML, CSS, JavaScript, Chart.js, and DSA concepts.

🧠 DSA Concepts Used
1. Arrays

Used to store:

List of students

List of sections

Subject marks

Chart datasets

2. Objects
'''
Each student is stored as an object:

{
  id: "S001",
  name: "Rahul Sharma",
  sectionId: "SEC001",
  marks: { english: 85, maths: 92, science: 88 }
}
'''
3. Sorting

Used for ranking top performers:

students.sort((a, b) => calculateAverage(b.marks) - calculateAverage(a.marks));

4. Searching & Filtering

Searching students by name/ID

Filtering by section

5. Aggregation Algorithms

Used to compute:

Class average

Pass percentage

Highest & lowest scores

Grade distribution

Subject-wise averages

✨ Features
📊 Dashboard

Total students

Total sections

Class average

Pass percentage

Performance trend chart

👨‍🎓 Student Management

Add student

View details in modal

Auto-grade calculation

Delete student

Search + section filter

🏫 Section Management

Add section

Assign teacher, room, capacity

Section capacity progress bar

Delete section

📈 Analytics Page

Subject-wise performance chart

Grade distribution pie chart

Section performance bar chart

Top 10 performers table

Pass/Fail summary

📥 Import & Export

Import student records from CSV

Auto-validate marks and section

Export all or section-wise report

Download sample CSV

🛠 Tech Stack

HTML5

CSS3

JavaScript (ES6)

Chart.js

PapaParse.js (CSV handling)

Netlify (Deployment)

📂 Project Structure
index.html
│── UI + Styling
│── Student CRUD
│── Section CRUD
│── Analytics + Charts
│── CSV Import/Export
│── DSA-based calculations

🧪 How to Use
1️⃣ Add Sections

Enter section name, teacher, room, max students

System assigns color + auto-generated ID

2️⃣ Add Students

Enter ID, name, section, and marks

System calculates:

Average

Grade

Rank in analytics

3️⃣ View Dashboard

Updates automatically with:

Stats

Trends

Top performers

4️⃣ Check Analytics

Get:

Subject-wise averages

Grade distribution

Section-wise performance

5️⃣ Import / Export CSV

Import students in bulk

Export student data anytime

📸 Screenshots (Replace with your own)
![Dashboard](Dashboard.png)
![Students Page](Students.png)
![Analytics](Analytics.png)

🚀 Future Enhancements

Login system (Admin / Teacher)

Database integration (Firebase / MongoDB)

PDF report card generator

Attendance module

AI-based performance prediction

Parent login dashboard

👩‍💻 Developer

Ammu S
Dsa Implpementation project

⭐ Support

If you like this project, please ⭐ star the repository!
