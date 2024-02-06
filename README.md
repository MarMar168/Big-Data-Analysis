Task 1: Data Loading and Data Cleaning (40%)
Download the data from OL. There are three datasets (T_Data_C1.csv, T_Data_C2.csv, and T_Data_C3.csv).
Each row of data consists of nineteen columns (independent variables) that describe the characteristics of a fictional telecoms company's clients You need to upload all three datasets onto Databricks with the fully managed Spark clusters in the cloud, you can easily provision clusters in the unified data analytics framework and rename them to be:
 BDA_T_data_C1.csv
 BDA_T_data_C2.csv
 BDA_T_data_C3.csv
You need to provide a suitable screen capture of the step. You then create a new workspace on Databricks and import three datasets into the experiment. You need to explore the various datasets, report the size of each dataset, and write the variables in each dataset and identity do they have any similarity. In the lecture class, seminar has indicated various ethical consideration of data science. What would be your opinion to be considered on the given datasets? Discuss your answer.
As part of the experiment, you need to create cluster to operate over the datasets into a single schema whenever it is necessary. This can be done through Databricks cloud notebook Write Pyspark code to read the dataset and organize it drop whenever is necessary. Find out how to operate on data in Spark with schemas. Explore and select suitable number of columns out of 21 attributes then describe the summary on maximum, minimum, average, and standard deviation by apply Spark-SQL functions. You need to apply suitable Join operators to perform merge dataset and remove the rows, which has zero values for the data transformation operations.


Task 2: Customer Retention Prediction and Display Results (60%)
Using Databricks community edition create the data visualizations using data from the cleaning dataset. Make a suitable screen capture of each plot and describe on what are the insights it depicts. You need to write the Pyspark code to manipulates the data and display the results.
1. Find the number of churn users are in the dataset, Discuss your opinion on the output whether the given dataset is balanced or imbalanced. What will be the descriptive statistics for tenure, totalcharges, and monthly charges? (10 Marks)
2. Do the analysis on a) Male, Female, churn, and b) Seniorcitizen,churn out of the two which is the most suitable attribute that can you can keep for further analysis? Does the tenure correlate to people become churn? Pivot the values and plot the values for better representation. (10 Marks)
3. 3. Use a model building process with data bricks for the given data, create a suitable training, evaluation data items, then build a pipeline with suitable transformers (onehotencoder, stringindexer, vectorassembler) (10 Marks)
4. Manipulate the feature engineering, using the transformers Imputer, StringIndexer, QuantileDiscretizer. Use VectorAssembler to give input to the model, you may take note, to use suitable numerical columns to end the feature engineering stage. (10 Marks)
5. Combine the pipeline fit, configure the train, test data and apply suitable regression model for the label and features columns. Execute the model and print the results of accuracy, plot the output with Area Under ROC. Evaluate the model with Binaryclassifiermetrics to analyse the prediction. (20 Marks)
