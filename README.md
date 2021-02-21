# pandas-challenge

Introduction: 

This assignment utilizes Pandas and Jupyter Notebook to analyze a set of data for Heroes of Pymoli. Pandas utilizes data frames to analyze data from an original csv file. Several techniques were made to analyze the data into the final summary data frames, including cleaning of the data, unique, mean, count, sum, map/format, value_counts, values, set_index, groupby, bins, and sorting.



Observations/Problems:

The sorting code only works on numerics. Once a column has been formatted to currency it is no longer a numeric and therefore will not sort as intended. My fix for this problem was to copy the desired column for the sort and create a 'faux' column. I could then successfully change the original column to currency with the map/format. The 'faux' column remained a numeric and was used for sorting. My final summary table would then be crafted to exclude the 'faux' column. The end result was a summary table that mimics that of the starter.



Table of Contents:

-HeroesOfPymoli

​		-Resources

​				-purchase_data.csv: Raw Data

​		-HeroesOfPymoli.ipynb: All coding in Jupyter Notebook to complete analysis.

​		-HeroesOfPymoli_starter.ipynb: Starter/Guide

​		-Observations_Trends.txt: Contains observation and trends made on HeroesOfPymoli.ipynb

-README