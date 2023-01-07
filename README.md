## Strava Archive Analysis

### Introduction
Strava is a popular website typically used by cyclists and runners to track GPS data from physical exercise. This code is written in Python3 using Jupyter Notebook with the intention of providing insight into a personal Strava archive containing data accumulated over six years. 

### Requirements
Download 'strava.ipynb' and 'activities.csv' file from this repository. In order to run the code, Python3 and Jupyter Notebook should be installed, both of which are available via Anaconda Navigator. Any additional packages are stated below - instruction on their installation is provided in the 'strava.ipynb' notebook.

Necessary Packages:
- pandas
- seaborn
- matplotlib
- sklearn

### Instructions
1. Ensure that the notebook and csv file are saved in the same directory.
2. Open the 'strava.ipynb' notebook and import the necessary packages stated above.
3. Read in the 'activities.csv' file.
4. Run the cells sequentially. Note that some cells will overwrite existing data, therefore errors may be generated should you try to run a cell a second time without reading in the original data again.
5. The notebook is split into four sections:
   - Manipulation of the Dataset - this code will re-organise the data frame to facilitate the subsequent analysis.
   - Initial Exploration - this returns numerical answers to specific questions as part of f-strings.
   - Visualisation - a number of plots are generated using seaborn to visualise other aspects of the data.
   - K-Nearest Neighbours Analysis of Cycle Commutes - aspects of the scikit-learn package are applied to a subset of the data to model cycle commutes in five different locations.

### Notes on Compatibility
Ideally this code would be applicable to any given archive as downloaded from the Strava website. However, for the purposes of anonymity and efficiency, the 'activities.csv' file saved here was heavily modified in Microsoft Excel prior to use. As a result, the code as written is unlikely translate to another individual's archive without similar modification of the csv file.
