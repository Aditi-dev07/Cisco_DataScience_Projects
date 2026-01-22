## Thermodynamics of Coffee: Cup Material and Lid Impact

## 📌 Overview
Does the type of cup you use really keep your coffee hot for longer? This project investigates the cooling rates of coffee across three different scenarios: an insulated metal mug with a lid, an insulated mug without a lid, and a standard ceramic mug. By analyzing temperature decay over time, we quantify the effectiveness of insulation and the crucial role of lids in heat retention.

## 📂 Dataset
* **`hot-coffee.csv`**: Contains time-series temperature data (in Fahrenheit) recorded every 5 minutes.
* **Scenarios:**
    * `insulated with lid`: Insulated metal mug with a closed top.
    * `insulated`: Insulated metal mug open to the air.
    * `ceramic`: Standard ceramic mug without a lid.
* **Ambient Temperature:** Constant at 67°F.

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`

## 🚀 Visualization & Analysis
1.  **Multi-Series Line Plot:**
    * Plotted temperature vs. time for all three cup types to visualize cooling curves.
    * Integrated a horizontal reference line for the **Ambient Air Temperature (67°F)** to show the cooling floor.
2.  **Advanced Formatting:**
    * Applied a clean, "minimalist" aesthetic by removing all box spines (top, right, left, bottom).
    * Used faded horizontal grid lines to improve readability without cluttering the data.
3.  **Direct Annotation:**
    * Utilized a custom `add_end_labels` function to label each cooling curve directly at its endpoint, eliminating the need for a distracting legend and improving clarity for the viewer.

## 📊 Key Findings
* **The "Lid" Effect:** The insulated mug with a lid outperformed all other options by a massive margin, losing heat much slower than the open insulated mug.
* **Material vs. Evaporation:** While insulation helps, significant heat is lost through evaporation. An open insulated mug cools down significantly faster than one with a lid, though it still outperforms ceramic.
* **Ceramic Limitations:** The ceramic mug showed the fastest cooling rate, approaching ambient temperature the quickest due to high thermal conductivity and surface evaporation.

## 🏁 Conclusion
The project highlights that while insulation material is important, the use of a lid is the most significant factor in maintaining beverage temperature. This data-driven visualization provides a clear proof of concept for thermodynamics in everyday life.
