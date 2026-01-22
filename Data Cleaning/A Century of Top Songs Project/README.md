☕ Data-Driven Strategy: Launching a Plant-Based Coffee Shop

## 📌 Project Overview

This repository contains end-to-end data analysis projects focused on transforming raw data into actionable insights. These projects demonstrate a strong proficiency in **Python**, **Pandas**, and **Matplotlib**, covering two distinct domains:

1. **Specialty Coffee Market Analysis:** Using survey data to build a launch strategy for a plant-based cafe.
2. **Cultural Analytics:** Analyzing a century of music to identify industry-wide shifts in song production.

---

## 🎯 Objectives

* **Business Intelligence:** Translate raw survey responses into inventory and marketing recommendations.
* **Time-Series Analysis:** Quantify the evolution of media (music) over a 100-year span.
* **Data Engineering:** Clean and restructure complex datasets (110+ columns) for statistical reliability.

---

## 📊 The Datasets

* **`coffee-survey-results.csv`**: A high-dimensional dataset containing ~1,000 responses from coffee enthusiasts, covering demographics, brewing habits, and ingredient preferences.
* **`top-song-durations.csv`**: A historical record of every #1 hit song from 1923 to 2023, featuring artist metadata and song lengths.

---

## 🛠️ Technical Workflow

*A step-by-step breakdown of the analytical process for learners and peers.*

### 1. Data Cleaning

* **Feature Selection:** Sliced large datasets to isolate relevant variables (e.g., extracting 5 key columns from a 113-column survey).
* **Handling Nulls:** Utilized `.dropna()` strategically to ensure demographic averages remained accurate.
* **Type Casting:** Converted string-based durations (HH:MM:SS) into numerical `total_seconds` to allow for mathematical modeling.

### 2. Feature Engineering

* **Categorical Encoding:** Mapped qualitative survey data (e.g., "1 cup") to quantitative floats (1.0) for statistical analysis.
* **Temporal Binning:** Segmented 100 years of data into "Eras" (Pre vs. Post-1968) to compare historical industry standards.

### 3. Exploratory Data Analysis (EDA)

* **Aggregation:** Applied `.groupby()` and `.mean()` to profile consumption habits across age ranges.
* **Visualization:** Developed sorted bar charts to provide immediate visual hierarchy of consumer preferences.

---

## 📈 Key Insights & Results

### **Market Analysis: The Plant-Based Cafe**

| Category | Finding | Strategic Recommendation |
| --- | --- | --- |
| **Top Sweetener** | **Granulated Sugar** | **63.9%** preference; prioritize as primary stock. |
| **Growth Demo** | **55-64 Year Olds** | Highest consumption (**2.1 cups/day**); target for loyalty programs. |
| **Specialty Trend** | **Raw & Brown Sugar** | **>25%** interest; essential for "specialty" branding. |

### **Music Trends: The 100-Year Shift**

* **The 1968 Pivot:** Identified a significant increase in song length. Average durations rose from **172.64s** (Pre-1968) to **230.48s** (Modern Era).
* **Historical Extreme:** The shortest #1 hit was identified as "Sonny Boy" (1928), lasting only **1 minute 55 seconds**.

---

## 🖼️ Visualizations

*(Note: Visuals are generated within the .ipynb files)*

> **[Graph: Sweetener Popularity Ranking]** > *A visualization used to justify inventory spending.*

> **[Graph: Music Duration Over Time]** > *A trend line showing the steady increase in song length as recording technology evolved.*

---

## 🚀 How to Run

### Option 1: Local Environment

1. Clone the repo: `git clone https://github.com/Aditi-dev07/Cisco_DataScience_Projects.git`
2. Install requirements: `pip install pandas matplotlib`
3. Run `jupyter notebook` and open the desired `.ipynb` file.

### Option 2: Google Colab

1. Click the **"Open in Colab"** badge at the top of the notebook.
2. Upload the corresponding `.csv` file when prompted by the `files.upload()` cell.

---

## 💼 Recruiter Quick-View

* **Problem Solving:** Demonstrated ability to clean "messy" real-world survey data.
* **Business Acumen:** Insights are framed as "Strategic Recommendations" rather than just numbers.
* **Tooling:** Expert use of the Python Data Science stack (Pandas/Matplotlib).
* **Communication:** Clearly documented workflow from raw data to final visualization.
---
*Created as part of the Cisco Data Science Projects collection.*
