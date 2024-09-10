# Advanced modeling

As part of our advanced statistical modeling course, we've created a project to study customer satisfaction among scooter users: 
- The "rapport" directory contains the report of this study written in french.
- The code directory contains the code used to realize our analysis
- The data directory contains the data used to do the analysis

## Project: Scooter users satisfaction.

File: scooter.xls

Several importance variables (score from 1 to 5) given by users to different characteristics of a scooter (store of origin, brand, etc.) are recorded as well as an overall satisfaction score (from 1 to 10).

## Objective 
- Find "typical" profiles of scooter users. 
- What's the difference between men and women? 
- What type of scooter would you suggest to a man/woman?

## Techniques used
 - Study of univariate and bivariate statistics as a function of the gender variable
 - Study of the correlation matrix
 - Creation of a PCA 

## Highlights 
 - Hierarchical clustering hcpc
    This test was not very conclusive, as the method failed to distinguish between two groups.
 - Performing MFA (multiple factor analysis)
    Since we have both quantitative and qualitative data, the afm method enables us to study all the data simultaneously.
 - Performing PCA also revealed also different insights between men and women

## Results

First, whe have identified 4 groups in our database. We have seen similitudes between the 2 first groups composed of men who prefer high-performance scooters with motercycle-like design. These men, typically from middle to upper-class backgrounds prioritize new technology. In contrast, women often express a preference for smaller, more stylish scooters.
