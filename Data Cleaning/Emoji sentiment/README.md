# 📊 Emoji Sentiment Analysis: Decoding Digital Emotions

This repository features a comprehensive data analysis of how emojis convey sentiment across 1.6 million tweets in 13 European languages. This project demonstrates end-to-end data science skills, including data cleaning, feature engineering, and behavioral analysis.

---

## 🎯 Project Overview

The goal of this project is to determine if popular emojis are truly associated with the sentiments we perceive them to have. By analyzing a dataset where 4% of 1.6 million tweets contained emojis, we quantify the "emotional weight" of digital symbols.

### ✨ Recruiter Highlights

* **Data Engineering:** Cleaned high-cardinality metadata and standardized raw datasets for analysis.
* **Feature Engineering:** Developed a custom `sentiment_score` to normalize emotional impact across different usage frequencies.
* **Statistical Analysis:** Evaluated the correlation between emoji placement (position in text) and its sentiment polarity.

---

## 🛠️ Tech Stack

* **Language:** Python 🐍
* **Library:** Pandas (Data Wrangling) 🐼
* **Environment:** Jupyter Notebook / Google Colab 📓

---

## 📈 Key Insights & Results

The analysis reveals fascinating patterns in how we use emojis to express feelings. Below is a summary of the findings:

| Metric | Result | Insight 💡 |
| --- | --- | --- |
| **Most Positive Emoji** | ❤️ (Heart) | Emojis with high positive ratios dominate digital praise. |
| **Avg. Position (Positive)** | 0.662 | Positive emojis appear earlier in the tweet. |
| **Avg. Position (Negative)** | 0.681 | Negative emojis are pushed further toward the end. |
| **Total Tweets Analyzed** | 1.6 Million | Provides high statistical significance for the results. |

### ❤️ Heart-Based Sentiment Breakdown

| Emoji Type | Sentiment Tilt | Status |
| --- | --- | --- |
| ❤️ Red Heart | Very Positive | ❤️❤️❤️❤️❤️ |
| 💔 Broken Heart | Negative | 🖤🖤🖤🖤🖤 |
| 💖 Sparkling Heart | High Positive | ❤️❤️❤️❤️🤍 |

---

## 🧠 What You Can Learn (Learner Friendly)

1. **Handling Ratios:** Learn how to convert raw counts (Pos/Neg/Neu) into a single probability score.
2. **Filtering for Quality:** Understand why we only analyze emojis with `occurrences > 500` to avoid statistical noise.
3. **Data Cleaning:** See how to transform messy column names (like `Image [twemoji]`) into clean, code-friendly formats.
---
## ⚙️ How to Run

1. Clone this repository.
2. Ensure you have `pandas` installed: `pip install pandas`.
3. Download `emoji-sentiment.csv` and place it in the project root.
4. Open `emoji-sentiment.ipynb` in Jupyter or VS Code and run all cells.

---
*Created as part of the Cisco Data Science Projects collection.*
