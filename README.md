# UFC-Fight-Finishes-Analysis
#### **Analyzing UFC Fight Finishes (1994–2023)**

## Overview
This project examines **UFC fight finishes from 1994 to 2023**, focusing on trends in **knockouts (KO/TKO) and submissions**. The analysis explores:
- **Most and least common finishing methods** in UFC history.
- **How finishing trends vary by weight class** (e.g., Heavyweight vs. Flyweight).
- **How fight finishes have evolved over time** (e.g., changes in submission variety).

## Dataset
- The data was sourced from **[Kaggle]**(https://www.kaggle.com/datasets/remypereira/mma-dataset-2023-ufc/data)
- The dataset was **cleaned, merged, and standardized** to ensure accurate analysis.

## Methods & Tools
- **Data Cleaning & Merging**: Python, Pandas, **Excel**
- **Visualization**: Tableau
- **Data Analysis**: Aggregation of finishes by year, weight class, and type


## Repository Structure

📂 UFC-Fight-Finishes-Analysis/
│── **README.md**   
│── **finish_sum_by_weight.ipynb**
│── **finishing_trends_over_time.ipynb**
│── 📂 data/  
│   ├── ufc_fight_data.csv
│   ├── clean_df_fighters.csv
│   ├── ufc_event_data.csv
│   ├── ufc_fight_data copy.csv
│   ├── ufc_fight_stat_data.csv
│   ├── full_writeup.pdf
│── 📂 visuals/
│   ├── main_dashboard.twbx


## How to View the Project
  1. Download main_dashboard.twbx from this repository.
  2. Open it using Tableau Desktop (any version that supports .twbx files).
  3. Interact with the visualizations to explore UFC fight finish trends!

## Limitations & Future Work
- **Data Mapping Issue:** Some fight finishes were categorized correctly in weight-class analysis but left uncategorized in the trends-over-time visualization. This does not impact key insights but could be improved in future iterations.
- **More Granular Data:** Expanding the dataset with fight-by-fight details could provide deeper insights into how finish rates evolve based on fighter styles.
- **Machine Learning Predictions:** Future work could involve predicting fight outcomes based on historical data.





  


