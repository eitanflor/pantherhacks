# PantherHacks 2020

Developed by: 
- Jerry Contreras
- Eitan Flor

## About

This project focuses on finding a possible solutions and enhancements in the broad health and community categories. As a result of the current COVID-19 situation, it is of paramount importance to mitigate the spread of the virus to flatten the curve. This will serve in reducing the load on local hospitals, allowing local business to reopen, along with public schools, colleges, and universities. For the community and FIU, this project will seek to merge computer science techniques and integrate live sources of local COVID-19 data to provide a basis for identifying high risk candidates and assigning statistical risk profiling metrics. Additionally, with further integration into a neo4j graph database, the possibilities greatly expand in enabling querying and visualization. Some practical examples involve identifying the individuals with the highest associated risk score, classifying zip-codes with the highest risk, and predicting infections (cases) based on factors of address, household size, and ethnicity. 

## Tools, Technologies, and Resources

<p align="center">
    <img src="https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/Google%20Resources/cloud.png">
    <img src="https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/Google%20Resources/neo4j.png">
<br>  
    <img src="https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/Google%20Resources/bigquery.png">
    <img src="https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/Google%20Resources/automl.jpg">
    <img src="https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/Google%20Resources/storage.png">
<br>
    <img src="https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/Google%20Resources/maps%20platform.png">
</p>

1. Python/Jupyter Notebook
1. Neo4j Graph Database
1. Google Maps Platform
    1. Geocoding API and Maps Javascript API
1. Google Cloud Platform
   1. Storage (Buckets)
   1. BigData
      1. Big Query
   1. Artificial Intelligence
      1. Tables (Dataset and ML Model) 

## Project Examples

Here are examples of the plotted data for the combined categories of the FIU student population, faculty, support, and administrative. 

![Map Image 1](https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/Zoomed-Out-Focus.JPG)
![Map Image 2](https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/FIU-MMC-Focus.JPG)

To explore this map in more detail, navigate to the interactive version by downloading the complete html file [here](https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/map.html).

Utilizing the completed python script, alongside Neo4j, we can construct a proof-of-concept network for FIU as shown below 

![Neo4j Network](https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/neo4j.png)

Further applications will involve network analysis and querying to identify possible high risk candidates, aid in contact tracing, and provide risk profiling metrics. 

## Machine Learning Model Results and Predictions

Here are the summary statistics of the deployed model:

<p align="center">
    <img src="https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/model%20results.JPG">
</p>

Also a sample of the estimated infections (cases) are depicted below:

<p align="center">
    <img src="https://github.com/eitanflor/pantherhacks/blob/master/Static%20Files/model-sample-results.JPG">
</p>


