# San Francisco Ford GoBike Project
![Ford GoBike](https://github.com/Sadiq-marcelo/investigate-FordGoBike-tripdata/assets/117516151/80a9885b-bac5-4954-b51a-5aeb50f492c6)



## Executive Summary
#### What is the project's main purpose?

This project seeks to explore Ford's Go Bike trip sharing data in San Francisco Bay Area 2019 using various data analysis methods ranging from Descriptive to Exploratory Data Analysis (EDA). This project is carried out using various techniques like data wrangling (gathering, assessing and cleaning), data visualization, and explanatory data analysis.

#### What are some of the key findings and conclusions drawn from your analysis?
As a result of the analysis carried out, here some of the key findings and conclusions considered includes:
* Most biders are between ages of 30 to 40years regardless of gender.
* Most trips were made during morning and afternoon, GoBike is popular with office commuters and students with frequency of bike sharing peaking at 8am to 9am during office and school going hours, and from 5pm to 6pm during office and school closing hours. Also, Thursdays happens to be most popular with riders, whilst there isn't much biking during weekends.
* There's negative trend between the bikers age and trip frequency as people tend to make less trips as they age older. 

## Introduction
#### Overview
The dataset contains 183,412 records of trips, and 16 different features including start time, end time, start station, end station, and latitude/longitude for each station.The dataset contains few numeric variables and categorical variables.

#### What are the problems tackled in this project?
The problems tackled in this project investigates the data further giving us insights by exploring the trends, characteristics, and features that are hidden within the data to help us make more informed data driven decisions. Some of these problems includes:

* What is the age distribution of bikers?
* What is trip frequency by bikers?
* What is the relationship between bikers age and trip duration?

#### Why is the project important?
The project dives deep into Ford's bike trip data giving us insights into customer (bikers) behaviour, and how Ford GoBike can improve it's service. Moreover, the project covers each step of the data analysis process in a chronological order from data gathering, data assessment and cleaning, data exploration, data visualization to sharing findings to perform thorough analysis on the data in question.

#### Where is this data sourced from?
The data used in this project is one of three projects carried out during Udacity Data Analyst Nanodegree Program. The data is provided by Udacity for the sole purpose of building projects utilizing the data analysis process.

## Methodology
The main methods utilized to carry out analysis involves:

* Descriptive Data Analysis
* Exploratory Data Analysis (EDA)

## Results/Data Analysis
Here are some of the results generated from the analysis made:
#### 1. Bikers Age Distribution
![bikers age distribution](https://github.com/Sadiq-marcelo/investigate-FordGoBike-tripdata/assets/117516151/36eb0e9f-ed61-47d9-b180-285c7511ccec)

The visualization here shows the age distribution of Go Bike users in with large chunk of riders within the age of 30 to 40 in both gender with least number of bikers ranging between 70 to 80 years.

#### 2. Trip Frequency by bikers
![most trips taken](https://github.com/Sadiq-marcelo/investigate-FordGoBike-tripdata/assets/117516151/29223ba7-1e4c-4deb-be83-669a0c833d11)

Unsurprisingly, most trips were made during morning and afternoon. The peak in this periods shows that GoBike is popular with office commuters and students with frequency of bike sharing peaking at 8am to 9am during office and school going time and from 5pm to 6pm during office and school closing times. Also, Thursdays happens to be most popular with riders, whilst there isn't much biking during weekends.

#### 3. Relationship between Bikers Age and Trip duration
![bikers vs trips taken](https://github.com/Sadiq-marcelo/investigate-FordGoBike-tripdata/assets/117516151/b08f217c-8273-44f2-9b26-d321663a3eff)

Notice the negative trend between the bikers age and trip frequency. With peaks between 330 to 600 seconds and age ranging from 25 to 35, the heatmap depicts the duration of trips taken to be short, and such, taken by people within working class and college going age. Importantly, the visualization shows a less trips are taken has users age.

## Conclusions
Summary of findings and recommendations includes:
* Most biders are between ages of 30 to 40years regardless of gender.
* Most trips were made during morning and afternoon, GoBike is popular with office commuters and students with frequency of bike sharing peaking at 8am to 9am during office and school going hours, and from 5pm to 6pm during office and school closing hours. Also, Thursdays happens to be most popular with riders, whilst there isn't much biking during weekends.
* There's negative trend between the bikers age and trip frequency as people tend to make less trips as they age older. 

