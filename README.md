# Titanic-Survivors-Prediction-Model
Prediction Model for finding the survivors 

As many of you might know that this is one of the most classical problem of Machine Learning and usually most often used by most of the beginners of this field while developing their first Machine Learning model. This problem is taken from one the past incidents occurred in the history of the world, in which the ship as you all know the name Titanic had sinked deep into the ocean after collision from an iceberg which led to death of many passengers of this ship.

Dataset which we are using in building this model have the required features and target variables such as:
- Features of the Dataset: (a) Name of Passengers
                           (b) Passengers ID
                           (c) Age
                           (d) Cabin
                           (e) Embarked
                           (f) Pclass (Passengers Class)
                           (g) Ticket
                           (h) Fare
                           (i) SibSp (Siblings/Spouse)
                           (j) Sex (Male/Female)
- Target Label: There is only one target label for this dataset and that is 'Survived'. This columns tells us about the Passengers who                       survived or not survived.

As a part of this project we need to follow several specific steps in order to complete this project which are:
- Data Loading into the Jupyter Notebook
- Data Preparation: This is the most crucial and important step of building a machine learning model which consists of the following:
                    (a) Data Cleaning: Fill the gaps in between the columns or rows of the Dataframe or replacing the 'NaN' With some                                              specific string or any numeric value.
                    (b) Dimensionality Reduction(if needed): This is the step in which we drop or remove certain specific columns or rows                                                                which are not relevant towards the project. 
                    (c) Encoding the Label: If we are using scikit learn library then we need to encode the labels into integer form(0,1 and                                             so on) for the categorical features and for the other types of features also if needed.
- Data Visualization: As we know that the collection of meaningful and well structured data is visually represented in order to give a                             better insight out of the data which is not possible in text format. So we use various plots from Matplotlib library                         and also from  the Seaborn library which better represent our data to understand it precisely.
- Developing Machine Learning Model: Now after all these steps we would develop some machine learning models using various algorithms such as: 
                                     (a) KNN Classifier Algorithm
                                     (b) Support Vector Machine Classification Algorithm
                                     (c) XGBOOST Algorithm
                                     (d) Random Forest Algorithm
- Deploying the Machine Learning Model: In this step we would save the final maximum accuracy of this machine learning model and then we                                             will develop a new Dataframe which would present the output of the predictions of Passengers who                                             Survived or not Survived corresponding to their Passenger ID.

In these specified steps we will develop our Model which can be used in any web or mobile application when needed.
