# Sparkify

## Table of Contents

1. [Installation](#installation)
2. [Directory Structure](#directoryStructure)
3. [Results](#results)

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
    
## Results <a name="results"></a>
The GBT (Gradient Boosted Trees) classifier produced the best results. An F1 score of 85.7 % could be reached after a Grid search. The values for Precision and Recall were 78.9 % and 93.7 %.
