## Is Granola Healthy? Public vs. Expert Consensus

## 📌 Overview
What we consider "healthy" can often be a point of contention. This project visualizes the level of agreement (or disagreement) between the general public and nutrition experts across 40 different food items. By plotting paired survey data, we identify which foods have a health "consensus" and which are subject to "perception gaps."

## 📂 Datasets
* **`healthy-food-survey-public.csv`**: Survey responses from the general public.
* **`healthy-food-survey-experts.csv`**: Survey responses from nutrition experts.
* **Features:** Food item names and counts of 'yes', 'no', and 'no opinion' responses regarding healthiness.

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`

## 🚀 Visualization & Analysis
1.  **Data Normalization:** Converted raw survey counts into percentages to allow for direct comparison between public and expert opinions.
2.  **Paired-Data Scatter Plot:**
    * Plotted `Public (%)` vs. `Experts (%)` for each food item.
    * **Pro Tip 1: Equality Line:** Added a diagonal 1:1 line ($y=x$). Points on this line represent perfect agreement; points far from it represent a perception gap.
    * **Pro Tip 2: Identical Scales:** Ensured both axes range from 0 to 100 to prevent visual distortion of the data.
3.  **Data Storytelling:** Identified specific "outlier" foods where the public thinks it's healthy but experts disagree (e.g., granola, orange juice) and vice versa.

## 📊 Key Findings
* **Consensus Foods:** Items like apples (high agreement on healthy) and white bread (high agreement on unhealthy) cluster at the extremes of the equality line.
* **The Granola Gap:** Certain foods like granola and coconut oil show a significant "Public > Expert" gap, where marketing may influence public perception more than clinical data.
* **Expert Disagreement:** Foods in the center of the plot show that even within groups, there is no clear consensus on healthiness.

## 🏁 Conclusion
The project demonstrates that health perception is not just about nutrition—it's about communication. The resulting visualization serves as a powerful tool to highlight where public health education might need to bridge the gap with scientific consensus.
