# World CO2 Emission Dashboard using Panel

Interactive visualization dashboard in Python with Panel. This dashboard provides interactive visualizations and data analysis for exploring global carbon dioxide (CO2) emissions over time, focusing on various aspects such as emissions by continent, CO2 sources, and their correlation with GDP per capita.

The dataset used in this project was gotten from `Our World In Data` which is a trusted Data source with real world raw data. The link to the github site where the original dataset is [HERE] (https://github.com/owid/co2-data/blob/master/owid-co2-data.csv)

## Introduction

This dashboard provides an interactive environment for exploring and analyzing CO2 emissions data from 1750 to the present. It uses Python libraries like Pandas, NumPy, Panel, and HoloViews for data processing, visualization, and interactivity. The dashboard presents data-driven insights into global CO2 emissions trends and their relationships with various factors.

## Installation
To run this dashboard, you'll need Python and the following libraries installed:

- `pandas`
- `numpy`
- `panel`
- `hvplot`

You can install these libraries using the following command:
``` pip install pandas numpy panel hvplot ```


If you want to see all the dependencies for this project, please see requirements.txt file.

To serve the dashboard locally, use the command:

``` panel serve Interactive_dashboard.ipynb ```

## Usage
This dashboard is designed to help users explore CO2 emissions data interactively. It offers visualizations and analysis across different aspects of emissions and related factors. Users can adjust parameters such as the year, data axis, and more to observe changes in CO2 emissions and their connections.

## Dashboard Components
### Year Slider
The year slider allows you to select the year for which you want to analyze CO2 emissions data. It ranges from 1750 to 2021, with a step size of 5 years.

### Y Axis Radio Buttons
These radio buttons enable you to choose the data axis for the y-axis of the visualizations. You can choose between 'co2' and 'co2_per_capita'.

### CO2 Emissions by Continent
This section provides a line plot illustrating CO2 emissions by continent over time. It visualizes the average CO2 emissions for each continent in the selected year.

### CO2 vs GDP Scatterplot
This scatterplot demonstrates the relationship between CO2 emissions and GDP per capita for various countries in the selected year. Each point represents a country, and the scatterplot helps visualize potential correlations between CO2 emissions and economic development.

### CO2 Source by Continent
This bar plot showcases the distribution of CO2 emissions from different sources (coal, oil, and gas) across continents (excluding 'World') in the selected year.

## Dashboard Template
The dashboard layout includes:
- A title introducing the dashboard's purpose.
- A sidebar with a brief description, a climate-related image, and the year slider.
- Main sections containing visualizations and analysis components.

## How to Run
- Make sure you have installed the required libraries (see requirements.txt and installation).
- Run the script. The dashboard will generate and launch in your browser.

## Contributing
Contributions to enhance this dashboard are welcome! You can contribute by adding new features, improving visualizations, optimizing code, or fixing issues. Please fork this repository, make your changes, and submit a pull request.


<img width="960" alt="image" src="https://user-images.githubusercontent.com/69481921/227059754-a5ede781-2648-4e71-ab6d-cdfd3455eee6.png">
