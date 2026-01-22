## Blood Pressure and Age Relationship Analysis

## 📌 Overview
This project investigates the relationship between age and systolic blood pressure by comparing two distinct populations: 100 individuals from the U.S. (NHANES data) and 71 individuals from the Yanomami Tribe in the Amazon. The study aims to determine if blood pressure naturally increases with age or if environmental factors, such as sodium intake, play a significant role.

## 📂 Datasets
* **`blood-pressure-usa.csv`**: Contains age and three separate systolic blood pressure readings for 100 U.S. individuals.
* **`blood-pressure-yanomami.csv`**: Contains age and systolic blood pressure data for 71 individuals living in near-total isolation.

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`, `linear_model` (custom module)

## 🚀 Data Modeling & Analysis
1.  **Data Preprocessing:** * Calculated the average systolic blood pressure for U.S. participants from three separate readings to ensure data consistency.
2.  **Linear Regression Modeling:**
    * Developed a `LinearModel` to predict blood pressure based on age for both the U.S. and Yanomami datasets.
    * **U.S. Model Results:** Slope: ~0.74, R-squared: ~0.47.
    * **Yanomami Model Results:** Slope: ~0.09, R-squared: ~0.03.
3.  **Comparative Analysis:**
    * Visualized and compared best-fit lines to observe differences in how age impacts blood pressure across the two populations.

## 📊 Key Findings
* The U.S. data shows a much stronger positive correlation between age and blood pressure compared to the Yanomami data.
* Confounding variables identified for further study include diet (specifically sodium intake), physical activity, and genetic predispositions.

## 🏁 Conclusion
The significant difference in the relationship between age and blood pressure across these populations suggests that lifestyle factors, such as the high sodium intake in the U.S. (3,500 mg) versus the Yanomami tribe (<100 mg), may be primary drivers of age-related hypertension.
