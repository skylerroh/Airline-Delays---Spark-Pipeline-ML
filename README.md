# Airline-Delays-Spark-Pipeline-ML
Basic Spark pipeline that engineers novel features and produces and evaluates various models for classification of departure delays.  
This repo contains a jupyter notebook that was originally run on the databricks platform. The notebook exhibits a linear end to end process of producing a model that predicts the probability that a flight is delayed by more than 15 min on departure.  

The full pipeline seen at the end of the notebook utilizes several techniques in Data Engineering and ML including:
 - distributed feature engineering using both core Spark Dataframe and RDD apis
 - writing and reading parquet checkpoints
 - pagerank and clustering
 - logistic regression, random forest, and gradient boosted trees
 - choice of evaluation metrics based on specific problem and use case
 - pairs-based algorithm to obtain evaluation metrics considering distributed environment
