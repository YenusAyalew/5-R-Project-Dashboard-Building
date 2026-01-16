# My 5th R Project – Dashboard Building and Communication

**Author:** Yenus Ibrahim Ayalew  
**GitHub:** [@YenusAyalew](https://github.com/YenusAyalew)

This is **my 5th R project**, focused on building **interactive dashboards** using real-world data on wind turbines in Canada. The main goal of this project is to explore **data visualization, dashboard design, and interactive communication** using R’s `flexdashboard`, `plotly`, `DT`, and `leaflet` packages.

## Project Overview

For this project, I worked with data from the **Canadian Wind Turbine Database (2024)**, which includes information about turbine projects across all provinces, such as project name, total capacity, number of turbines, model, manufacturer, commissioning year, and geographical coordinates.  

The aim was to create a dashboard that presents the data clearly and allows users to interact with it to explore insights about wind energy projects.

## Key Features and Work Done

1. **Interactive Table**
   - Shows the **top 50 and bottom 50 wind turbine projects** based on energy production capacity.
   - Built with the `DT` package for sorting, paging, and searching.

2. **Interactive Plots**
   - Created using `ggplot2` and `plotly`:
     - **Total Turbines by Province:** shows which provinces have the largest number of turbines.  
     - **Number of Turbines Commissioned by Year:** visualizes the trend of turbine installations over time.
   - Users can hover over the plots for exact numbers and province/year details.

3. **Interactive Map**
   - Focused on **Saskatchewan turbines**, built with `leaflet`.
   - Features include:
     - Red markers with a **bolt icon** for turbines.
     - Popups showing turbine **identifier, capacity, model, manufacturer, and commissioning year**.
     - Hover labels for project names.

4. **Dashboard Layout**
   - The table, plots, and map are arranged in a **flexdashboard** with three columns for easy navigation and comparison.
   - Follows **good design principles**: clarity, interactivity, and usability.

## Learning Outcome

Through this project, I improved my skills in:

- **Data cleaning and transformation** using `dplyr` and `tidyverse`.
- **Interactive visualization** with `plotly` and `leaflet`.
- **Dashboard design**, including layout, color usage, and interactivity.
- Communicating complex data in a simple and engaging way.

This project is a meaningful step in advancing my **R programming and data communication skills**, while practicing how to present real-world data to both technical and non-technical audiences.
