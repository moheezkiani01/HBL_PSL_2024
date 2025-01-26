# PSL 2024 Data Analysis

## Author
Moheez Azam Kiani

## Project Description
This project focuses on analyzing data from the Pakistan Super League (PSL) 2024. The goal is to extract valuable insights into players' performances, team strategies, and match dynamics using Python for data processing and visualization. The analysis provides a comprehensive understanding of cricket statistics through various preprocessing and visualization techniques.

---

## Features

### Data Preprocessing
- Cleaning raw data by addressing missing values and duplicates.
- Renaming columns for improved clarity.
- Transforming data into a format suitable for analysis.

### Data Exploration
- Generating summary statistics, such as mean, median, maximum, and minimum values.
- Examining data structure, including data types, rows, columns, and missing values.

### Data Selection
- Selecting rows and columns by index, labels, or random sampling.
- Extracting specific values for focused analysis.

### Data Aggregation
- Calculating aggregated metrics like sums, averages, medians, and maximum values.
- Summarizing large datasets into concise information.

### Data Augmentation
- Creating new columns from existing data (e.g., Runs-per-over).

### Data Visualization
- Plotting statistical trends using:
  - Bar plots for runs frequency.
  - Horizontal bar charts for runs vs. strike rate.
  - Box plots for runs by batting position.
  - Line charts for runs vs. balls faced.
  - Violin plots for team performance distributions.

---

## Technology Stack

### Programming Language
- Python

### Libraries Used
- **pandas:** Data manipulation and analysis.
- **numpy:** Numerical computations.
- **matplotlib & seaborn:** Data visualization.

---

## Getting Started

### Prerequisites
1. Install Python (version 3.x).
2. Install required libraries using:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

### Dataset
- Ensure the dataset file `fact_batting_summary.csv` is available in the project directory.

### How to Run
1. Open the `psldataanalysis.ipynb` file in Jupyter Notebook or any compatible IDE.
2. Run the cells sequentially to reproduce the analysis and visualizations.

---

## Project Workflow

1. **Data Loading:** Import the dataset and preview its structure.
2. **Data Cleaning:** Handle missing values, remove duplicates, and rename columns.
3. **Data Exploration:** Generate statistical summaries and explore key metrics.
4. **Data Selection:** Focus on specific rows, columns, or aggregated data.
5. **Data Visualization:** Generate charts and graphs to present the findings.

---

## Example Visualizations

### Frequency of Runs Scored
- A bar plot showcasing how often specific run totals are scored by players.

### Top Scorers Analysis
- A horizontal bar chart highlighting the top 10 run-scorers along with their strike rates.

### Runs Distribution by Batting Position
- A box plot displaying the variation in runs scored across batting positions.

### Runs vs. Balls Faced
- A line graph illustrating the relationship between runs scored and balls faced.

### Team Performance Distribution
- A violin plot showing the distribution of runs-per-over for each team.

---

## Use Cases
- **Cricket Analysts:** Gain actionable insights into player and team performance.
- **Sports Enthusiasts:** Understand game dynamics through statistical analysis.
- **Data Science Learners:** Apply data preprocessing and visualization techniques in a real-world scenario.

---

## Acknowledgments
- **PSL 2024:** For providing the dataset.
- **Open-Source Libraries:** For enabling efficient data analysis and visualization.

---

## Future Enhancements
- Extend the analysis to include bowling performance metrics.
- Implement predictive modeling for match outcomes.
- Develop interactive dashboards for real-time data exploration.

---

Feel free to explore and contribute to this project!
