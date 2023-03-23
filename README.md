# Disease-classification-SML-project
Objectives: 
->Use any four supervised ML models and compare their performances. 
->Apply dimensional reduction technique (PCA) on data and see how the classification accuracy decreases as the dimension is reduced. Plot a graph between classification accuracy and number of PCA features. 
->Apply Random Forest algorithm and tune the hyper-parameters for getting the best classification accuracy. 


In this project, CSV files for training and testing data are given. Each CSV file has 133 columns. 132 of these columns are symptoms a person experiences; the last column is the prognosis. These symptoms are mapped to 41 diseases (42 were written on the assignment however on checking different classes we get only 41). The data is so simple that by applying any machine learning algorithm, anyone can get an accuracy greater than 95%. I have tried 6 different machine learning algorithm in which Logistic Regression, Support Vector Machines, KNN and Naïve Bayes gives 100% accuracy whereas Decision Tree and LDA gives 97% accuracy.
Further PCA is applied to reduce the dimension of the feature vector and then observed how classification accuracy decreases as dimension is reduced and found that even with just 5 features almost all the algorithms gave more than 95% accuracy. Accuracy values for features varying from 1 to 20 are calculated and a plot of accuracy v/s features for all 132 features is present in the colab notebook whose link is given below.
At last, applied Random Forest and tuned the Hyperparameters using GridSearchCV which takes different parameters as key and different values of the parameters (in an array) as values in a dictionary and gives the best parameters on testing on validation data.
