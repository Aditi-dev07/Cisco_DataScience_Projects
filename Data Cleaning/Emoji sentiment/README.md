# 📊 Data Science Portfolio: Market Strategy, Historical Trends & Sentiment Analysis
---

## 📌 Project Overview
This repository contains a curated collection of data analysis projects focused on transforming raw datasets into actionable business intelligence and cultural insights. By leveraging the Python data science stack, these projects address real-world challenges ranging from retail inventory optimization to social media linguistics and historical media trends.

1.  **A Plant-Based Coffee Shop:** Market research to define the launch strategy for a specialty cafe.
2.  **A Century of Top Songs:** A longitudinal study exploring the evolution of music from 1923 to 2023.
3.  **Emoji Sentiment Analysis:** An investigation into the emotional mapping and positioning of emojis in 1.6 million tweets.

---

## 🎯 Objectives
* **Business Intelligence:** Translate consumer survey data into specific inventory and demographic targeting recommendations.
* **Data Reliability:** Implement rigorous data cleaning pipelines to ensure statistical accuracy in high-dimensional datasets.
* **Trend Forecasting:** Identify historical "pivot points" in media production and consumer preferences.
* **Linguistic Mapping:** Quantify the relationship between digital symbols (emojis) and human sentiment.

---

## 📊 The Datasets
* **`coffee-survey-results.csv`**: Responses from ~1,000 coffee enthusiasts covering brewing habits and ingredient preferences.
* **`top-song-durations.csv`**: A 100-year record of every #1 hit song, including artist metadata and duration.
* **`emoji-sentiment.csv`**: Sentiment scores (Positive/Negative/Neutral) and positioning data derived from 1.6M multi-lingual tweets.

---

## 🛠️ Technical Workflow
*A systematic approach designed for reproducibility and analytical depth.*

### 1. Data Cleaning & Standardization
* **Feature Extraction:** Sliced datasets with 110+ columns to isolate key variables for specific business questions.
* **Integrity Management:** Handled missing values (`NaN`) and performed type-casting on time-series data (converting `HH:MM:SS` strings to numeric `total_seconds`).
* **Data Normalization:** Standardized categorical responses to ensure consistency across large-scale survey data.

### 2. Feature Engineering
* **Categorical Encoding:** Mapped qualitative survey ranges to quantitative scales (e.g., converting "cups per day" strings to floats for averaging).
* **Temporal Segmentation:** Binning a century of data into "Eras" (Pre-1968 vs. Modern) to reveal hidden industry shifts.
* **Sentiment Metrics:** Calculating normalized sentiment scores based on emoji occurrence and tweet polarity.

### 3. Exploratory Data Analysis (EDA)
* **Demographic Profiling:** Used `.groupby()` and `.agg()` to identify the highest-spending and highest-consuming user segments.
* **Visual Synthesis:** Crafted sorted horizontal bar charts and trend lines to provide immediate clarity to stakeholders.

---

## 📈 Key Insights & Results

### **I. Market Strategy (Plant-Based Coffee Shop)**
| Strategic Metric | Leading Insight | Business Recommendation |
| :--- | :--- | :--- |
| **Top Sweetener** | **Granulated Sugar (63.9%)** | Primary inventory priority; stock in high volume. |
| **Growth Segment** | **Age 55–64 (2.1 cups/day)** | Target this cohort for premium loyalty programs. |
| **Specialty Trend** | **Oat & Almond Milk** | Essential plant-based drivers for modern specialty shops. |

### **II. Historical & Linguistic Trends**
* **The 1968 Musical Pivot:** Identified a significant shift in song production; average durations rose from **172.64s** (Pre-1968) to **230.48s** (Post-1968).
* **Emoji Sentiment Positioning:** Data reveals that **negative emojis** are statistically placed closer to the **end of tweets** (avg position 0.681) compared to positive ones (0.662), suggesting a "concluding" emotional weight in digital communication.

---

## 🚀 How to Run
### 1. Environment Setup
Clone the repository and install the required dependencies:
```bash
git clone [https://github.com/Aditi-dev07/Cisco_DataScience_Projects.git](https://github.com/Aditi-dev07/Cisco_DataScience_Projects.git)
pip install pandas matplotlib

*Created as part of the Cisco Data Science Projects collection.*
