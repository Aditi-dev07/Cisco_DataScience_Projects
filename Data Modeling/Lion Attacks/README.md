
## Influence of Moonlight on Lion Attacks

## 📌 Overview
Humanity has a historical fear of the dark due to nocturnal predators. This project investigates the relationship between the lunar cycle—specifically evening moonlight brightness—and the frequency of lion attacks on humans. The goal is to quantify how much nocturnal hunting activity is inhibited by natural light.

## 📂 Dataset
* **`lion-attacks-lunar-cycle.csv`**: Contains the number of lion attacks recorded for each day of the lunar cycle.
* **Feature - `evening_moonlight`**: A variable ranging from 0 (total darkness between 6pm-10pm) to 1 (maximum brightness), accounting for moon phase and visibility duration.

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`, `scikit-learn`
* **Modeling Tools:** Custom `LinearModel` class for regression analysis.

## 🚀 Data Modeling & Analysis
1.  **Exploratory Data Analysis (EDA):** Created a scatter plot of `evening_moonlight` vs `attacks` to observe trends.
2.  **Linear Regression:**
    * Fitted a linear model to describe the relationship: $y = mx + b$.
    * Calculated the **Slope ($m$)** and **Intercept ($b$)** to understand the rate of change.
3.  **Visualization:** Overlaid the best-fit line on the scatter plot to visualize the negative correlation.
4.  **Statistical Calculation:** Calculated the percentage decrease in attacks as moonlight transitions from a New Moon (0) to a Full Moon (1).

## 📊 Key Findings
* **Correlation:** There is a strong negative correlation between moonlight and lion attacks.
* **Slope:** The negative slope confirms that as the moon gets brighter, the number of attacks significantly decreases.
* **Impact:** Lion attacks decrease by approximately **76.48%** when evening moonlight increases from 0 to 1.

## 🏁 Conclusion
The model proves that lions are significantly more successful or active hunters during dark nights. This data modeling project helps illustrate how environmental factors directly impact predator-prey dynamics (including human safety).
