## Correlation Between Brightness and Toxicity in Poison Dart Frogs

## 📌 Overview
This project examines the relationship between physical appearance and biological defense mechanisms in the poison dart frog species *Dendrobates pumilio*. Specifically, it investigates whether the brightness of a frog's skin (back vs. belly) serves as a reliable visual indicator (aposematic signal) of its toxicity levels to potential predators.

## 📂 Datasets
* **`frog-reflectance.csv`**: Contains average brightness measurements (0 to 1) for the back and belly of 10 different frog populations in Panama.
* **`frog-toxicity.csv`**: Provides toxicity scores (0 to 1) for 48 individual frogs across the same populations, measured via skin extract potency.

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`, `linear_model` (custom module)

## 🚀 Data Modeling Approach
1.  **Data Integration:** Calculated the average toxicity for each population ID (`pop_id`) and merged it with the reflectance data.
2.  **Comparative Modeling:** Built two distinct linear regression models:
    * **Model 1:** `toxicity` vs. `back_brightness`
    * **Model 2:** `toxicity` vs. `belly_brightness`
3.  **Statistical Analysis:** Compared the $R^2$ values (Goodness of Fit) to determine which body part more accurately signals toxicity.
4.  **Biological Interpretation:** Explored why certain evolutionary traits (like dorsal brightness) are more strongly correlated with survival mechanisms.

## 📊 Key Findings
* **Back Brightness:** Showed a strong correlation with toxicity ($R^2 \approx 0.607$).
* **Belly Brightness:** Showed a much weaker correlation ($R^2 \approx 0.184$).
* **Biological Logic:** Predators primarily see the frog's back (dorsal side). Therefore, evolution has favored the back as the primary canvas for "warning colors," making it a more honest indicator of danger than the belly, which is often hidden.

## 🏁 Conclusion
The project confirms that back brightness is a statistically significant predictor of toxicity in poison dart frogs. This supports the theory of aposematism, where animals develop highly visible signals to communicate their toxicity to the world, thereby increasing their chances of being avoided by predators.
