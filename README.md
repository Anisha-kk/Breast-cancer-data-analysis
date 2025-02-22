# Breast-cancer-data-analysis
This project performs Classification on Scikit-Learn [breast cancer dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html).
The classification is done using different models and their perfromance is compared.

## Data Understanding
**Number of Instances:** 569

**Number of Attributes:** 30 numeric, predictive attributes and the class

**Attribute Information:**

radius (mean of distances from center to points on the perimeter)

texture (standard deviation of gray-scale values)

perimeter

area

smoothness (local variation in radius lengths)

compactness (perimeter^2 / area - 1.0)

concavity (severity of concave portions of the contour)

concave points (number of concave portions of the contour)

symmetry

fractal dimension (“coastline approximation” - 1)

The mean, standard error, and “worst” or largest (mean of the three worst/largest values) of these features were computed for each image, resulting in 30 features. For instance, field 0 is Mean Radius, field 10 is Radius SE, field 20 is Worst Radius.

**class:**

WDBC-Malignant

WDBC-Benign

**Missing Attribute Values:** None

**Class Distribution:** 212 - Malignant, 357 - Benign

**Creator:** Dr. William H. Wolberg, W. Nick Street, Olvi L. Mangasarian

This is a copy of UCI ML Breast Cancer Wisconsin (Diagnostic) datasets. https://goo.gl/U2Uwz2

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.

## Results
The dataset was classified using Logistic Regression, Random Forest Classifier, Naive Bayes Classifier, Decision Tree Classifier, Support Vector Machine and Neural Network. The performance of Random Forest model is the highest with an accuracy score of 96% and recall score of 97%. 
