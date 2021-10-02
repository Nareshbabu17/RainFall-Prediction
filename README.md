# RainFall-Prediction
Prediction of Rainfall using Machine Learning Algorithms(Random Forest Classifier)
Data Description 
Data was collected from weatherAus which contains values of humidity, rainfall, evaporation, windspeed, winddirection, cloud, temperature, pressure, and Rain today
Rain Tomorrow is the label which has to be predicted by considering all the values of the features given above.
Random Forest is a supervised learning algorithm which is used for both classification as well as regression. But however, it is mainly used for classification problems. As we know that a forest is made up of trees and more trees means more robust forest. Similarly, random forest algorithm creates decision trees on data samples and then gets the prediction from each of them and finally selects the best solution by means of voting. It is an ensemble method which is better than a single decision tree because it reduces the overfitting by averaging the result.
Results
Random Forest implementation with using train set resulted model that has accuracy 96.72%, mean squared error = 0.032, root mean squared error = 0.18, ROC Area = 0.93 By testing set the model has accuracy 85.38% mse = 0.14 rmse = 0.17 ROC area = 0.73
