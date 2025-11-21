
# 🌟 **AI/ML Job Market Insights Dashboard (Power BI)**


## 📸 Dashboard Preview

![Dashboard Preview](https://raw.githubusercontent.com/AabshaarShaikh20/AI-ML-Job-Market-Insights-Dashboard-Power-BI-/main/screenshot.JPG)





This Power BI project analyzes **2,000+ synthetic AI, ML, Data Science & Analytics job postings (2023–2025)** to uncover trends in hiring, skills, salaries, and experience levels across the industry.

The dashboard provides a clear view of the **AI job market**, helping understand which roles are in demand, what skills companies require, and how salaries vary across experience and locations.

---


## 🔍 **Key Features of the Dashboard**


### ✅ **1. Job Posting Trends Over Time**

A line chart showing how AI job postings fluctuate monthly across 2023–2025.

### ✅ **2. Jobs Posted by Day of the Week**

Identifies which weekdays have the highest AI/ML job postings.

### ✅ **3. Most In-Demand Job Titles**

A clean visual ranking the most frequently posted AI/ML roles such as:

* Data Scientist
* ML Engineer
* Data Analyst
* Computer Vision Engineer
* AI Product Manager

### ✅ **4. Salary vs Experience Level**

Shows how salary ranges increase from Entry → Mid → Senior → Lead → Director roles (using a calculated midpoint salary).


### ✅ **5. Smart Slicers**

To filter the entire dashboard by:

* **Location**
* **Industry**

---

## 📊 **Tools & Techniques Used**

* **Power BI Desktop**
* Data Cleaning & Transformation (Power Query)
*To calculate the mid-point of each salary range, I created a new DAX column:
salary_mid = ([salary_min] + [salary_max]) / 2

**📝What I Did**

* The original salary_range column had values in a range format (e.g., 30,000–50,000).

* I split this into two separate columns: salary_min and salary_max.

* Using these two fields, I created another calculated column salary_mid, which stores the midpoint salary for easier analysis and comparison.

---

## 📁 **Dataset Details**

The dataset includes:

* Job titles
* Company details
* Industry
* Required skills
* Tools preferred
* Salary ranges (USD)
* Location
* Experience level
* Posting dates (2023–2025)

Although synthetic, the dataset is designed to reflect **real-world hiring trends** in AI & Machine Learning.

---

## 🚀 **Why This Project Matters**

This dashboard is perfect for:

* Understanding AI hiring patterns
* Analyzing salary expectations
* Identifying high-demand roles
* Tracking industry and location trends
* Showcasing Power BI skills for resumes / portfolios


Connect @Aabshaar Shaikh


