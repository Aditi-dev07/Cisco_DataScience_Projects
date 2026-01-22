## Comparative Analysis of Global Banknote Dimensions

## 📌 Overview
This project explores the physical dimensions of banknotes from 42 different currencies across all 22 UN-defined subregions. The analysis focuses on the trade-offs in currency design: uniform dimensions (for durability and machine compatibility) versus varied dimensions (to aid the visually impaired).

## 📂 Dataset
* **`banknote-dimensions.csv`**: Contains `length` and `width` measurements in millimeters for various denominations across 42 global currencies.

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`

## 🚀 Visualization & Analysis
1.  **Paired Scatter Plots:** * Created visualizations comparing the **Minimum vs. Maximum Length** and **Minimum vs. Maximum Width** for each currency.
    * This helps identify which currencies maintain consistent sizes and which have high variance between denominations.
2.  **Annotated Data Storytelling:**
    * Developed a custom `add_labels` helper function to programmatically label data points on scatter plots, highlighting specific outliers and clusters.
3.  **Consistency Statistics:**
    * Analyzed how many currencies maintain uniform length, uniform width, both, or neither across their denominations.

## 📊 Key Findings
* **Uniformity:** A significant percentage of currencies maintain consistent width while varying length (common in Euro and British Pound systems).
* **Dimensional Extremes:** Identified currencies with the largest overall notes and those with the most dramatic size differences between their smallest and largest denominations.
* **Global Trends:** Most modern currencies strike a balance between machine processing needs (uniform width) and accessibility (variable length).

## 🏁 Conclusion
The visualization successfully maps global currency design strategies, illustrating how different nations prioritize automation versus accessibility through the physical scaling of their banknotes.
