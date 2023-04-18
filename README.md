# Seattle vs St.Louis Weather

Description :
The purpose of this project is to determine the differences between St. Louis & Seattle Weather; specifically identifiying the differences in rain/precipitation. 

Software: 
The software used in this project was google colab. The Earth Engine Python API can be deployed in a Google Colaboratory notebook. Colab notebooks are Jupyter notebooks that run in the cloud and are highly integrated with Google Drive

Data: 
The NOAA National Centers for Environmental Information provides access to many types of environmental data, including records of daily precipitation. You can use their website https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND to request records of daily precipitation from Seattle and St. Louis (or other locations of interest) for the last 5 years (2018 - 2022). Dr. Brian Fischer, a professor at Seattle University, had both sets for seattle & st. louis ready for his students found in his git https://github.com/brian-fischer/DATA-3320/tree/main/weather

Data Processing/Analysis: 
In order to prepare the data, specific steps were taken, this included: converting data types, selecting relevant subsets, removing unnecessary parts, identifying and dealing with NaN/missing values, mergining the two sets, renaming the columns and creating derived variables to use in the final analysis. 

The data preparation was done on google collabration & is called = Bayan_Farag_DATA_3320_Seattle_St.Louis_Data

The final data file is called = clean_seattle_stl_weather.csv

Analysis: 
In order to analyze the data and create meaningful plots, specific steps were taken, this included: breaking the problems into smaller subproblems, plotting those subproblems & making new dataset called df_more - which limited a range for precipitation, adding labels/descriptions to plots, and finally stating the conclusions made/found 

The file name in the Github repo that performs the data analysis is called = Bayan Farag DATA 3320 Seattle St Louis Analysis Template.ipynb

Authors: 
Bayan Farag & Dr. Brian Fischer. 
Bayan is an undergrad student at Seattle University studying Computer Science and a Minor in Data Science. Dr. Fischer is a professor at Seattle University He has a B.A. in Mathematics from Illinois Wesleyan University and a D.Sc. in Systems Science & Mathematics from Washington University in St. Louis.

Liscense Section: 
Any individual may use the materials in the repository as well as cite and annotate on there own colab notebook. 

