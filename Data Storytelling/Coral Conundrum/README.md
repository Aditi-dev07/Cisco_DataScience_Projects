## 🪸 ** Coral Conundrum**
### **Why Did Coral Reef Fish Disappear from Our Language Around 1998?**

---

### **🔍 Project Overview**
Coral reef fish are among the most colorful and biologically important species in the ocean, playing a critical role in maintaining reef health. Yet, around **1998**, the usage frequency of many coral reef fish names dropped sharply in English texts.

This project investigates a puzzling question:

> **Why did references to coral reef fish decline at the same time the world was paying more attention to the oceans?**

By combining **linguistic trends**, **environmental data**, and **global events**, the project explores whether ecological crises and societal shifts can influence how often we talk about nature.

---

### **🎯 Project Objectives**
- Identify temporal trends in word usage for coral reef fish species  
- Examine potential links between language trends and coral bleaching events  
- Explore broader environmental and societal explanations behind linguistic decline  

---

### **🗂️ Data Description**
#### **Primary Data**
- **Source:** Historical English word-frequency corpus  
- **Focus:** Coral reef fish species  
- **Format:** Time-series word-frequency data  

#### **Supporting Datasets**
- **Coral Bleaching Events (`bleaching-reefs.csv`)**
  - Covers 100 reef locations across 54 countries (1980–2016)
  - Severity classified as:
    - `M` (Moderate): 1–30% coral affected
    - `S` (Severe): >30% coral affected
- **Global Coral Cover (`global-coral-cover.csv`)**
  - Yearly average percentage of live coral coverage
- **SCUBA Certifications (`new-scuba-certifications.csv`)**
  - Annual number of new SCUBA certifications worldwide

---

### **🔧 Data Preprocessing**
- Aggregated bleaching events by year using group-by operations
- Segmented bleaching data by severity level
- Aligned environmental datasets with word-frequency timelines
- Standardized time scales for comparative analysis

---

### **🔬 Methodology**
This project adopts an **exploratory, hypothesis-driven approach** rather than predictive modeling.

#### **Analytical Techniques**
- Time-series analysis of coral reef fish word usage
- Event-based aggregation of coral bleaching occurrences
- Comparative visualization across environmental indicators
- Custom plotting functions to maintain consistent visual design

#### **Rationale**
Environmental phenomena are often complex and interconnected. Visual exploration allows patterns and correlations to surface before drawing conclusions.

---

### **📊 Visualizations & Graphical Analysis**
The analysis includes:
- Line plots showing coral reef fish word-frequency trends
- Bar charts illustrating:
  - Total bleaching events per year
  - Severe bleaching events by year
- Visual alignment of environmental stressors with linguistic changes
---
### 🧰 Skills & Tools Demonstrated
- Python (Matplotlib)
- Time-series data analysis
- Data visualization and storytelling
- Reusable function design
- Insight-driven interpretation of historical data
