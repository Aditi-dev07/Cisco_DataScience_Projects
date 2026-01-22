# ☕ Data-Driven Strategy: Launching a Plant-Based Coffee Shop

## Project Overview

As specialty coffee shops grow in popularity, understanding the nuances of consumer behavior is vital for market entry. This project analyzes a comprehensive survey of **~1,000 coffee enthusiasts** to provide data-driven recommendations for a new specialty coffee shop.

**The Business Problem:** A new shop plans to offer a strictly **plant-based** menu. This analysis identifies the optimal dairy alternatives and sweetener inventory to stock, while profiling the highest-consuming demographics to guide marketing efforts.

---

## Technical Workflow

*This section outlines the end-to-end data pipeline used to move from raw survey responses to actionable business strategy.*

### 1. Data Cleaning & Integrity

* **High-Dimensional Slicing:** The original dataset contained **113 columns**; the analysis focused on extracting specific subsets related to demographics, dairy preferences, and sweetener choices.
* **Missing Value Management:** Utilized `.dropna()` on target columns like age and daily consumption to ensure that missing data did not skew demographic averages.
* **Standardization:** Cleaned categorical survey responses to ensure consistency across the dataset.

### 2. Feature Engineering

* **Categorical Encoding:** To perform mathematical operations on consumption data, I mapped qualitative survey ranges (e.g., "Less than 1 cup") to specific numerical values (e.g., `0.5`).
* **Preference Aggregation:** Converted boolean-style survey columns into percentages by calculating the mean across the sample and scaling by 100.

### 3. Exploratory Data Analysis (EDA)

* **Demographic Profiling:** Grouped data by age range using `.groupby()` to calculate the average number of cups consumed per day by different cohorts.
* **Ranking & Sorting:** Implemented `.sort_values()` before plotting to create a visual hierarchy of consumer preferences, making insights immediately apparent to stakeholders.

---

## Key Insights & Results

*Actionable findings used to define the shop’s inventory and marketing roadmap.*

| Category | Finding | Business Impact |
| --- | --- | --- |
| **Top Sweetener** | **Granulated Sugar (63.9%)** | Primary inventory requirement. |
| **Secondary Sweeteners** | **Brown Sugar (26.5%) & Raw Sugar (24.5%)** | Essential for a "Specialty" menu. |
| **Target Demographic** | **Age 55-64 years old** | Highest consumption rate at **2.1 cups/day**. |
| **Emerging Markets** | **18-24 & 25-34** | Key cohorts for plant-based milk marketing. |

---

## How to Run

To replicate this analysis locally or in the cloud, follow these instructions:

1. **Environment Setup:** Ensure you have Python installed with the following libraries:
```bash
pip install pandas matplotlib

```


2. **Dataset Preparation:** Download `coffee-survey-results.csv` and place it in the same directory as the notebook.
3. **Run with Google Colab (Cloud):** * Click the **"Open in Colab"** badge at the top of the notebook.
* Uncomment the `files.upload()` cell to import your dataset directly into the session.


4. **Execute Analysis:**
Open the .ipynb files in Jupyter Notebook or VS Code.
Ensure the corresponding .csv files are in the same directory as the notebook.
Google Colab User? Use the provided files.upload() cells within the notebooks to import the data.

---

##  Visualizations

*(Placeholders for visualizations found in the notebook)*

> **[Graph Placeholder: Sweetener Preference Ranking]**
> *A horizontal bar chart showing the dominance of granulated sugar followed by brown and raw sugars.*

> **[Graph Placeholder: Consumption by Age Group]**
> *A visualization illustrating the peak consumption levels in middle-aged to senior demographics.*

---

**Author:** Aditi Verma

---

Created as part of the Cisco Data Science Projects collection.
