# Task 4 - Geospatial Data Analysis

## Overview
This project analyzes sales data across different locations in the United States to understand regional business performance and identify potential areas for business expansion.

## Objectives
- Analyze sales and profit across US states.
- Visualize sales data using an interactive geographical map.
- Identify the top-performing states and cities.
- Find potential expansion areas for further investigation.

## Tools and Libraries
- Python
- Pandas
- Matplotlib
- Plotly
- Jupyter Notebook

## Dataset
**Sample Superstore Dataset**

The dataset contains sales transactions, customer locations, product information, sales amounts, and profit values.

## Work Completed
1. Loaded and explored the sales dataset.
2. Calculated total sales, profit, and order counts by state.
3. Created an interactive US state sales map.
4. Generated a chart showing the top 10 states by sales.
5. Analyzed sales performance by city.
6. Identified preliminary expansion candidates using order counts, sales per order, and profitability.

## Project Structure

```text
task4-geospatial-analysis/
├── data/
│   └── Sample - Superstore.csv
├── src/
│   └── task4.ipynb
├── output/
│   ├── sales_map.html
│   ├── top_states.png
│   ├── top_cities.csv
│   ├── expansion_candidates.csv
│   └── state_sales_analysis.csv
└── README.md
```

## How to Run
1. Install the required libraries:

   ```bash
   pip install pandas matplotlib plotly nbformat
   ```

2. Place `Sample - Superstore.csv` inside the `data` folder.
3. Open `src/task4.ipynb` in Jupyter Notebook or VS Code.
4. Update the dataset path in the notebook if necessary.
5. Run all cells from top to bottom.
6. Open `output/sales_map.html` in a web browser to explore the interactive map.

## Results
The analysis produces state-wise sales and profit reports, a top-states chart, city-level sales summaries, and an interactive map to help compare regional performance.

The expansion candidate report highlights locations that may deserve further investigation.

## Limitations
The dataset provides historical sales information but does not include existing store locations, competitor presence, or total market demand. Therefore, the suggested expansion candidates are preliminary and require additional research before making business decisions.

## Conclusion
This project uses data analysis and geographical visualization to explore regional sales performance and support data-driven business expansion decisions.
