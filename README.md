![CrossCompute Log](https://crosscompute.com/images/CrossCompute-LogoBrand-Horizontal-20200420.svg)

# Hurricane Emergency Map

![image](https://user-images.githubusercontent.com/75760920/161057051-7e53135a-e18b-44ef-a83a-475047a55053.png)


## Introduction

This tool uses plotly to create choropleth maps displaying the average hurricane Saffir-Simpson Category and amount of deaths through the years 2000 - 2021 in the United States. By hovering over a specific state, the user can view the average Saffir-Simpson Category or amount of deaths as a number.

## Data Gathering

Data was obtained from the Atlantic Oceanographic and Meteorological Laboratories Hurricane Research Division. The division conducts scientific research into hurricanes and related tropical weather phenomena, using theoretical studies, computer models, and an annual field program employing NOAA hurricane research aircraft.

https://www.aoml.noaa.gov/hrd/hurdat/All_U.S._Hurricanes.html

## Data Visualization

Using the data obtained, the average Saffir-Simpson Category was calculated for each state and put into a Pandas dataframe. Plotly was then used in order to visualize the data by creating a choropleth map from it.

![image](https://user-images.githubusercontent.com/75760920/161058216-214a78a0-eb08-49c4-8a39-2690ee858353.png)

By hovering over a state, the user can find the average Saffir-Simpson category, state, and occurrence respectively.

## Biography

Rohan Sazad is a student at CUNY Queens College majoring in Computer Science. He has knowledge in C++ and Python.

Email: rsazad813@gmail.com

LinkedIn: https://www.linkedin.com/in/rohan-sazad-635293217/
