#  Segmentation using Clustering and PCA

The data collected has many variables which makes it difficult to find useful details without using Data Science Techniques. The very first step is to perform EDA and then performing Clustering, PCA as per the requirements in the data.

## Skills and Tools

    - EDA
    - Clustering
    - PCA
    - Data Mining
    - Silhouette Score
    - Segmentation
    
## Problem 1 - Part 1: PCA:

Problem Statement: The ‘Hair Salon.csv’ dataset contains various variables used for the context
of Market Segmentation. This particular case study is based on various parameters of a salon chain
of hair products. You are expected to do Principal Component Analysis for this case study
according to the instructions given in the rubric. Kindly refer to the PCA_Data_Dictionary.jpg
file for the Data Dictionary of the Dataset.
Note: This particular dataset contains the target variable satisfaction as well. Please do drop
this variable before doing Principal Component Analysis.


## Problem 2 - Part 2: Clustering:

The State_wise_Health_income.csv dataset given is about the Health and economic conditions
in different States of a country. The Group States based on how similar their situation is, so as to
provide these groups to the government so that appropriate measures can be taken to escalate
their Health and Economic conditions.

  2.1. Read the data and do exploratory data analysis. Describe the data briefly. (Check the null
  values, Data types, shape, EDA, etc, etc)
  2.2. Do you think scaling is necessary for clustering in this case? Justify
  2.3. Apply hierarchical clustering to scaled data. Identify the number of optimum clusters using
  Dendrogram and briefly describe them.
  2.4. Apply K-Means clustering on scaled data and determine optimum clusters. Apply elbow curve
  and find the silhouette score.
  2.5. Describe cluster profiles for the clusters defined. Recommend different priority based actions
  that need to be taken for different clusters on the bases of their vulnerability situations according to
  their Economic and Health Conditions.

## Data Dictionary for State_wise_Health_income Dataset:

 1. States: names of States
 2. Health_indeces1: A composite index rolls several related measures (indicators) into a single score
 that provides a summary of how the health system is performing in the State.
 3. Health_indeces2: A composite index rolls several related measures (indicators) into a single score
 that provides a summary of how the health system is performing in certain areas of the States.
 4. Per_capita_income-Per capita income (PCI) measures the average income earned per person in a
 given area (city, region, country, etc.) in a specified year. It is calculated by dividing the area's total
 income by its total population.
 5. GDP: GDP provides an economic snapshot of a country/state, used to estimate the size of an
 economy and growth rate.


Dataset for Part 1: PCA: Hair Salon.csv
Dataset for Part 2: Clustering: State_wise_Health_income.csv


    
