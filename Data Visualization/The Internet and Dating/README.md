## The Internet and Dating: How the Digital Age Changed Love

## 📌 Overview
From the founding of Cisco at Stanford to the modern era of dating apps, technology has fundamentally changed how human connections are formed. This project visualizes the shifting landscape of romantic relationships from the 1960s to the 2010s. We analyze the decline of traditional meeting methods—like meeting through family or neighbors—and the meteoric rise of online dating.

## 📂 Dataset
* **`how-couples-met.csv`**: Contains survey data across several decades.
* **Categories:** Meeting at college, at work, through friends, through family, at restaurants, through neighbors, and online.

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`

## 🚀 Visualization & Analysis
1.  **Time Series Analysis:**
    * Transformed decade-based data into a multi-line graph to track the evolution of seven distinct social meeting methods.
2.  **Visual Storytelling & Emphasis:**
    * Used color theory and line weight to highlight the primary "story": the explosive growth of **Online Dating** (from 3% in the 90s to 42% in the 2010s).
    * Applied a high-contrast red (`C3`) with a thicker line for the "online" category while dimming background data with reduced alpha (transparency).
3.  **Advanced Layout (Pro Tips):**
    * **Direct Labeling:** Removed the legend entirely to reduce cognitive load. Used a custom `add_end_labels` function to place text directly at the end of each line.
    * **Clean Design:** Removed chart spines and unnecessary ticks to focus the viewer's attention on the data trends.
4.  **Decade Comparison:**
    * Created side-by-side horizontal bar plots to compare specific decades (e.g., the 1960s vs. the 2010s) to highlight the total disappearance of some social norms.

## 📊 Key Findings
* **The Online Takeover:** By the 2010s, online dating became the #1 way couples meet, surpassing all other methods combined.
* **The Decline of the "Vouch":** Meeting through family members saw the most significant decline, dropping to just 10% by the 2010s.
* **Resilient Methods:** Meeting at restaurants/bars and through friends remain relatively stable compared to more localized methods like "neighbors."

## 🏁 Conclusion
The project successfully maps a major sociological shift. By using strategic emphasis and professional labeling techniques, the visualization clearly communicates how the internet has disrupted one of the most fundamental human activities: finding a partner.
