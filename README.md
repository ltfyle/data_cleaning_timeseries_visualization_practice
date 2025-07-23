## Learning Goals 
* My goals for this project were to solidify my knowledge of basic data cleaning, and to practice visualizations for data subsets with multiple categories.

## Background
* This is synthetic data for a made up cafe, created by kaggle user ahmedmohamed2003. It's shape is (10000, 7), containing three categorical columns, 3 numerical, and one datetime.

## Reflections
* Overall, I am pleased with the results of this project.
* I learned:
  *  how to use the missingno package to analyze missing values
  *  how to use the groupby method to efficiently get the dependent values for visualizations of multi-level data.
* I was disappointed that I couldn`t make my time series graphs more legible. I experimented with reducing the grainularity of the data by sorting by date, then taking every 10th row using the iloc method. This worked to make the quantity by location graph more legible, but it appeared to change the shape of the quantity by location by item graph. 
