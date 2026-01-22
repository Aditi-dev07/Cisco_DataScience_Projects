# 🎵 A Century of Top Songs: Data Analysis Project
## 📌 Project Overview
What makes a song a #1 hit? Does duration play a role in a song's success? This project explores a century of musical evolution (1923–2023), specifically analyzing how the length of chart-topping hits has shifted over time. From the "Roaring 20s" to the streaming era, this analysis uncovers the patterns behind the world's most popular music.

### 🎯 Objectives
* **Data Cleaning:** Transform raw duration strings (HH:MM:SS) into numerical formats for statistical analysis.
* **Trend Analysis:** Compare average song durations across different historical eras (pre-1968 vs. post-1968).
* **Visualization:** Graph the evolution of song lengths to identify shifts in listener preferences and industry standards.

---

## 📊 The Dataset
The project utilizes a dataset containing every #1 hit song from **1923 to 2023**.
* **Source:** `top-song-durations.csv`
* **Key Features:** `year`, `artist`, `title`, and `duration`.
* **Highlights:** * **Shortest Song:** "Sonny Boy" by Al Jolson (1928) - 1 minute 55 seconds.
    * **Modern Reference:** "Last Night" by Morgan Wallen (2023) - 2 minutes 43 seconds.

---

## 🛠️ Technical Workflow & Tools

### Tech Stack
* **Language:** Python 🐍
* **Libraries:** Pandas (Data Manipulation), Matplotlib (Visualization).
* **Environment:** Jupyter Notebook / Google Colab.

### Key Data Engineering Steps
1.  **Format Conversion:** To perform calculations, the `duration` column was parsed from a string format to `total_seconds`.
2.  **Statistical Segmentation:** The data was split at 1968 to compare "classic" era durations against "modern" trends.
3.  **Handling Extremes:** Identified outliers and historical anomalies (e.g., extremely short hits during the 1920s).

---

## 📈 Key Insights
* **Significant Growth:** There is a marked difference in song length over the century. The average duration **before 1968 was ~172.64 seconds**, whereas in **1968 or later, it increased to ~230.48 seconds**.
* **The 1968 Turning Point:** This year serves as a statistical "pivot," likely reflecting changes in recording technology (LP vs. 45s) and creative shifts in the music industry.

---

## 👨‍💻 Learner-Friendly Guide
If you are new to Data Science, this notebook demonstrates:
1.  How to use `.convert_dtypes()` for cleaner dataframes.
2.  Using `.query()` for quick data filtering.
3.  How to troubleshoot plotting errors when dealing with non-numeric data types.

---

## 🚀 How to Run
1. Clone this repository.
2. Ensure you have `pandas` and `matplotlib` installed: `pip install pandas matplotlib`.
3. Open `top-songs-project.ipynb` in your preferred editor.
4. Upload `top-song-durations.csv` when prompted.

---

## 💼 Recruiter Quick-View
* **Problem-Solving:** Addressed data type constraints to enable time-series analysis.
* **Analytical Thinking:** Segmented 100 years of data to identify distinct historical trends.
* **Communication:** Clearly documented findings through integrated markdown and visual storytelling.

---
*Created as part of the Cisco Data Science Projects collection.*
