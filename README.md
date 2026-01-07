# Project Title: Electric Vehicle Population Data Analysis

## 1. Project Overview
This project focuses on analyzing Electric Vehicle (EV) population data using Pandas for data cleaning and analysis, and Matplotlib and Seaborn for data visualization. The goal is to explore electric vehicle adoption trends, regional distribution patterns, and key factors influencing EV growth to support transportation planning and sustainability initiatives.

## 2. Tools Used
* **Pandas** - Data cleaning and manipulation
* **NumPy** - Numerical operations
* **Matplotlib** - Basic data visualization
* **Seaborn** - Advanced and statistical visualizations

## 3. Dataset
* **Source**: Washington State Department of Licensing (DOL)
* **Description**: The dataset contains structured information on Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) with the following key columns:
    * VIN (1-10)
    * County, City, State
    * Model Year
    * Make, Model
    * Electric Vehicle Type
    * Electric Range
    * Vehicle Location

## 4. Steps Followed
1. Imported the dataset using Pandas.
2. Cleaned the data by:
    * Handling missing values (e.g., filling 'Unknown' for missing locations).
    * Converting numeric columns to proper formats.
    * Standardizing categorical values.
3. Performed exploratory data analysis (EDA) using Pandas.
4. Created visualizations using Matplotlib and Seaborn, such as:
    * Bar charts for EV adoption trends over time.
    * Charts for vehicle type distribution (BEV vs. PHEV).
    * Analysis of electric range efficiency.
5. Interpreted the results to extract meaningful insights.

## 5. Key Insights
* Recent model years show a significant increase in registered electric vehicles.
* Battery Electric Vehicles (BEVs) are more prevalent than Plug-in Hybrids (PHEVs).
* Adoption varies by county, likely correlated with urban density and charging infrastructure.
* Newer vehicles generally provide higher electric range.
* Incentives and supportive policies have positively influenced adoption rates.

## 6. Visualizations
* Bar chart showing adoption trends by Model Year.
* Distribution plot comparing BEV vs. PHEV counts.
* Categorization of vehicles by electric range (Low, Medium, High).

## 7. Files Included
* `Electric_Vehicle_Population_Data.csv` - Raw dataset
* `Main_Project.ipynb` - Pandas analysis and visualizations
* `README.md` - Project description and usage instructions

## 8. How to Use
1. Open `Main_Project.ipynb` using Jupyter Notebook or JupyterLab.
2. Run the notebook cells step by step to view data cleaning, analysis, and visualizations.
3. Modify the code to explore additional insights if needed.

## 9. Conclusion
This project demonstrates how Python libraries such as Pandas, Matplotlib, and Seaborn can be effectively used for real-world data analysis. The insights gained from this analysis can help policymakers and manufacturers understand the current landscape of electric mobility.
