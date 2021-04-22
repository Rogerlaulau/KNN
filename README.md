# KNN

# There are 2 classification tasks using K-Nearest Neighbor (KNN)

# A dummy dataset on weather and temperature is created and used for classifying whether to play outdoors.

- Firstly, need to do the label encoding as data is string and cannot be understood by machine, so transform labels into numbers for both feature weather and temperature as well as the label (play or not).

- Secondly, combine multiple columns or features into a single set of data using "zip" function.

- Thirdly the k value which is n_neighbors for the KNN classifier which is a package from scikit learn.

- Lastly, train the model by fitting features and label into it and evaluate the model accuracy.


## Wine dataset

To classify the type of cultivar of the wine based on the following 13 features using KNN with different K values.
Since the value of K result in different accuracies, a better K value could be concluded for this wine case.

The dataset comprises 13 features ('alcohol', 'malic_acid', 'ash', 'alcalinity_of_ash', 'magnesium', 'total_phenols', 'flavanoids', 'nonflavanoid_phenols', 'proanthocyanins', 'color_intensity', 'hue', 'od280/od315_of_diluted_wines', 'proline') and a target (type of cultivars).This data has three types of cultivar classes: 'class_0', 'class_1', and 'class_2'. The goal is to classify the type of cultivar.


### Note
- KNN performs better with a lower number of features than a large number of features.
- KNN takes time since it needs to scan all data points for the Euclidean distance.
