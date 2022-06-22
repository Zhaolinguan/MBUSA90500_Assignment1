# MBUSA90500_Assignment1
- Student Name: Zhaolin Guan
- Student ID: 1079227
- Report Link: https://github.com/Zhaolinguan/MBUSA90500_Assignment1

# Description 
The City of Melbourne has been hard hit over the last 2 years due to the COVID-19 pandemic and the amount of
pedestrian traffic has changed considerably. Your company Modellers-R-Us specialises in modelling pedestrian
activity in parts of the city of Melbourne. You are developing Python code that will help analyse pedestrian activity
across different parts of the City of Melbourne. In particular, your software will analyse pedestrian counts and
relation to other factors, such as time, maximum temperature, rainfall and solar exposure.

# Dependencies
- Language: Python 3.8.3
- Packages / Libraries: in 'requirements.txt'
- Download requirements.txt and install on terminal: pip install -r requirements.txt

# Datasets
- Primary dataset: count2021-2022.csv
	- The source data website for primary data: https://data.melbourne.vic.gov.au/Transport/Pedestrian-Counting-System-Monthly-counts-per-hour/b2ak-trbp?src=featured_banner
- External dataset 1: temperature-all-years.zip
- External dataset 2: rainfall-all-years.zip
- External dataset 3: solar-all-years.zip
	- The source data website for external datasets: http://www.bom.gov.au/climate/data/

# Directory
- `raw_data`: Contains all the raw data files. Instruction for downloading is in **1_Downloads.ipynb**
- `processed_data`: Contains all the preprocessed data files. 
- `plots`: Output and save all your figures here.
- `code`: Keep all notebooks and scripts in this folder. 
    - Notebook 1_Downloads.ipynb for "Extracting Data" and "Installing Packages".
    - Notebook 2_Preprocessing_Covid.ipynb for "Preprocessing" and "Exploratory Data Analysis" of covid data 
    - Notebook 2_Preprocessing_Taxi.ipynb for "Preprocessing" and "Exploratory Data Analysis" of yellow taxi data 
    - Notebook 2_Preprocessing_Taxi_CleanVersion.ipynb for "Systematic Preprocessing" and "Aggregations" of yellow taxi data
    - Notebook 2_Preprocessing_Ridership.ipynb for "Preprocessing" and "Exploratory Data Analysis" of ridership data
    - Notebook 3_Taxi_Analysis.ipynb for "Analysis and Visualisation" of yellow taxi data 
    - Notebook 3_Covid_Analysis.ipynb for "Analysis and Visualisation" of covid data 
    - Notebook 3_Weather_Analysis.ipynb for "Analysis and Visualisation" of weather data 
    - Notebook 3_Visualisation_folium.ipynb for "Visualisation" using folium.
    - Notebook 3_Visualisation_pyshp.ipynb for "Visualisation" using pyshp.
    - Notebook 4_Modelling.ipynb for "Statistical Modelling".
- `deprecated`: A folder of code that I experimented with, but decided to not go ahead. 

