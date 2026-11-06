## Summary

**Data:** Titanic passengers from Kaggle, 891 rows and 12 columns.

**Cleaning:** I filled 177 blank ages with the median (28) and 2 blank ports with the most common port (S).
I left Cabin alone because 77% of it was empty.

**Findings:**
1. Women survived at 74% and men at 19%.
2. Survival fell with ticket class: 63% in class 1 and 24% in class 3.
3. Children under 12 survived at 57%, adults at 39%.

**Limitation:** Filling the blank ages created an artificial spike near 28 in the histogram.

# IPL Data Analysis Using Python 🏏

## About the Project
This project explores IPL cricket data using Python to analyze player performances and season-wise batting trends.

## Objectives
- Identify the top 10 IPL run-scoring batters.
- Analyze total runs across IPL seasons.
- Understand batting performance trends.
- Present insights using data visualization.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset
IPL dataset containing match and batting information.

## Key Findings
- V Kohli leads the dataset with 9,346 runs.
- RG Sharma ranks second with 7,331 runs.
- 2026 has the highest season total in this dataset, with 26,156 batter runs.
- Recent seasons show higher aggregate batting runs.

## Visualizations
1. Top 10 IPL Run Scorers – Bar Chart
2. Total IPL Runs Across Seasons – Line Chart

## Project Structure

```text
Pandas/
│
├── archive/
│   └── IPL.csv
│
├── IPL_Analysis.ipynb
├── README.md
└── project.ipynb
```

## How to Run
1. Clone this repository.
2. Install the required libraries:

```bash
pip install pandas matplotlib jupyter
```

3. Open Jupyter Notebook.
4. Open `IPL_Analysis.ipynb`.
5. Run the notebook cells.

## Conclusion
This project demonstrates how Python can be used for data cleaning, analysis, aggregation and visualization to discover useful insights from cricket data.

## Author
Created as a Python Data Analysis learning project.
