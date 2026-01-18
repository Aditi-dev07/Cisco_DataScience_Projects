# Animal Sleep Analysis

## Introduction
Different animal species exhibit vastly different sleep patterns. For example, elephants may sleep only 3–4 hours per day, while bats can sleep up to 20 hours. This project explores the relationship between **sleep duration**, **body mass**, and **diet** across animal species using exploratory data analysis and linear regression.

The analysis investigates questions such as:
- Is there a relationship between an animal’s body mass and its average sleep time?
- Does diet (carnivore, omnivore, herbivore) correlate with sleep duration?
- Does transforming body mass using a logarithmic scale improve linear modeling?

## Table of Contents
- Project Structure
- Dataset
- Installation
- Usage
- Features
- Dependencies
- Examples
- Project Ideas
- Troubleshooting

## Project Structure
```
.
├── animal-sleep.ipynb
├── animal-sleep.csv
├── linear_model.py
└── README.md
```

## Dataset
The dataset `animal-sleep.csv` contains average values for multiple animal species, including:
- **sleep** – average hours of sleep per day  
- **mass** – average body mass in kilograms  
- **diet** – dietary classification  

Body mass is right-skewed, so a log10 transformation is used for modeling.

## Installation
```bash
git clone https://github.com/your-username/animal-sleep.git
cd animal-sleep
pip install pandas matplotlib
```

## Usage
Run the Jupyter notebook:
```bash
animal-sleep.ipynb
```

## Features
- Exploratory data analysis
- Data visualization
- Log-transformed linear regression
- Custom linear model implementation

## Dependencies
- Python 3.x
- pandas
- matplotlib
- Jupyter Notebook

## Examples
The notebook demonstrates scatter plots, regression lines, and comparisons across diet categories.

## Project Ideas
- Build separate models by diet
- Compare linear vs non-linear models
- Add statistical significance testing

## Troubleshooting
- Ensure CSV and Python files are in the same directory
- Reinstall dependencies if imports fail
