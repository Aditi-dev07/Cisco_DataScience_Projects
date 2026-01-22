##  E-Bike Stopping Distances Modeling

## 📌 Overview
This project explores the physics-based relationship between the speed of an electric bicycle and its stopping distance. The goal is to determine whether a linear or quadratic mathematical model best describes the distance an e-bike skids before coming to a complete stop on a gravel road.

## 📂 Dataset
* **`ebike-stopping-distances.csv`**: Contains experimental data points recording the speed of the e-bike (km/h) and the resulting stopping distance (m) after applying both front and rear brakes.
* **Key Range:** Speeds up to 36.3 km/h with stopping distances reaching approximately 14.2 meters.

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`, `scikit-learn` (LinearRegression)
* **Modeling Tools:** Custom `LinearModel` class and quadratic transformation logic.

## 🚀 Data Modeling Approach
1.  **Exploratory Data Analysis (EDA):** Visualized the data using scatter plots to identify the trend between speed and distance.
2.  **Linear Regression:** * Fitted a straight-line model: $y = mx + b$.
    * Identified a "sanity check" failure: the linear model predicted a negative stopping distance at zero speed.
3.  **Quadratic Modeling:**
    * Implemented a quadratic model to better reflect the kinetic energy physics ($E_k = \frac{1}{2}mv^2$), where stopping distance is expected to be proportional to the square of the speed.
4.  **Model Comparison:** Evaluated models using the Coefficient of Determination ($R^2$).

## 📊 Key Findings
* **Linear Model:** Achieved an $R^2$ of 0.925. While strong, it failed to accurately represent the behavior at low speeds.
* **Quadratic Model:** Achieved a superior $R^2$ of 0.981.
* The quadratic model provides a much better fit, confirming that stopping distance increases quadratically as speed increases.

## 🏁 Conclusion
The study concludes that a quadratic model is the most accurate way to predict e-bike stopping distances. This aligns with physical laws indicating that as speed doubles, the energy required to stop (and thus the distance) quadruples.
