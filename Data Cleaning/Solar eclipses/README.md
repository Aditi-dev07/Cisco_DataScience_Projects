# 🌑 Solar Eclipses Analysis (Python, Pandas)

## Overview

This project analyzes **historical and upcoming solar eclipses** to answer astronomy-focused questions using **data analysis techniques**. The goal is to demonstrate how raw, text-heavy datasets can be cleaned, transformed, and queried to extract meaningful insights.

The notebook is designed to be:

* **Learner-friendly**: clear questions, guided steps, and practical data cleaning
* **Recruiter-oriented**: demonstrates real-world data wrangling, datetime handling, and analytical reasoning

---

## Problem Statements

The analysis is driven by the following questions:

1. **When did the longest solar eclipse occur?**
2. **When did the longest *total* solar eclipse occur?**
3. **What is the average duration of total solar eclipses?**
4. **What are the next 10 upcoming solar eclipses?**

These questions require both **string manipulation** and **time-based analysis**, making them well-suited for demonstrating practical pandas skills.

---

## Dataset

### Source File

* **File name**: `solar-eclipses.csv`
* **Description**: Contains historical and future solar eclipse events with duration and date information

### Key Columns

| Column     | Description                                        |
| ---------- | -------------------------------------------------- |
| `date`     | Date of the solar eclipse                          |
| `type`     | Type of eclipse (Total, Partial, Annular, etc.)    |
| `duration` | Duration of eclipse (string format, e.g. `6m 38s`) |

---

## Data Preparation & Cleaning

The dataset required multiple preprocessing steps:

* Convert `date` column to datetime format
* Clean the `duration` column:

  * Remove text characters (`m`, `s`)
  * Convert durations into **total seconds** for numerical comparison
* Filter eclipses by type (e.g., *Total* only)

These steps reflect common real-world challenges when working with observational or scientific datasets.

---

## Analysis Workflow

### 1. Longest Solar Eclipse

* Convert duration strings into seconds
* Sort eclipses by duration
* Identify the maximum-duration eclipse

### 2. Longest Total Solar Eclipse

* Filter dataset to total eclipses only
* Apply the same duration-based ranking

### 3. Average Duration of Total Solar Eclipses

* Compute the mean duration (in seconds)
* Convert results back into a human-readable format

### 4. Upcoming Solar Eclipses

* Filter eclipses occurring after the current date
* Sort chronologically
* Display the next 10 events

---

## Key Insights

* Solar eclipse durations vary significantly depending on type
* Total eclipses are comparatively rare but have measurable duration patterns
* Datetime filtering enables seamless separation of historical vs future events

---

## Skills Demonstrated

### Technical Skills

* Python (pandas)
* String cleaning and transformation
* Datetime parsing and filtering
* Sorting and aggregation
* Exploratory data analysis (EDA)

### Analytical Skills

* Translating domain questions into data queries
* Applying numerical transformations to textual data
* Interpreting scientific data using code

---

## How to Run the Project

1. Clone the repository
2. Ensure Python 3.8+ is installed
3. Install dependencies:

   ```bash
   pip install pandas
   ```
4. Place `solar-eclipses.csv` in the project directory
5. Open and run `solar-eclipses.ipynb`

---
