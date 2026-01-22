# ✈️ Flight Delays Analysis (Python, Pandas, Matplotlib)

## Overview

This project explores **flight departure delays** using real-world airport data to understand **how the day of the week affects the likelihood of a delayed departure**. The analysis is implemented in a Jupyter Notebook and is designed to be both **learner-friendly** and **industry-relevant**, showcasing practical data cleaning, feature engineering, and exploratory data analysis (EDA) skills.

The notebook follows a clear, step-by-step workflow that mirrors how a data analyst or junior data scientist would approach a time-based operational problem.

---

## Business & Analytical Context

Flight delays impact:

* Passenger satisfaction
* Airline operating costs
* Airport congestion and scheduling efficiency

By identifying patterns in delays across days of the week, stakeholders can:

* Improve scheduling decisions
* Anticipate high-risk delay periods
* Allocate operational resources more effectively

---

## Dataset

### Primary Dataset

* **Source**: Sample of domestic departures from **Atlanta International Airport (ATL)**, one of the busiest airports in the world
* **Year**: 2023
* **File used in notebook**: `flights.csv`

### Key Columns

| Column Name            | Description                                           |
| ---------------------- | ----------------------------------------------------- |
| `scheduled`            | Scheduled departure time (datetime)                   |
| `actual`               | Actual departure time (datetime)                      |
| *(derived)* `delay`    | Difference between actual and scheduled departure     |
| *(derived)* `is_late`  | Boolean flag for flights delayed more than 15 minutes |
| *(derived)* `day_name` | Day of the week of departure                          |

> A flight is considered **late** if it departs **more than 15 minutes (900 seconds)** after its scheduled time.

---

## Project Workflow

### 1. Data Loading & Preparation

* Load CSV data using **pandas**
* Convert columns to appropriate datetime types
* Disable chained assignment warnings for clarity

### 2. Feature Engineering

* Compute flight delay using:

  ```
  delay = actual - scheduled
  ```
* Create a binary `is_late` column based on industry-standard delay thresholds
* Extract **day of week** from datetime values

### 3. Exploratory Data Analysis (EDA)

* Calculate the **percentage of delayed flights per day of the week**
* Sort results chronologically (Sunday → Saturday)
* Visualize delay patterns using a bar chart

### 4. Data Visualization

* Bar chart showing **percentage of delayed flights by day of week**
* Clear axis labeling for interpretability

---

## Key Insights

* **Sunday** has the highest percentage of delayed departures
* Delay likelihood varies meaningfully across the week
* Day-of-week trends suggest operational or passenger-volume influences

These insights demonstrate how **simple feature engineering combined with aggregation** can uncover actionable patterns in operational data.

---

## Skills Demonstrated

**Technical Skills**

* Python (pandas, matplotlib)
* Datetime manipulation
* Feature engineering
* Boolean logic & aggregation
* Data visualization

**Analytical Skills**

* Translating business questions into data tasks
* Applying real-world thresholds and assumptions
* Interpreting time-based patterns
* Communicating insights visually

---

## Project Extensions (Proposed)

An optional extension is included in the notebook:

* **Dataset**: `us-daily-passengers.csv`
* Analyze average number of airline passengers by day of week
* Compare passenger volume trends with delay percentages

**Goal**: Determine whether higher passenger volumes correlate with increased delay likelihood.

---

## How to Run the Project

1. Clone the repository
2. Ensure Python 3.8+ is installed
3. Install dependencies:

   ```bash
   pip install pandas matplotlib
   ```
4. Place `flights.csv` in the project directory
5. Open and run `flights-delays-project.ipynb`

---

## Who This Project Is For

* **Recruiters**: Demonstrates clean, structured analytical thinking and practical Python skills
* **Learners**: Provides a guided, end-to-end example of a real-world EDA project
* **Aspiring Data Analysts / Data Scientists**: Shows how to turn raw timestamps into business insights

---

Feel free to explore, fork, or build upon this project!
