## World Population Trends and Projections

## 📌 Overview
This project visualizes the global shift in human population across four major regions: Africa, Asia, Europe, and the Americas. By analyzing historical data from 1800 and UN-supported projections through 2100, we explore how the "center of gravity" of the world's population is moving, specifically highlighting the dramatic growth in Africa and Asia.

## 📂 Dataset
* **`world-indicators.csv`**: Sourced from Gapminder.org.
* **Scope:** 1800 to 2100 (projected).
* **Indicators:** Regional population, life expectancy, child mortality, fertility rates, and income per person.

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`

## 🚀 Visualization & Analysis
1.  **Horizontal Bar Charts (2000 vs. 2100):**
    * Created side-by-side comparisons of population distribution using "blocks" (1 block = 1 billion people).
    * Highlighted the projected increase from 6 billion (2000) to 11 billion (2100) people globally.
2.  **Long-Term Line Plots (1800–2100):**
    * Pivoted the dataset to plot regional population growth over three centuries.
    * Applied "Pro Tips" for clean design: removed unnecessary spines, added faded grid lines, and implemented a custom `add_end_labels` function to label lines directly at their endpoints for better readability.
3.  **Data Transformation:**
    * Cleaned data to isolate regions from global aggregates.
    * Converted raw population counts into billions for simplified visualization.

## 📊 Key Findings
* **The Rise of Asia and Africa:** Asia remains the most populous region, but Africa shows the steepest growth curve toward 2100.
* **Regional Stability:** Europe and the Americas show significant stabilization in population growth compared to the exponential trends in other regions.
* **Visualization Efficacy:** Line charts with direct endpoint labels proved more effective than traditional legends for tracking four distinct regional paths over 300 years.

## 🏁 Conclusion
The project successfully communicates the scale of global demographic shifts. Through effective data visualization, it highlights that the challenges and opportunities of the 21st century will increasingly be centered in Africa and Asia.
