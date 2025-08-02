# Data Analyst SQL Project 📊

## 📌 Introduction

This SQL project dives deep into job market trends for **Data Analyst** roles, using a relational database to extract actionable insights on job opportunities, salary trends, and in-demand skills. The project simulates real-world analytics and is designed to sharpen practical SQL skills while uncovering valuable data-driven patterns.

---

## 🧠 Background

As part of my learning journey in Data Analytics Engineering, I created this project to gain hands-on experience with structured query language (SQL). The dataset used mimics job postings and hiring trends for data-related positions. The focus was not just on writing queries, but also on interpreting real-life patterns such as salary ranges, top hiring companies, and skill demand.

---

## 🛠️ Tools Used

- **SQL**: Core querying language
- **PostgreSQL**: Relational database engine
- **DB Fiddle / DBeaver / PgAdmin** *(depending on environment used)*
- **Git & GitHub**: Version control and project publishing

---

## 📊 Analysis

The project is broken down into five focused SQL scripts. Each one answers a specific question relevant to a job-seeking Data Analyst or someone studying job market trends.

---

### 🔹 1. `1_top_paying_jobs.sql`
**Question Answered:**  
> What are the highest paying Data Analyst roles that offer remote flexibility?

**Insights:**  
- Ranks top 10 jobs by average yearly salary.
- Filters for remote jobs (`job_location = 'Anywhere'`) with non-null salaries.
- Helps identify which job titles offer the best compensation for remote analysts.

---

### 🔹 2. `2_top_hiring_companies.sql`
**Question Answered:**  
> Which companies are hiring the most Data Analysts?

**Insights:**  
- Counts and ranks companies by number of job listings.
- Includes only companies with at least 10 job postings.
- Useful for job targeting and company-specific applications.

---

### 🔹 3. `3_most_demanded_skills.sql`
**Question Answered:**  
> What are the most in-demand skills for Data Analyst positions?

**Insights:**  
- Joins job postings with skills tables to find which skills appear most.
- Only considers postings with remote availability and valid salaries.
- Can guide skill development and resume optimization.

---

### 🔹 4. `4_highest_paying_skills.sql`
**Question Answered:**  
> Which skills are associated with the highest average salaries?

**Insights:**  
- Calculates average salary for each skill based on job listings.
- Highlights top-paying technical competencies.
- Combines salary and demand to identify high-value skills.

---

### 🔹 5. `5_skill_demand_vs_salary.sql`
**Question Answered:**  
> Which skills offer both high demand and high salary?

**Insights:**  
- Combines demand and salary CTEs to show skill trade-offs.
- Filters to include only skills that appear in more than 10 postings.
- Great for balanced skill prioritization.

---

## 💡 What I Learned

- Writing complex queries using **JOINs** and **CTEs (Common Table Expressions)**
- Filtering and sorting real-world job data effectively
- Discovering insights from structured datasets
- Understanding the job market for data analyst roles
- Importance of combining demand with compensation when analyzing skills

---

## ✅ Conclusion

This project was a great hands-on exercise in both SQL and job market analytics. I now better understand how to navigate large datasets, use SQL for insight generation, and prioritize skills based on real hiring trends. This repository also serves as a portfolio-ready piece showcasing my ability to handle data end-to-end using SQL.

---

## 📁 Repository Structure

```plaintext
.
├── 1_top_paying_jobs.sql
├── 2_top_hiring_companies.sql
├── 3_most_demanded_skills.sql
├── 4_highest_paying_skills.sql
├── 5_skill_demand_vs_salary.sql
└── README.md
