# COVID-19 Data Analysis for Kenya, USA, and India

This project analyzes a COVID-19 dataset to explore and compare the trends of the pandemic in Kenya, the USA, and India. It visualizes key metrics like total cases, total deaths, new cases, and vaccination progress over time, and provides a global context of case numbers.

## Objectives

* Load and clean COVID-19 data using pandas.
* Filter data for Kenya, USA, and India.
* Visualize the progression of total cases and deaths over time for these countries.
* Compare the daily new cases between the selected countries.
* Calculate and visualize the death rate (total deaths / total cases).
* Analyze and visualize vaccination progress (if data is available).
* Optionally, visualize total cases globally using a choropleth map.
* Summarize key insights and reflections from the analysis.

## Tools and Libraries Used

* **pandas:** For data manipulation and analysis.
* **matplotlib:** For basic data visualization.
* **seaborn:** For enhanced and statistical data visualization.
* **plotly.express:** (Optional) For creating interactive choropleth maps.

## How to Run/View the Project

1.  Ensure you have Python installed on your system.
2.  Install the necessary libraries by running: `pip install pandas matplotlib seaborn plotly`
3.  Place the COVID-19 data CSV file (e.g., `covid_data.csv`) in the same directory as the Python script.
4.  Run the Python script (e.g., `python your_script_name.py`) in a Jupyter Notebook or a Python environment. The script will load the data, perform the analysis, and display the generated visualizations.
5.  The insights and reflections will be printed to the console or displayed within the Jupyter Notebook.

## Insights and Reflections

* The USA showed the highest overall number of COVID-19 cases among the three countries.
* India experienced a significant surge in new cases during a specific period.
* Vaccination rollout speed and coverage appeared to vary across the countries.
* The calculated death rate showed different trends in each country over time.
