# Compute Descriptive Statistics with Python

This repository contains Python notebooks for two projects focused on computing descriptive statistics to explore and summarize datasets using Python.

## Project 1: Exploring Literacy Rate Data

### Introduction
Throughout this notebook, we will practice computing descriptive statistics to explore and summarize a dataset. Before getting started, make sure to watch the associated instructional video and complete the in-video question. All of the code we will be implementing and related instructions are contained in this notebook.

### Overview
Whenever a data professional works with a new dataset, the first step is to understand the context of the data during the discovering stage. Often, this involves discussing the data with project stakeholders and reading documentation about the dataset and the data collection process. After that, the data professional moves on to data cleaning and addresses issues like missing data, incorrect values, and irrelevant data. Computing descriptive stats is a common step to take after data cleaning.

In this notebook, we will use descriptive stats to get a basic understanding of the literacy rate data for each district in your education dataset.

## Project 2: Analyzing Air Quality Data

### Introduction
Data professionals often use descriptive statistics to understand the data they are working with and provide collaborators with a summary of the relative location of values in the data, as well as information about its spread.

For this activity, you are a member of an analytics team for the United States Environmental Protection Agency (EPA). You are assigned to analyze data on air quality with respect to carbon monoxide, a major air pollutant. The data includes information from more than 200 sites, identified by state, county, city, and local site names. You will use Python functions to gather statistics about air quality, then share insights with stakeholders.

### Key Takeaways
- Functions in the pandas and numpy libraries can be used to find statistics that describe a dataset.
- The describe() function from pandas generates a table of descriptive statistics about numerical or categorical columns.
- The mean(), median(), min(), max(), and std() functions from numpy are useful for finding individual statistics about numerical data.

### Presenting Findings
- AQI values at or below 100 are generally thought of as satisfactory. When AQI values are above 100, air quality is considered to be unhealthy—at first for certain sensitive groups of people, then for everyone as AQI values increase.
- An AQI of 100 for carbon monoxide corresponds to a level of 9.4 parts per million.
- The average AQI value in the data is approximately 6.76, which is considered safe with respect to carbon monoxide. Further, 75% of the AQI values are below 9.

### Summary for Stakeholders
- 75% of the AQI values in the data are below 9, which is considered good air quality.
- Funding should be allocated for further investigation of the less healthy regions in order to learn how to improve the conditions.

---

### Notebooks

1. [Project 1 - Exploring Literacy Rate Data](project1.ipynb)
2. [Project 2 - Analyzing Air Quality Data](project2.ipynb)

Each project has its own notebook for detailed implementation and analysis.

Feel free to explore the notebooks in this repository to learn more about these projects and the techniques used for computing descriptive statistics with Python.

