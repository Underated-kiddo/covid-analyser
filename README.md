# COVID-19 Global Data Tracker

## Overview
This project is a Python-based data analysis and visualization tool for tracking and analyzing global COVID-19 data. It uses the `owid-covid-data.csv` dataset to generate insights and visualizations, such as trends in cases, deaths, and vaccinations.

## Features
- **Daily COVID-19 Cases Over Time**: Line chart showing daily new cases globally.
- **Top 10 Locations by Total Deaths**: Bar chart of the locations with the highest total deaths.
- **Top 10 Countries by Total Cases**: Bar chart of the countries with the highest total cases.
- **Time Trend Analysis for Selected Countries**: Line charts showing total cases and deaths over time for specific countries.
- **Vaccination Trends**: Line chart showing cumulative vaccinations for selected countries.
- **Correlation Heatmap**: Heatmap showing correlations between key COVID-19 metrics.
- **Vaccinated vs Unvaccinated Population**: Pie chart approximating the global vaccinated vs unvaccinated population.

## Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`

## Setup
1. Clone the repository or download the project files.
2. Ensure the `owid-covid-data.csv` file is in the project directory.
3. Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Run the `data_analyser.ipynb` notebook in Jupyter Notebook or any compatible environment.

## Outputs
All generated charts are saved in the `charts` directory:
- `daily_cases.png`: Daily new cases over time.
- `top10_deaths.png`: Top 10 locations by total deaths.
- `top10_cases.png`: Top 10 countries by total cases.
- `trend_US_India.png`: Time trends for the United States and India.
- `vaccination_trends.png`: Vaccination trends for selected countries.
- `correlation_heatmap.png`: Correlation heatmap of key metrics.
- `vaccinated_pie.png`: Pie chart of vaccinated vs unvaccinated population.

## Insights
- The United States and India have the highest total cases.
- Strong positive correlation exists between total cases and total deaths.
- Vaccination numbers have grown rapidly in major countries.
- The pie chart highlights the global vaccination gap.

## Notes
- Ensure the dataset is up-to-date for the most accurate analysis.
- Modify the `DATA_PATH` variable in the notebook if the dataset is located elsewhere.