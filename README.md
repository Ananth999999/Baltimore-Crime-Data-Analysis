# Baltimore Crime Rate Analysis (2017–2022)

This project performs an exploratory data analysis (EDA) of crime trends in Baltimore City using real-world data from [data.baltimorecity.gov](https://data.baltimorecity.gov). The main objective is to analyze how crime rates have changed over time and across neighborhoods.

---

##  Dataset

- **Source**: [Baltimore City Open Data Portal](https://data.baltimorecity.gov)
- **File used**: `Part_1_Crime_Data.csv`
- **Columns analyzed**: Crime Date & Time, Neighborhood, Total Incidents, Crime Type, etc.

---

##  Key Objectives

- Load and clean the dataset by removing null columns
- Extract year from crime timestamps
- Calculate total incidents in 2017 and 2022
- Measure percentage change in crime rates
- Visualize trends in major crime types: **HOMICIDE**, **SHOOTING**, **AGG. ASSAULT**

---

##  Visualizations

- Line chart showing crime trends from 2017 to 2022 for major crime types
- Grouped statistics by Neighborhood and Year

---

##  Tech Stack

- Python
- pandas
- matplotlib
- numpy
- Jupyter Notebook

---

##  How to Run This Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/baltimore-crime-analysis.git
   cd baltimore-crime-analysis
