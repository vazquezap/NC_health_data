# Overview
## NC Health Data
This repository contians instructions and resources for creating and using North Carolina health data.

The repository contains an instructional Python notebook **(NC_health_data.ipynb)**, the original *.csv* file **(CountyHealthData_2014-2015.csv)** for retrieval, and additional resources such as **NC_subset.csv**, **NC_subset_health.csv**, and visualizations, in addition to this **README.md** file.

The original dataset in this repository **(CountyHealthData_2014-2015.csv)** has been retreived from Professor Gotzler's English 105 course through the University of North Carolina at Chapel Hill.

# Why North Carolina? 
This repository specifically focuses on data from North Carolina. This repository may interest residents of North Carolina the most, however, it is important that this dataset be analyzed by outside perspectives, i.e. those residing in other states. The **purpose** of looking at the data from North Carolina is to find a correlation, if any, among different variables relating to healthcare costs (i.e. uemployment, uninsured individuals, median household income). Although each variable may potentially have a relationship to healthcare costs, this does not mean that there *must* be some type of correlation. For instance, unemployment rates and median household income for each county might not relate to each other, but the variables are important to consider as a whole, which is why they are included in the dataset. 

# What Can this Data Show?
Through analysis of this data, individuals may generate a deeper understanding of issues relating to healthcare costs. Categorical variables such as unemployment, uninsured children and adults, and median household income are useful components in understadning correlations within the dataset.

**Potential outcomes** rely on the availability of this dataset to the public, policy makers, researchers, and educators who may be intersted in reviewing this data as means to potentially address issues relating to healthcare costs. Analyzing trends in this dataset is an important step to mitigating social issues relating to healthcare. 


# Visualizing NC Data

***NC_subset_health contains data which may be valuable for visualization.*** 

## Potential Visualizations: Maps
The following visualization shows the percent of uninsured individuals in North Carolina, by county, in 2015.

**View the interactive version of this visualization:**
https://datawrapper.dwcdn.net/xF1uf/2/

![nc_map_uninsured](https://user-images.githubusercontent.com/118190183/204169252-420bcaf7-9e23-49ba-96de-a756765122d4.png)

## Potential Visualizations: Bar Graphs
The following visualization shows the top ten counties with the highest healthcare costs in North Carolina. The bar graph is formatted to show cost in descending order.

<img width="960" alt="Captura de pantalla_20221127_093558" src="https://user-images.githubusercontent.com/118190183/204179496-42adb743-d860-4736-b495-2d64156f874c.png">


#### Tip For Data Visualization
A simple way to produce data vizualizations using **NC_subset.csv** or **NC_subset_health.csv** is to change the numberical values (Uninsured, Unemployment, etc.) from decimals to percentages.
