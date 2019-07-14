# Sparkify

## Table of Contents

1. [Installation](#installation)
2. [Directory Structure](#directoryStructure)
3. [Project Motivation](#motivation)
4. [Data Exploration](#exploration)
5. [Features](#features)
6. [Modelling](#modelling)
7. [Results](#results)

## Installation <a name="installation"></a>
This project was written in Python 3.6, using a Jupyter Notebook on Anaconda. The relevant Python packages for this project are as follows:

- numpy
- pandas
- datetime
- pyspark.sql
- pyspark.sql.functions
- pyspark.sql.types
- pyspark.sql.window
- pyspark.ml.feature 
- pyspark.ml.classification
- pyspark.ml.evaluation
- pyspark.ml.tuning
- sklearn.metrics

## Directory Structure <a name="directoryStructure"></a>

- Root /

    - README.md  
    - Sparkify.ipynb
    
## Project Motivation <a name="motivation"></a>
Sparkify is a music streaming service like Spotify. There are paid premium services and free basic services. 
The free users will listen to ads while the paid users consume songs ad-free. At any time users can upgrade, 
downgrade or cancel their subscription. 
We want to identify the users that could potentially cancel their account and leave the service. 
By identifying this population upfront, we could incentive them by giving them discounts or other rewards. 
This could make them stick, giving us a loyal customer base which is important for the company's success.

Within this project churn is defined as a cancellation of service. 
In case a "Cancellation Confirmation" event for a user is detected, this user is considered to have churned. 
There might be multiple cancellation confirmations, due to the fact, 
that a user registered after cancellations but cancelled again.

## Data Exploration <a name="exploration"></a>

## Features <a name="features"></a>

## Modelling <a name="modelling"></a>

## Results <a name="results"></a>
The GBT (Gradient Boosted Trees) classifier produced the best results. An F1 score of 85.7 % could be reached after a Grid search. The values for Precision and Recall were 78.9 % and 93.7 %.
