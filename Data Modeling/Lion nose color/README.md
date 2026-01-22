## Lion Age Estimation via Nose Coloration

## 📌 Overview
Can we estimate a lion's age just by looking at its nose? This project explores the biological phenomenon where lions are born with pink noses that gradually develop black freckles and darken as they age. By analyzing data from the Serengeti, we build a model to predict age based on the proportion of black pigment on a lion's nose.

## 📂 Dataset
* **`lion-nose-color.csv`**: Contains data for 91 lions from the Serengeti whose exact ages have been monitored since birth.
* **Features:**
    * `age`: The known age of the lion in years.
    * `proportion_black`: The percentage of the lion's nose that is black (ranging from 0 to 1).

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`
* **Modeling Tools:** Custom `LinearModel` class for performing simple linear regression.

## 🚀 Data Modeling Approach
1.  **Exploratory Data Analysis (EDA):** Visualized the relationship between `proportion_black` and `age` using a scatter plot.
2.  **Linear Regression Modeling:**
    * Independent Variable ($x$): Proportion of black on the nose.
    * Dependent Variable ($y$): Age of the lion.
    * Fitted a line of best fit to quantify the relationship.
3.  **Prediction:** Used the model to estimate the age of a lion when its nose is 50% black.
4.  **Extrapolation Analysis:** Investigated the validity of predicting age at 100% nose darkness.

## 📊 Key Findings
* **Correlation:** There is a clear positive linear relationship between age and nose darkness.
* **Model Utility:** The model effectively predicts age within the observed range of the dataset.
* **Limitations:** Predicting the age for 100% black noses is considered **unreliable extrapolation**. Biological factors (genetics, health, environment) mean the darkening process may plateau or vary significantly in older lions.

## 🏁 Conclusion
While nose coloration is a strong indicator of age in younger lions, it serves as a descriptive trend rather than a precise biological clock for older lions. This project highlights the difference between interpolation within a dataset and risky extrapolation beyond it.
