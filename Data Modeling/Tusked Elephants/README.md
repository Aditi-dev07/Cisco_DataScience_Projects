## Genetic Impact of Poaching on Elephant Tusk Size

## 📌 Overview
The illegal ivory trade in the 1970s and 80s devastated elephant populations, with poachers specifically targeting animals with the largest tusks. This project investigates the long-term evolutionary impact of this selective pressure. By comparing elephants born before the poaching crisis to those born after a period of recovery, we model how the relationship between body size and tusk length has shifted.

## 📂 Dataset
* **`male-elephant-tusk-size.csv`**: Contains data on young male elephants from East Africa.
* **Cohorts:**
    * **1966-1968 (Pre-poaching):** Baseline data from before severe ivory hunting.
    * **2005-2013 (Post-recovery):** Data from elephants born after the poaching period ended.
* **Features:** `shoulder_height` (cm) and `tusk_length` (cm).

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`, `scikit-learn`
* **Modeling Tools:** Custom `LinearModel` class for regression analysis.

## 🚀 Data Modeling Approach
1.  **Data Segmentation:** Split the dataset into `pre_poaching` and `post_recovery` groups to analyze them independently.
2.  **Comparative Analysis:** Calculated mean tusk lengths and identified potential age-related confounding factors (smaller elephants naturally have smaller tusks).
3.  **Bivariate Modeling:**
    * Plotted `shoulder_height` vs. `tusk_length` to observe shifts in physical proportions.
    * Created two linear regression models to quantify the change in tusk growth relative to body size.
4.  **Prediction:** Compared predicted tusk lengths for a standard elephant size (e.g., 400cm shoulder height) across both time periods.

## 📊 Key Findings
* **Mean Shift:** Average tusk lengths decreased significantly in the post-recovery population.
* **Proportional Change:** For any given shoulder height, pre-poaching elephants generally had much longer tusks than post-recovery elephants.
* **Quantitative Prediction:** An elephant with a 400cm shoulder height would have a predicted tusk length of **242.76 cm** pre-poaching, compared to only **139.08 cm** post-recovery.

## 🏁 Conclusion
The results provide strong evidence of "evolution in real-time." By selectively removing large-tusked individuals from the gene pool, poaching acted as an artificial selection pressure, leading to a population with genetically smaller tusks.
