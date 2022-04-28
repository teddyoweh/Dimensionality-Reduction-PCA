# Dimensionality Reduction PCA

 Dimensionality is refered to the attribute or features of a dataset
 

 
#### Dimensionality reduction is basically a process of reducing the amount of random features,attributes variables or in this case called dimensions in a dataset  and leaving as much variation in the dataset as possible by obtaining a set of only relevant features to increase the effiency of a model.



# Importance of Dimensionality Reduction

When running models or training models machine Learning not all the dimensions of a datasets are relevant, and to make you a model train in a less time and more effienct dimensionality reduction should be carried out on a dataset to remove the irrelevant datasets. It avoids overfitting of a dataset because, when attributes or dimensions are many, the model tends to become complex and overfit on the training data. Also useful when visualizing data

#### Two approaches are either keeping the most important features and removing the rest and .. combination of features to reduce the dimensions


# Feature Extraction and Feature Selection? 
Feature selection removes irrelevant features from a dataset.
Feature extraction  makes new features from existing ones.

### Both dimensionality reduction processes.


# Why feature selection is important?
Feature selection is rather important because it is an effiecient method of dimensionality reduction by removing irrelevant features. It also builds an accurate model with better prediction power and overfitting by selecting only relevant features.


# Wrapper-based feature selection
In wrapper methods, it is based on a specific machine learning algorithm.
It evaluates all the features of a dataset and gives optimal results of the various combinations of features.

Some methods are 

### Forward Selection
This process starts off with no feature then keeps features which improves the model the best till when a new feature doesn't improve the model

### Backward Elimination
This process removes the least significant feature which improves the performance of the model.


# Filter-based feature selection
In this process the features Dimensionality reduction is a machine learning (ML) or statistical technique of reducing the amount of random features,attributes variables or in this case called dimensions in a dataset by obtaining a set of only relevant features to increase the effiency of a model. are selected based of their results in statical tests



# Embedded-based feature selection
This process combines both the Wrapper and Filter based selection methods. It tests both methods,generate a combination of features and selection the best of the methods that improves the models performance
