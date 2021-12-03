# MAST30034 Project - Quantitative Analysis
- Student Name: Huan Zhang
- Student ID: 1173919
- Due Date: Friday 13th of August 11:59:00 am (AEST).

# Report Link: https://www.overleaf.com/read/yvwznfsvkswh

# Dependencies
- Language: Python 3.8 or above
- Packages / Libraries: see `requirements.txt`

# Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- NOAA Temperature: https://www.ncdc.noaa.gov/cdo-web/search
- NYC Population: https://data.cityofnewyork.us/City-Government/New-York-City-Population-By-Community-Districts/xi7c-iiu2
- city of NY Traffic Counts: https://data.cityofnewyork.us/Transportation/Traffic-Volume-Counts-2014-2019-/ertz-hr4r
- New York city boroughs shapefile: https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm
- EIA Gasoline retail price: https://www.eia.gov/dnav/pet/hist/LeafHandler.ashx?n=PET&s=EMM_EPMMR_PTE_SNY_DPG&f=W
# Directory
- `raw_data`: since the data size is too large, please run the "download" note book to dowlond all the taxi data, but THIS TAKES TIME AND REQUIRES ENOUGH DISK MEMORY (for a whole year data)
- `data`: Contains all the preprocessed data files. 
- `plots`: All the plots created
- `code`: All notebooks and scripts are in this folder. 
    - "preprocess.ipynb" for "Preprocessing" the taxi data
    Note: to run this book, you need to donwload 2019 whole year yellow taxi data to "../raw_data/2019" / run "download.ipynb". Also this notebook required a lot time to run (roughly 45-60mins), large enough memory and RAM to re-generate the "parquet" outputs in "../data/"
    - "weather_preprocess.ipynb": preprocessing the weather data same as above, don't run this if you don't have enough memory. (data is in "../raw_data/weather.csv")
    - Notebook 'Overall_Inference' is for general analysis and visualisation
    - Notebook 'Population_Inference' is for analysing the connection between zones and population's effect
    - Notebook 'Weather_Inference' is for exploring the relationship between weather and the taxi data
    - "download.ipynb" for downloading the raw taxi data from the website
ALL THE AGGREGATED RESULTS ARE SAVED IN 'data/'
