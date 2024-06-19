<h2>COVID-19 Lockdown Impact Analysis</h2>
This project analyzes the impact of national lockdowns on COVID-19 transmission rates and active cases in Italy and Germany using publicly available data. We visualize trends in confirmed cases, infection rates, and active cases before and after lockdowns in these countries.

<h4>Dataset</h4>
The dataset, sourced from this URL, includes:

<li>Date: The record date.</li>
<li>Country: The country of the record.</li>
<li>Confirmed: Cumulative confirmed COVID-19 cases.</li>
<li>Recovered: Cumulative recovered COVID-19 cases.</li>
<li>Deaths: Cumulative deaths due to COVID-19.</li>
<h4>Steps and Analysis</h4>

1. Loading the Dataset
Import libraries: pandas, numpy, plotly.express, and matplotlib.pyplot.
Load and display the dataset.

2. Preprocessing
Filter out records with zero confirmed cases.
Check the DataFrame shape.

3. Global Visualizations
Use choropleth maps to visualize global confirmed cases and deaths.

4. Italy Lockdown Analysis
Define Italy's lockdown period (March 9, 2020, to April 9, 2020).
Filter data for Italy.
Calculate daily infection rates.
Plot infection rates before and after lockdown.
Calculate and visualize active cases.

5. Germany Lockdown Analysis
Define Germany's lockdown period (March 23, 2020, to April 23, 2020).
Filter data for Germany.
Select relevant columns.
Calculate and visualize daily infection rates.
Scale and plot confirmed, recovered, and death cases.

<h4>Results</h4>
The visualizations show trends in COVID-19 transmission and active cases before and after the lockdowns in Italy and Germany, highlighting the effectiveness of lockdown measures.

<h4>Conclusion</h4>
This project provides insights into the effectiveness of national lockdowns in controlling COVID-19 spread, demonstrating the importance of timely interventions in public health.
