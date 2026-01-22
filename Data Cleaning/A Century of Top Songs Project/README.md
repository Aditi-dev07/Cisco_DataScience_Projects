# 🎵 A Century of Top Songs:

##  Project Overview
What makes a song a #1 hit? Does duration play a role in a song's success? This project explores a century of musical evolution (1923–2023), specifically analyzing how the length of chart-topping hits has shifted over time. From the "Roaring 20s" to the streaming era, this analysis uncovers the patterns behind the world's most popular music.

### Objectives
* **Data Cleaning:** Transform raw duration strings (HH:MM:SS) into numerical formats for statistical analysis.
* **Trend Analysis:** Compare average song durations across different historical eras (pre-1968 vs. post-1968).
* **Visualization:** Graph the evolution of song lengths to identify shifts in listener preferences and industry standards.

---

##  The Dataset
The project utilizes a dataset containing every #1 hit song from **1923 to 2023**.
* **Source:** `top-song-durations.csv`
* **Key Features:** `year`, `artist`, `title`, and `duration`.
* **Highlights:** * **Shortest Song:** "Sonny Boy" by Al Jolson (1928) - 1 minute 55 seconds.
    * **Modern Reference:** "Last Night" by Morgan Wallen (2023) - 2 minutes 43 seconds.

---

## Technical Workflow

### 1. Data Loading & Inspection
* **Source:** `top-song-durations.csv` covering years 1923–2023.
* Utilized `pandas` for data ingestion and initial exploratory data analysis (EDA).

### 2. Data Cleaning & Feature Engineering
* **Type Conversion:** Converted raw `duration` strings (MM:SS) into a numeric `total_seconds` format to enable mathematical analysis.
* **Optimization:** Used `df.convert_dtypes()` to ensure high-performance computation in `pandas`.

### 3. Exploratory Data Analysis (EDA)
* Identified outliers, such as the shortest and longest songs in the dataset.
* Segmented data into historical epochs (Pre-1968 vs. Post-1968) to test hypotheses regarding duration shifts.

### 4. Data Visualization
* Mapped the progression of song lengths over a 100-year timeline using `matplotlib`.

---

## Key Insights & Results

| Metric | Observation |
| :--- | :--- |
| **Shortest Hit** | *"Sonny Boy"* by Al Jolson (1928) - **115 seconds** |
| **Average Duration (Pre-1968)** | **172.64 seconds** (~2.8 minutes) |
| **Average Duration (Post-1968)** | **230.48 seconds** (~3.8 minutes) |

**Key Finding:** The data reveals a significant **33% increase** in average song duration for number-one hits after 1968 compared to the preceding 45 years. While early hits were constrained by the physical limits of 78-rpm records, modern hits saw a peak in duration before the recent streaming-era "short-song" trend began to emerge.

---

## How to Run
1. Clone this repository.
2. Ensure you have `pandas` and `matplotlib` installed: `pip install pandas matplotlib`.
3. Open `top-songs-project.ipynb` in your preferred editor.
4. Upload `top-song-durations.csv` when prompted.

---

##  Recruiter Quick-View
* **Problem-Solving:** Addressed data type constraints to enable time-series analysis.
* **Analytical Thinking:** Segmented 100 years of data to identify distinct historical trends.
* **Communication:** Clearly documented findings through integrated markdown and visual storytelling.

---
*Created as part of the Cisco Data Science Projects collection.*
