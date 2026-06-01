Project Overview

This project performs COVID-19 data analysis and visualization using Python. It loads a COVID-19 dataset, cleans the data, calculates statistics, and creates charts to understand the spread and impact of the pandemic.

The project uses:

Pandas for data handling NumPy for numerical operations Matplotlib for plotting graphs Seaborn for advanced visualizations Features Load and inspect COVID-19 dataset Clean missing and duplicate data Rename columns for easier access Generate descriptive statistics Analyze top affected countries Create: Bar Chart Pie Chart Scatter Plot Heatmap Trend Analysis Graph Technologies Used Python 3 Pandas NumPy Matplotlib Seaborn Dataset

The project uses:

covid_19_data.csv

The dataset should contain columns such as:

ObservationDate Country/Region Confirmed Deaths Recovered Active Installation

Install the required libraries using:

pip install pandas numpy matplotlib seaborn How to Run Place covid_19_data.csv in the same folder as the Python script. Run the Python file: python covid_analysis.py Project Workflow Step 1 — Import Libraries

Imports all required Python libraries.

Step 2 — Load Dataset

Reads the CSV dataset using Pandas.

Step 3 — Data Cleaning Renames columns Removes missing values Removes duplicate rows Converts date column into datetime format Step 4 — Descriptive Statistics

Displays:

Total confirmed cases Total deaths Total recovered cases Statistical summary Step 5 — Country Analysis

Shows the Top 10 affected countries using a bar chart.

Step 6 — Pie Chart

Displays distribution of:

Confirmed Deaths Recovered cases Step 7 — Scatter Plot

Shows relationship between:

Confirmed cases Death cases Step 8 — Heatmap

Displays correlation between:

Confirmed Deaths Recovered Active cases Step 9 — Trend Analysis

Shows COVID-19 confirmed case trends over time.

Step 10 — Conclusion

Prints successful completion message.

Output Visualizations

The program generates:

Bar Chart Pie Chart Scatter Plot Correlation Heatmap Line Graph Sample Output Total Confirmed Cases: XXXXX Total Deaths: XXXXX Total Recovered: XXXXX

Analysis Completed Successfully! Future Improvements Add real-time COVID-19 API data Build interactive dashboards Add prediction models using Machine Learning Create country-wise filters Conclusion

This project helps in understanding COVID-19 trends through data analysis and visualization techniques. It is useful for beginners learning:

Data Analysis Data Cleaning Data Visualization Python Libraries
