
Over 20% of airlines flight arrive more than 15 minutes late. This figure shows how important the issue of predicting flight delays is. Being able to process large amount of both weather and flights data is key to being able to predict this delays with machine learning techniques. 


The aim of this project is to optimize the data preparation process in a big data setting. In fact, the data preparation process involves cleaning and joining two main datasets. The first dataset is the Airline On-Time Performance (AOTP) dataset provided by RITA - Bureau of Transportation Statistics for the five-year period beginning January 2009 and ending December 2013. The second dataset is the Quality Controlled Local Climatological Data (QCLCD) for the same period gathering hourly weather data. Both these datasets are rather large (> 20 Gb) and require the use of big data techniques. 

The project consists in translating into Spark (both Dataframes and RDDs) a MapReduce instance of the data preparation process described in [1]. 


This final report explains the method followed to reach the objective and provides an analysis of the result. Section 2 describes the solution based on the work developed in [1]. Section 3 describes the different datasets. Section 4 focuses on the various implementations, in Python using RDD and Dataframes of the data preparation process . Finally, sections 5 focuses on the difficulties and section 6 provides a SparkMLlib implementation of the machine learning process described in [1]

