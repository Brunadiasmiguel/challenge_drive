# challenge_drive

# Lyft: Driver's analysis

## Project Description

The goal of the project was to take insights from three datasets containing information about drivers and their rides to know what is the **driver's lifetime value**. An in depth analysis was performed to answer additional questions related to the topic and Python was chosen as the coding language to perform the analysis.  

## Questions and Hypotheses

Through the challenge a few questions and hypotheses were raised. The mail goal was to answer the question: "what is the driver's lifetime value?". 
Additional questions were raised and answered:

1) What factors affect the driver's lifetime value?
2) How is Lyft's revenue calculated?
3) What driver segments generate a higher lifetime value?
4) What is the projected lifetime of a driver?
5) What insights can be taken from the driver churn information?
6) What days and times are more popular?
7) What information can be taken from the Prime Time information in order to incentivise drivers to work at certain times?
8) What relevant business values has the lifetime value?
9) What future strategies can be advised based on the data?

## Datasets 

Three data sets were used for the analysis:

- driver_ids.csv: with the driver ids and onboarding data

- ride_ids.csv: with ride information as distance and time

- ride_timestamps.csv: with the ride timestamp and event information


They were all organised locally in the folder data, not available online due to possible privacy issues.

## Data Wrangling and Analysis

All data manipulation is in the notebook file named data_wrangling.ipynb.

## Results

A few interesting results came from the analysis, for instance:

1) The Driver's lifetime value is $ 766 in three months overall
2) The lifetime value is highly dependent on the number of rides, therefore three clusters were created: occasional, average and frequent drivers
3) The average lifetime of a driver is 55 days
4) Number of days until off-boarding and the number off rides done have some correlation
5) After 6 weeks active in the app, the churn starts to increase considerably. Week 10 was the most critical week for exits
6) The churn rate reached 50% between weeks 8 and 9 after onboarding
7) Friday and Saturday nights seems popular times
8) There are some times with potential to explore since the prime time was high and they were not the times with more rides

## Problems

Due to time restrains, further time series analysis to understand predictive factors for churn could have been done, as analysing revenue drops and number of rides drops closer to offboarding. Potential outlier analysis could have been made with more time as well.

## Repository Organisation

The repository has a git.ignore file, a README.md file with the project explanation and the data_wrangling.ipynb file with the data wrangling and analysis, including plotting. 

## Project Links

The link to the repository is: https://github.com/Brunadiasmiguel/challenge_drive

The link to the presentation is: https://docs.google.com/presentation/d/17EqnSEd3QWl_93eThCwhDDeGOAbWGiHmdNwEhDcMVMA/edit?usp=sharing