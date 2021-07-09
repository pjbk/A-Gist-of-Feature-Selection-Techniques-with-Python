A Gist of Feature Selection Techniques in Python

Top reasons to use feature selection are: It enables the machine learning algorithm to train faster. It reduces the complexity of a model and makes it easier to interpret. It improves the accuracy of a model if the right subset is chosen. [3] Feature Selection is one of the core concepts in Data Science & Machine Learning which have hugely impact the performance of a model. The data features that are used to train machine learning models have a huge influence on the performance. The problem we often face is to identify the related features from a set of data and removing the irrelevant or less important features with do not contribute much to our target variable in order to achieve better accuracy for our model. [1]

In this notebook, I have sheded some light on some useful feature selection techniques simply you can use in Machine Learning. I used Python programming language in this case with sklearn.

Feature Selection Methods

Here, three feature selection techniques that are easy to use and also gives good results will be discussed.

Feature Correlation Matrix [.corr()],

Univariate Selection [SelectKBest with chi²],

Feature Importance [.feature_importances_]

Let’s explore these techniques one by one with an example dataset, "Breast Cancer Risk Prediction". You can download the dataset from HERE. The dataset contains 32 features, but here I will try to select top 10 important features from the dataset.


Dataset Description

The Breast Cancer datasets is available UCI machine learning repository maintained by the University of California, Irvine. The dataset contains 569 samples of malignant and benign tumor cells.

The first two columns in the dataset store the unique ID numbers of the samples and the corresponding diagnosis (M=malignant, B=benign), respectively. The columns 3-32 contain 30 real-value features that have been computed from digitized images of the cell nuclei, which can be used to build a model to predict whether a tumor is benign or malignant.

1= Malignant (Cancerous) - Present (M),

0= Benign (Not Cancerous) -Absent (B)

Ref.

https://towardsdatascience.com/feature-selection-techniques-in-machine-learning-with-python-f24e7da3f36e?gi=d00ef7465ca2 |

https://medium.com/@nmscott14/3-feature-selection-methods-e7ccd6dbf316 |

https://www.analyticsvidhya.com/blog/2016/12/introduction-to-feature-selection-methods-with-an-example-or-how-to-select-the-right-variables/

For more exciting notebooks visit my Kaggle workspace! [ https://www.kaggle.com/pankajbhowmik ]
