## Car Dimensions: A Look Through Time

## 📌 Overview
This project investigates whether car models have grown larger over generations. By comparing the dimensions (length, width, and height) of the earliest generations of 53 iconic car models with their latest counterparts, the analysis uncovers clear trends in automotive design and size evolution.

## 📂 Dataset
* **`car-dimensions.csv`**: Contains `length`, `width`, and `height` in millimeters for 53 different car models across two generations: `first` and `latest`.

## 🛠️ Tech Stack
* **Language:** Python (Jupyter Notebook)
* **Libraries:** `pandas`, `matplotlib`, `seaborn`

## 🚀 Visualization & Analysis
1.  **Paired Scatter Plots:**
    * Visualized the evolution of `length`, `width`, and `height` by plotting the first generation against the latest.
    * Used 45-degree reference logic: points above the diagonal indicate size growth over time.
2.  **Advanced Metric Calculation:**
    * Calculated **Car Footprint** ($Length \times Width$) to measure the ground area occupied by vehicles.
    * Calculated **Percentage Change** for all dimensions to quantify relative growth.
3.  **Comparative Bar Charts:**
    * Created horizontal bar plots to identify which car models have changed the most and least in terms of footprint and physical dimensions.
4.  **Annotated Data Exploration:**
    * Implemented custom labeling for data points to highlight specific brand models like the Volkswagen Golf, Mini Cooper, and others.

## 📊 Key Findings
* **Consistent Growth:** Almost all car models show a significant increase in footprint, with the latest generations being considerably larger than the originals.
* **Width and Length:** Length and width have seen the most consistent increases, while height changes vary more by vehicle class.
* **Top Outliers:** Identified specific models that have undergone radical "size inflation" compared to their compact origins.

## 🏁 Conclusion
The automotive industry shows a clear trend toward larger vehicles. This visualization project highlights how "compact" cars of the past often rival the "mid-size" cars of today, providing data-driven evidence for the phenomenon of car size growth.
