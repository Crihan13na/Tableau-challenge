# Citi Bike Analytics and Insights

A data visualization project that helps publicize and share information about the New York Citi Bike program from March 2019 to March 2020. Built using Tableau.

## Overview

The New York Citi Bike program is the largest bike sharing program in the United States. Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the Citi Bike webpage. For more information about the program, see <https://en.wikipedia.org/wiki/Citi_Bike>.

## About the Tableau story board

Link to Tableau story board: <https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Story1>


The story board analyzes and visualizes Citi bike data from January 2019 to January 2020.

## Analysis and Insights for the Data

An analysis on the phenomenons uncovered by the data is available within the Tableau story board. Each dashboard is accompanied by a short analysis.

### Tableau Dashboards

Each section of the story board includes a dashboard.

Here are links to each of the individual Tableau dashboards created for this project:

* [Most Used Bikes](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Dashboard6)
* [Start Station Popularity](Dashboard(https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Dashboard2)
* [End Station Popularity]    (Dashboard(https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Dashboard3)
* [Rider Demographics Dashboard](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Dashboard1)
* [Customers vs Subscribers](Dashboard(https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Dashboard5)
* [Peak Hours ](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Dashboard4)
### Visualizations

Each dashboard consists of a group of related visualizations.

Here are links to each of the individual Tableau visualizations created for this project:

* [Bike Trips By Gender](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet4)
* [Bike Trips By Rider Type](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet7)
* [Most Popular Start Stations](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet2)
* [Avg Trip Duration by Age and Gender](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet5)
* [Most Popular End Stations](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet9)
* [Most Used Bikes (due for repair or inspection](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet14)(https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet15)
* [Map - Most Popular Start Stations](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet3)
* [Map - Most Popular End Stations](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet10)
* [Bike Trips by Month and Gender](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet6)
* [Bike Trips by Month and Rider Type](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet13)
* [Peak Summer Hours (June 2019 - August 2019](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet12)
* [Peak Winter Hours (December 2019 - February 2020)](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet11)
* [End Station Popularity Over Time](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet8)
* [Start Station Popularity Over Time](https://public.tableau.com/profile/anastasia.b.#!/vizhome/NewYorkCitiBikeAnalysis/Sheet1)

## About the data

The data used to build the Tableau visualizations comes from the Citi Bike webpage and is available from the webpage as csv files. For more information about the data used to build the visualizations, see <https://www.citibikenyc.com/system-data>.

The csv files are stored in a zip file inside the [Resources](./Resources) folder of this repository.

## Cleaning the data

To clean the data, a python package called pandas was used.

The steps to clean the data are captured and documented in the [citi_bike_data_cleaning.ipynb](./citi_bike_data_cleaning.ipynb) jupyter notebook file in this repository.

To get the final csv file that was used in Tableau to create the visualizations, run through all of the cells in the jupyter notebook file.
