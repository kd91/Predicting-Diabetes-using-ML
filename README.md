# Predicting-Diabetes-using-ML

Exploratory Analysis and Machine Learning on Diabetes Dataset:

This project includes exploratory analysis and will utilize sci-kit learn to train and test a support vector machine (SVM) to detect diabetes using the diabetes data based on the UC Irvine machine learning repository. 

Information about the data set:
Abstract: From National Institute of Diabetes and Digestive and Kidney Diseases; Includes cost data
(donated by Peter Turney)
(http://www.inf.u-szeged.hu/~tothl/gepitan/uci%20repository/WEB/UCI%20ML%20Repository%20Content%20Summary.htm)

The jupyter notebooks includes the following steps:
1. Load the diabetes data set from the csv file.
2. EDA - Conduct exploratory analysis of the dataset. Obtain aggregate statistics on each predictor variable and preprocess data appropriately. Create plots to tell the story of the data: display the distribution of each variable and relationships between some of the variables.
3. Partition the dataset into training and testing sets.
4. Using 2 different kernels (rbf and polynomial), train support vector machines to classify examples into control (0) and case (1). Select the best model for each kernel and explain how you chose the parameters you used: kernel, soft margin(C), gamma or degree. Record metrics including prediction accuracy, confusion matrix and area under the ROC curve.

Dataset : Attribute Information:
1. Number of times pregnant
2. Plasma glucose concentration a 2 hours in an oral glucose tolerance test
3. Diastolic blood pressure (mm Hg)
4. Triceps skin fold thickness (mm)
5. 2-Hour serum insulin (mu U/ml)
6. Body mass index (weight in kg/(height in m)^2)
7. Diabetes pedigree function
8. Age (years)
9. Class variable (0 or 1)
10. Age levels

Information about the scikit-learn:
scikit learn home page: http://scikit-learn.org/stable/index.html
scikit learn machine learning tutorial: http://scikit-learn.org/stable/tutorial/basic/tutorial.html
scikit learn SVM page: http://scikit-learn.org/stable/modules/svm.html#svm
scikit learn MinMaxScaler page:
http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html