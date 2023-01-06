# Strava Archive Analysis

## Introduction
Strava is a popular website typically used by cyclists and runners to track GPS data from physical exercise. This code is written in Python3 using Jupyter Notebook with the intention of providing insight into a personal Strava archive containing data accumulated over six years. 

## Requirements
Download the 'Individual Project: Strava Archive Analysis.ipynb' Jupyter Notebook and associated 'activities.csv' file from this repository. In order to run the code, Python3 and Jupyter Notebook should be installed - both are available via Anaconda Navigator. A number of packages are required and they are stated below. Instruction on their installation is provided in the 'Individual Project: Strava Archive Analysis.ipynb' notebook.

Necessary Packages:
- pandas
- seaborn
- matplotlib
- sklearn
**any more?**

## Instructions
- Ensure that the notebook and csv file are saved in the same directory.
- Open the 'Individual Project: Strava Archive Analysis.ipynb' notebook and import the necessary packages stated above.
- Read in the 'activities.csv' file
- Run the cells sequentially. Note that some cells will overwrite existing data in the data frames therefore errors may be generated should you try to run a cell a second time without reloading the data.

## Notes on Compatibility
Ideally this code would be applicable to any given archive as downloaded from the Strava website. However, for the purposes of anonymity and efficiency, the 'activities.csv' file saved here was heavily modified in Microsoft Excel prior to use. As a result, the code as written is unlikely translate to another individual's archive without similar modification of the csv file.

