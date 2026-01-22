# 🌋 Volcanic Eruptions Analysis (Python, Pandas, Data Exploration)

## Overview

This project analyzes **global volcanic eruption data** to uncover patterns related to eruption frequency, geographic distribution, and eruption characteristics. Using Python and pandas, the notebook demonstrates how to explore geophysical datasets and extract meaningful insights from structured tabular data.

The project is designed to be:

* **Learner-friendly**: clear steps and interpretable analysis
* **Recruiter-oriented**: highlights data wrangling, aggregation, and analytical reasoning skills

---

## Problem Context

Volcanic eruptions are significant natural events that impact:

* Climate and air quality
* Human settlements and infrastructure
* Geological and environmental research

This analysis focuses on answering questions such as:

* How frequently do volcanic eruptions occur?
* Which volcanoes erupt most often?
* What patterns exist in eruption history data?

---

## Dataset

### Source File

* **File name**: `volcanic-eruptions.csv`
* **Description**: Contains records of volcanic eruptions across different regions and time periods

### Key Columns

| Column              | Description                             |
| ------------------- | --------------------------------------- |
| `volcano_name`      | Name of the volcano                     |
| `country`           | Country where the volcano is located    |
| `start_year`        | Year the eruption began                 |
| `end_year`          | Year the eruption ended (if applicable) |
| `eruption_category` | Classification of eruption type         |

---

## Data Preparation & Cleaning

The dataset required several preprocessing steps:

* Load eruption records using pandas
* Handle missing or incomplete year values
* Ensure numeric consistency for time-based analysis
* Filter and group data by volcano and region

These steps reflect real-world challenges in working with historical and scientific datasets.

---

## Analysis Workflow

### 1. Eruption Frequency Analysis

* Count total eruptions recorded
* Identify volcanoes with the highest number of eruptions

### 2. Volcano-Level Aggregation

* Group data by volcano name
* Rank volcanoes by eruption count

### 3. Temporal Patterns

* Explore eruption occurrences across years
* Identify long-term trends or clusters in eruption activity

---

## Key Insights

* A small number of volcanoes account for a disproportionately large share of recorded eruptions
* Volcanic activity is unevenly distributed geographically
* Historical datasets often contain gaps that must be handled carefully during analysis

---

## Skills Demonstrated

### Technical Skills

* Python (pandas)
* Data cleaning and validation
* Grouping and aggregation
* Exploratory Data Analysis (EDA)

### Analytical Skills

* Pattern recognition in time-series-like data
* Translating scientific records into structured insights
* Handling incomplete historical data

---

## How to Run the Project

1. Clone the repository
2. Ensure Python 3.8+ is installed
3. Install dependencies:

   ```bash
   pip install pandas
   ```
4. Place `volcanic-eruptions.csv` in the project directory
5. Open and run `volcanic-eruptions.ipynb`

---

## Who This Project Is For

* **Recruiters**: Demonstrates strong data aggregation and analytical thinking
* **Learners**: A practical example of analyzing real-world scientific data
* **Aspiring Data Analysts / Scientists**: Shows ability to work with complex, imperfect datasets
