# 🎬 Netflix Data Analysis

A comprehensive exploratory data analysis (EDA) of Netflix's content library using Python, pandas, and Seaborn. This project answers key business questions about Netflix's catalog — from content trends and top directors to ratings breakdowns and country-wise distributions.

---

---

## 📌 Project Overview

This project performs a thorough analysis of the Netflix dataset to uncover trends and patterns across movies and TV shows. The notebook walks through:

- Data loading and initial exploration
- Data cleaning (duplicates, null values)
- Visual and statistical analysis to answer 13 specific problem statements

---

## 📦 Dataset

- **Source:** [Kaggle]
- **File:** `Dataset_Netflix.csv`
- **Key Columns:**

| Column | Description |
|---|---|
| `Show_Id` | Unique identifier for each title |
| `Category` | Movie or TV Show |
| `Title` | Name of the content |
| `Director` | Director(s) of the title |
| `Cast` | Cast members |
| `Country` | Country of production |
| `Release_Date` | Release date |
| `Rating` | Content rating (e.g., TV-14, R, PG-13) |
| `Duration` | Length in minutes or seasons |
| `Type` | Genre/type (e.g., Dramas, Comedies, Kids' TV) |

---

## 🛠️ Technologies Used

- **Python 3.x**
- **pandas** — data manipulation and analysis
- **seaborn** — statistical data visualization
- **matplotlib** — plotting support
---

## 🔍 Analysis & Questions Answered

The notebook systematically addresses the following problem statements:

1. **Show Details Lookup** — Find the Show ID and Director of *House of Cards*
2. **Release Year Trends** — Which year had the highest number of releases? *(Bar chart)*
3. **Content Distribution** — How many Movies vs. TV Shows exist? *(Count plot)*
4. **Year Filter** — List all Movies released in the year 2000
5. **Country Filter** — Titles of all TV Shows released in India
6. **Top Directors** — Top 10 directors by total content on Netflix
7. **Multi-condition Filter** — Movies categorized as Comedies, or content from the United Kingdom
8. **Cast Search** — How many titles featured Tom Cruise?
9. **Ratings Analysis**
   - All unique ratings on Netflix
   - Movies with TV-14 rating in Canada
   - TV Shows with R rating released after 2018
10. **Duration Analysis** — Maximum duration of any Movie/Show
11. **Country Rankings** — Which country has the highest number of TV Shows?
12. **Sorting** — Dataset sorted by release year (descending)
13. **Complex Filter** — Drama Movies *or* Kids' TV Shows

---

## 💡 Key Insights

- Netflix's content library grew significantly in the mid-2010s, peaking around **2019–2020**.
- **Movies** outnumber **TV Shows** in the catalog.
- The **United States** dominates in total content, with **India** ranking high for TV Shows.
- **TV-MA** and **TV-14** are the most common content ratings on the platform.
- The top directors have contributed a substantial volume of both Movies and TV Shows.

---

