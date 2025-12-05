# Advanced Student Management System (Result Analyzer)

A web-based system to manage students, analyze marks, generate performance charts, and track section-wise analytics.

🔗 **Live App:** https://student-result-analysis.netlify.app/

---

## 📌 Overview
![Home screen](Dashboard.png)

The Advanced Student Management System is designed for schools and teachers to:

- Add and manage students  
- Create and manage sections  
- Analyze class performance  
- Visualize data using interactive charts  
- Import and export student records  

Built using **HTML, CSS, JavaScript, Chart.js, and DSA concepts**.

---

## 🧠 DSA Concepts Used

### **1. Arrays**
Used to store:
- List of students  
- List of sections  
- Subject marks  
- Chart datasets  

### **2. Objects**
Each student is stored as:

```js
{
  id: "S001",
  name: "Rahul Sharma",
  sectionId: "SEC001",
  marks: { english: 85, maths: 92, science: 88 }
}
```

### **3. Sorting Algorithms**
Used for ranking top performers:

```js
students.sort((a, b) => calculateAverage(b.marks) - calculateAverage(a.marks));
```

### **4. Searching and Filtering**

-Search students by name or ID
-Filter by section

### **5. Aggregation Algorithms**

Used to compute:

-Class average
-Pass percentage
-Highest & lowest score
-Subject-wise averages
-Grade distribution

## **✨ Features**
### 📊 Dashboard

Total students

Total sections

Class average

Pass percentage

Performance trend chart

### 👨‍🎓 Student Management

Add student

Student details modal

Auto-grade & average

Delete student

Search + filter

### 🏫 Section Management

Add sections

Teacher, room, max capacity

Section progress bar

### 📈 Analytics Page

Subject-wise bar chart

Grade distribution pie chart

Section performance chart

Top performers table

### 📥 Import & Export

Import students from CSV

Export full or section-wise data

Download sample CSV

### 🛠 Tech Stack

HTML5

CSS3

JavaScript

Chart.js

PapaParse.js

Netlify

### 📂 Project Structure
index.html
│── UI + Styling
│── Student CRUD
│── Section CRUD
│── Analytics + Charts
│── CSV Import/Export
│── DSA-based calculations

### 🧪 How to Use

Create Sections

Add Students with Marks

View Dashboard

Analyze Results

Import/Export CSV

### 🚀 Future Enhancements

Login system

Database support

PDF report card generator

Attendance module

AI-based performance prediction

### 👩‍💻 Developer

Ammu S
Passionate about AI, ML & Full-Stack Development.

## ⭐ Support

If you liked this project, please ⭐ star the repo!

