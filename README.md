# Parameter-optimization-of-SVM
SVM, also known as Support Vector Machine, is a commonly used Supervised Learning algorithm that can be applied to solve both Classification and Regression problems. However, it is mainly utilized for Classification tasks in Machine Learning.

To enhance the accuracy of SVM, certain key parameters such as kernel, C, and gamma can be adjusted. This process is referred to as Hyperparameter Tuning.

Optimizing these parameters can be done using GridSearchCV in Python, which is a tool for finding the best hyperparameters.

In the Python file, a Fitness Function has been employed to optimize the parameters.

#DATASET
The dataset for the project has been downloaded from the UCI Machine Learning Repository.
https://archive.ics.uci.edu/ml/datasets/Dry+Bean+Dataset

Seven different types of dry beans were used in this research, taking into account the features such as form, shape, type, and structure by the market situation. A computer vision system was developed to distinguish seven different registered varieties of dry beans with similar features in order to obtain uniform seed classification. For the classification model, images of 13,611 grains of 7 different registered dry beans were taken with a high-resolution camera. Bean images obtained by computer vision system were subjected to segmentation and feature extraction stages, and a total of 16 features; 12 dimensions and 4 shape forms, were obtained from the grains.

Number of Instances:

13611

	
Number of Attributes:

17
