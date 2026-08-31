# 📊 AI Impact on Student Performance

## 📌 Project Overview

**AI Impact on Student Performance** is a Data Analytics and Visualization project designed to analyze the relationship between **Artificial Intelligence (AI) usage and student academic performance**.

The project examines different aspects of student data, including **AI usage status, AI tools used, AI usage purpose, attendance percentage, grade level, final score, and AI dependency score**.

The project follows a complete data analytics workflow, starting from **data understanding and cleaning in Microsoft Excel** and progressing to **interactive data visualization and dashboard development using Microsoft Power BI**.

The project is divided into two major phases:

* **Phase 1 – Data Understanding & Data Cleaning**
* **Phase 2 – Data Visualization & Interactive Dashboard Development**

The final output is an interactive **three-page Power BI dashboard** that allows users to explore overall student performance, AI usage patterns, and individual student-level information.

---

# 🎯 Project Objectives

The main objectives of this project are:

1. **Analyze Student Performance**

   To understand overall academic performance using the final score and other relevant student-related factors.

2. **Analyze AI Usage**

   To identify students who use AI and compare AI users with non-AI users.

3. **Study AI Tools**

   To analyze the different AI tools used by students and understand their distribution.

4. **Analyze AI Usage Purpose**

   To understand the different purposes for which students use AI tools.

5. **Study AI and Academic Performance**

   To analyze the relationship between AI usage and students' average final scores.

6. **Analyze Attendance**

   To study attendance percentage and its relationship with academic performance.

7. **Analyze AI Dependency**

   To examine AI dependency scores and their relationship with final scores.

8. **Develop an Interactive Dashboard**

   To create an easy-to-use Power BI dashboard containing KPIs, charts, slicers, navigation buttons, bookmarks, and drill-through functionality.

---

# 📂 Dataset Description

## Dataset Name

**AI Student Performance Dataset**

The dataset contains information related to students, their academic performance, attendance, and AI usage behaviour.

According to the Phase 1 report, the dataset contains:

* **Records:** 8,000 students
* **Columns:** 26
* **Initial Tool:** Microsoft Excel

The cleaned dataset was later used for Power BI analysis and dashboard development.

---

## 🔑 Important Dataset Fields

Some of the important fields used in the project include:

| Field                   | Description                           |
| ----------------------- | ------------------------------------- |
| `student_id`            | Unique identifier for each student    |
| `grade_level`           | Grade/academic level of the student   |
| `uses_ai`               | Indicates whether the student uses AI |
| `ai_tools_used`         | AI tools used by students             |
| `ai_usage_purpose`      | Purpose of AI usage                   |
| `attendance_percentage` | Student attendance percentage         |
| `final_score`           | Final academic performance score      |
| `ai_dependency_score`   | Score representing AI dependency      |

These fields are used to create different analyses and visualizations in Power BI.

---

# 🧹 Phase 1 – Data Understanding & Data Cleaning

The first phase of the project focused on understanding the dataset and improving its data quality before performing visualization and analysis.

## Data Cleaning Activities

### 1. Duplicate Checking

Duplicate records were checked using the Excel **Remove Duplicates** feature.

**Result:** No duplicate rows were found.

### 2. Missing Value Checking

Blank or missing cells were checked using Excel filters.

**Result:** No actual blank cells were identified in the checked dataset.

### 3. Categorical Data Checking

Categorical fields were checked for consistency.

The fields checked include:

* Gender
* Grade Level
* Uses AI
* AI Tools Used
* AI Usage Purpose

The existing value **"None"** in categorical fields such as `ai_tools_used` and `ai_usage_purpose` was preserved as a dataset value.

### 4. Numerical Data Checking

Numerical and decimal values were checked for appropriate formatting.

Age values were also checked against the range used during the cleaning process.

### 5. Cleaned Dataset Preparation

After completing the required checks, the cleaned Excel dataset was prepared for further analysis and visualization.

---

# 📊 Phase 1 – Planned Analysis

The Phase 1 report identified several Pivot Table analyses to understand the dataset.

These include:

1. Gender-wise Student Count
2. Grade Level-wise Student Count
3. AI Users vs Non-AI Users
4. AI Tools Used Distribution
5. AI Usage Purpose Distribution
6. AI Usage vs Average Final Score
7. Grade Level vs Average Final Score
8. AI Usage Purpose vs Average Final Score
9. AI Dependency Score vs Average Final Score
10. Attendance Percentage vs Average Final Score

These analysis areas form the foundation for the Power BI dashboard.

---

# 📈 Phase 2 – Power BI Dashboard

After completing the data preparation stage, the cleaned dataset was imported into **Microsoft Power BI**.

The objective of Phase 2 was to transform the cleaned data into an interactive dashboard that makes analysis easier and more visually understandable.

The Power BI report contains **three pages**.

---

# 📄 Page 1 – Overview Dashboard

The **Overview Dashboard** acts as the main summary page of the report.

## KPI Cards

The dashboard contains four important KPI cards:

* **Total Students**
* **Average Final Score**
* **Average Attendance**
* **AI Users**

These KPIs provide a quick summary of the dataset.

## Visualizations

The Overview page includes:

* AI User Distribution
* Grade Level Student Count
* AI Usage vs Average Final Score

## Slicers

Interactive slicers are provided for:

* Grade Level
* AI Usage
* AI Tool Used

These slicers allow users to dynamically filter the dashboard.

---

# 🤖 Page 2 – AI Usage Analysis

The second page focuses specifically on **AI usage behaviour and its relationship with student performance**.

## Main Visualizations

The page contains:

### AI Tools Used Distribution

Shows the distribution of AI tools used by students.

### AI Usage Purpose Distribution

Shows the different purposes for which students use AI.

### AI Dependency Score Analysis

Helps analyze AI dependency in relation to student performance.

### AI Usage Purpose vs Average Final Score

Allows comparison between AI usage purposes and students' average final scores.

## Slicers

The page provides four slicers:

* AI Usage Status
* AI Tool Used
* AI Usage Purpose
* Grade Level

These filters allow users to perform more specific analysis.

---

# 👨‍🎓 Page 3 – Student Performance

The third page is designed for **student-level analysis**.

It contains a **Student Details Table** and is prepared as the destination page for drill-through analysis.

## Drill-through

The recommended drill-through field is:

`student_id`

A user can select a student and use:

**Right Click → Drill Through → Student Performance**

This opens the detailed information for the selected student.

## Back Button

A **Back Button** is included so that users can easily return to the previous dashboard page.

---

# ⚙️ Power BI Interactive Features

The dashboard includes several interactive features.

## 🔹 KPI Cards

KPI cards display important summary measures at a glance.

## 🔹 Charts

Charts are used to compare:

* AI usage
* Grade level
* Attendance
* Final score
* AI tools
* AI usage purpose

## 🔹 Slicers

Slicers allow users to filter the dashboard based on different categories.

## 🔹 Navigation Buttons

Navigation buttons allow users to move between:

**Overview → AI Analysis → Performance**

## 🔹 Bookmarks

Bookmarks can be used to save predefined dashboard states.

The report uses three main bookmark views:

* Overview
* AI Analysis
* Performance

## 🔹 Drill-through

Drill-through allows users to move from a selected student to a detailed student-level page.

## 🔹 Back Button

The Back button allows users to return from the drill-through page to the previous page.

---

# 🔄 Project Workflow

```text
AI Student Performance Dataset
              ↓
      Data Understanding
              ↓
        Data Cleaning
              ↓
       Data Validation
              ↓
       Cleaned Dataset
              ↓
        Data Analysis
              ↓
      Power BI Import
              ↓
       Data Visualization
              ↓
      Dashboard Design
              ↓
   Interactive Features
              ↓
      Final Dashboard
```

---

# 🛠️ Tools & Technologies Used

## Microsoft Excel

Used during Phase 1 for:

* Data understanding
* Data cleaning
* Duplicate checking
* Missing value checking
* Data validation
* Numerical and categorical data checking
* Pivot Table analysis preparation

## Microsoft Power BI

Used during Phase 2 for:

* Data visualization
* Dashboard development
* KPI cards
* Charts
* Slicers
* Filters
* Page navigation
* Bookmarks
* Drill-through
* Student-level analysis

## Power Query

Power Query can be used for data transformation and preparation where applicable. Specific Power Query transformation steps are not documented in the supplied Phase 1 and Phase 2 reports.

## DAX

DAX measures/calculations should only be listed here if they were actually used in the final Power BI file. The supplied project reports do not specifically document individual DAX formulas.

---

# 📸 Dashboard Screenshots

The final GitHub repository should include screenshots of the completed Power BI dashboard.

Recommended screenshots:

### 1. Overview Dashboard

Shows:

* KPI cards
* AI user distribution
* Grade-level analysis
* AI usage vs final score
* Slicers

### 2. AI Usage Analysis

Shows:

* AI tools distribution
* AI usage purpose
* AI dependency analysis
* AI usage purpose vs final score

### 3. Student Performance

Shows:

* Student details
* Selected student information
* Drill-through result
* Back button

> **Note:** Actual dashboard screenshots should be added to the GitHub repository after exporting or capturing the final Power BI pages.

---

# 🔍 Key Insights / Findings

The dashboard is designed to provide insights into the following areas:

### Student Performance

The dashboard provides an overall view of student performance using the **Average Final Score** KPI and performance-related visualizations.

### AI Usage

The dashboard allows users to identify AI users and compare AI usage patterns.

### AI Tools

The AI Tools Used Distribution visual helps understand which AI tools are represented in the dataset.

### AI Usage Purpose

The dashboard provides an analysis of different purposes for AI usage.

### AI and Final Score

The report includes **AI Usage vs Average Final Score** and **AI Usage Purpose vs Average Final Score**, allowing users to explore performance differences across AI-related categories.

### Attendance

Attendance percentage is included as an analysis dimension and can be studied against final score.

### AI Dependency

AI dependency score is included to examine its relationship with student performance.

> **Important:** Exact highest/lowest numerical findings should be added after checking the final Power BI dashboard values. The supplied Phase 1 and Phase 2 reports describe the analysis structure but do not provide all final numerical results.

---

# 📋 Dashboard Page Structure

| Page                | Main Purpose                | Important Features                |
| ------------------- | --------------------------- | --------------------------------- |
| Overview Dashboard  | Overall student performance | KPI Cards, Charts, Slicers        |
| AI Usage Analysis   | AI behaviour analysis       | AI Tools, AI Purpose, Dependency  |
| Student Performance | Student-level details       | Table, Drill-through, Back Button |

---

# 📌 Project Completion Status

| Requirement              | Status                              |
| ------------------------ | ----------------------------------- |
| Data Cleaning            | ✅ Completed                         |
| Dataset Preparation      | ✅ Completed                         |
| Minimum 3 Power BI Pages | ✅ Completed                         |
| Meaningful Page Names    | ✅ Completed                         |
| Page Headings            | ✅ Included                          |
| KPI Cards                | ✅ Included                          |
| Charts                   | ✅ Included                          |
| Slicers                  | ✅ Included                          |
| Navigation Buttons       | ✅ Included                          |
| Bookmarks                | ✅ Configured/Planned                |
| Drill-through            | ✅ Student Performance Page Prepared |
| Back Button              | ✅ Included                          |

---

# 🎯 Expected User Flow

The dashboard is designed to follow a simple user flow:

```text
Open Overview Dashboard
        ↓
View KPIs & Overall Trends
        ↓
Apply Slicers
        ↓
Open AI Usage Analysis
        ↓
Explore AI Tools & AI Purpose
        ↓
Select a Student
        ↓
Drill Through
        ↓
View Student Performance
        ↓
Click Back
        ↓
Return to Previous Page
```

---

# 🚀 Future Scope

The project can be enhanced in the future with:

### 1. Performance Forecasting

Machine Learning or forecasting techniques can be added to predict future student performance.

### 2. Real-Time Data

The dashboard can be connected to regularly updated or real-time data sources.

### 3. Automated Reports

Scheduled and automated reports can be generated and distributed to teachers or administrators.

### 4. Advanced Predictive Analytics

Predictive models can be added to identify factors that may influence student performance.

### 5. Advanced AI Analysis

Future versions can include more detailed analysis of AI dependency, AI usage frequency and academic outcomes.

---

# 🏁 Conclusion

The **AI Impact on Student Performance** project demonstrates a complete Data Analytics workflow, starting with data understanding and cleaning and progressing to interactive dashboard development.

In **Phase 1**, the dataset was checked for duplicates, missing values, categorical consistency, numerical formatting and other data-quality issues. The cleaned dataset was then prepared for analysis.

In **Phase 2**, the cleaned dataset was transformed into a structured **three-page Power BI dashboard** consisting of an Overview Dashboard, AI Usage Analysis and Student Performance page.

The use of **KPI cards, charts, slicers, navigation buttons, bookmarks and drill-through** makes the dashboard interactive and user-friendly.

Overall, the project provides a practical approach to analyzing student performance and AI usage behaviour and presents the results through an easy-to-understand visual dashboard.

---

# 📚 References

1. **AI Student Performance Dataset** – Project dataset.
2. **Phase 1 Report – AI Student Performance Analysis: Data Understanding & Data Cleaning Report.**
3. **Phase 2 Report – AI Impact on Student Performance: Power BI Dashboard Development & Interactive Analytics.**
4. Microsoft Power BI – Dashboard and data visualization documentation.
5. Microsoft Excel – Data cleaning and analysis features.

---

# 👤 Author

**Name:** AKSHAY R

**Course:** DATA ANALYTICS


**Academic Year:** 2026–2027

---

## ⭐ Project Summary

**Project:** AI Impact on Student Performance
**Domain:** Data Analytics & Visualization
**Dataset Size:** 8,000 Students
**Columns:** 26
**Tools:** Excel, Power BI
**Dashboard Pages:** 3
**Main Features:** KPI Cards, Charts, Slicers, Navigation, Bookmarks, Drill-through
**Project Phases:** Data Cleaning → Data Analysis → Visualization → Interactive Dashboard
