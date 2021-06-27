# Y100_ForecastsAndPredictions_MachineLearning_ChurnPredictingProject
Project Description
The gym chain Model Fitness is developing a customer interaction strategy based on analytical data. 
In order to fight churn, Model Fitness has digitized a number of its customer profiles. Your task is to analyze them and come up with a customer retention strategy.

Instructions for completing the project
Step 1. Download the data
Step 2. Carry out exploratory data analysis (EDA)
-Look at the dataset: does it contain any missing features? Study the mean values and standard deviation (use the describe() method).
-Look at the mean feature values in two groups: for those who left (churn) and for those who stayed (use the groupby() method).
-Plot bar histograms and feature distributions for those who left (churn) and those who stayed.
-Build a correlation matrix and display it.
Step 3. Build a model to predict user churn
-Build a binary classification model for customers where the target feature is the user's leaving next month.
-Divide the data into train and validation sets using the train_test_split() function.
-Train the model on the train set with two methods:
  -logistic regression
  -random forest
-Evaluate accuracy, precision, and recall for both models using the validation data. Use them to compare the models. Which model gave better results?
Remember to indicate the random_state parameter when dividing data and defining the algorithm.
Step 4. Create user clusters
-Set aside the column with data on churn and identify object (user) clusters:
-Standardize the data.
-Use the linkage() function to build a matrix of distances based on the standardized feature matrix and plot a dendrogram. Note: rendering the dendrogram may take time! 
Use the resulting graph to estimate the number of clusters you can single out.
-Train the clustering model with the K-means algorithm and predict customer clusters. (Let the number of clusters be n=5, so that it'll be easier to compare your results with those of other students. 
However, in real life, no one will give you such hints, so you'll have to decide based on the graph from the previous step.)
-Look at the mean feature values for clusters. Does anything catch your eye?
-Plot distributions of features for the clusters. Do you notice anything?
-Calculate the churn rate for each cluster (use the groupby() method). Do they differ in terms of churn rate? Which clusters are prone to leaving, and which are loyal?
Step 5. Come up with conclusions and basic recommendations on working with customers
Draw conclusions and formulate recommendations regarding the strategy for customer interaction and retention.
You don't need to go into detail. Three or four essential principles and examples of their implementation in the form of specific marketing steps will do.
