# ⌨️ Typing Speed Analysis (Python, Pandas, Visualization)

## Overview

This project analyzes **typing speed test results** to explore patterns in **words per minute (WPM)** performance across different users and tests. The notebook demonstrates how to clean numerical data, compute descriptive statistics, and visualize distributions to draw meaningful conclusions from everyday performance data.

The project is intentionally designed to be:

* **Beginner-friendly** for learners practicing EDA
* **Recruiter-oriented** by highlighting core analytical and visualization skills

---

## Problem Context

Typing speed is a commonly measured productivity metric used in:

* Skill assessments
* Educational tools
* Hiring tests and online platforms

This analysis focuses on understanding:

* Typical typing speed ranges
* Performance variability
* How summary statistics and plots can reveal trends

---

## Dataset

### Source File

* **File name**: `typing-speeds.csv`
* **Description**: Contains typing test results measured in words per minute

### Key Columns

| Column | Description                      |
| ------ | -------------------------------- |
| `wpm`  | Typing speed in words per minute |

---

## Data Preparation

The dataset required minimal but important preprocessing:

* Load data using pandas
* Ensure numeric typing speed values
* Remove or handle invalid / missing entries (if present)

This reflects a realistic scenario where not all datasets are perfectly clean.

---

## Analysis Workflow

### 1. Descriptive Statistics

* Calculate:

  * Mean typing speed
  * Median typing speed
  * Standard deviation
* Use these metrics to understand central tendency and spread

### 2. Distribution Analysis

* Visualize typing speed distribution using plots
* Identify:

  * Common WPM ranges
  * Outliers or unusually high/low scores

### 3. Interpretation

* Relate observed patterns to real-world expectations
* Discuss variability in human performance data

---

## Key Insights

* Typing speeds cluster around a central range rather than being evenly distributed
* A small number of high-WPM values can significantly affect the mean
* Visualizations provide faster insight than raw numbers alone

---

## Skills Demonstrated

### Technical Skills

* Python (pandas)
* Descriptive statistics
* Data visualization
* Exploratory Data Analysis (EDA)

### Analytical Skills

* Interpreting distributions
* Identifying outliers
* Translating raw metrics into insights

---

## How to Run the Project

1. Clone the repository
2. Ensure Python 3.8+ is installed
3. Install dependencies:

   ```bash
   pip install pandas matplotlib
   ```
4. Place `typing-speeds.csv` in the project directory
5. Open and run `typing-speeds.ipynb`

---

## Who This Project Is For

* **Recruiters**: Demonstrates strong fundamentals in statistics and visualization
* **Learners**: A clean introduction to EDA using a familiar, intuitive dataset
* **Aspiring Analysts**: Shows how simple datasets can still yield meaningful insights

---
