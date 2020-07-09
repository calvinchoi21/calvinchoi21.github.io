# Calvin_Portfolio
data science portfolio

# [Using Climate Data to Uncover Crime Patters in Toronto](https://github.com/calvinchoi21/toronto-crime-clustering/blob/master/Toronto_Crime.ipynb)

The aim of this project is to combine crime data obtained from the Toronto Police Service (TPS) with Toronto based climate data from the Government of Canada to uncover patterns in criminal activity in the city as it relates to climate. Clustering analysis is used to accomplish this task. Clustering is an unsupervised data mining technique that groups data such that objects in the same cluster share more similar properties than objects in other clusters. This project utilizes the K-prototypes algorithm to handle both the categorical and numerical features in the preprocessed dataset. Although the more popular K-means algorithm is also employed after some additional preprocessing, the more versatile K-protoypes algorithm yielded more insightful information due to its ability to handle catagorical data.


# [Predicting Hotel Cancellations](https://github.com/calvinchoi21/predicting-booking-cancellations)

The purpose of this project is to predict whether a given booking at a hotel would be cancelled in the future. This is accomplished by training classification algorithms on a set of features to choose between two classes in the target feature (1 for cancelled and 0 for not cancelled). Cancellations can lead to a loss in revenue for hotels making it a worthwhile endeavour to predict whether a given booking is likely to cancel. 

Five classifiers (three base, two ensemble algorithms) all from different categories are initially tested. Based on the scoring, one base and one ensemble algorithm will be fine-tuned and tested on a subset of data set aside to simulate future, unseen data. Due to the heavy presence of categorical features in this dataset, this project places equal emphasis on data preprocessing as it does with the predictive modelling component.


# [Predicting Customer Churns with Classification Algorithms](https://github.com/calvinchoi21/predicting-customer-churn/blob/master/Classification_Customer_Churn.ipynb)

The purpose of this project is to predict whether a telco customer will leave the company, i.e. churn, by utilizing supervised learning in the form of classification. An example of why a company would employ this task is to identify exisiting customers that are likely to churn so that resources such as promotional material be allocated appropriately in an effort to retain them.

For this task, six classification algorthims are initially considered using cross-validation on the training set. Of those six, three are shortlisted for further modelling. For each of those models, the hyperparameters are tuned and the validation set is used to test the performance increase from the tuning. After a model is tuned, a precision and recall trade-off that is appropriate for the task is chosen for it. The final models are then tested on the validation set to compare performance. Finally, the models are tested once more on unseen data via the test set to determine the best performing model.
