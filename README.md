# LIDAR - point cloud classification

The project aims to classify a point cloud. The data comes from airborne laser scanning (ALS) of a section of the city of Krakow and was downloaded from www.geoportal.gov.pl.

The points were classified into seven groups:

2 - points lying on the ground,
3 - points representing low vegetation, i.e., in the range of 0-0.40 m,
4 - points representing medium vegetation, i.e., in the range of 0.40-2.00 m,
5 - points representing tall vegetation, i.e., in the range above 2.00 m,
6 - points representing buildings, structures, and engineering structures,
7 - noise,
9 - points representing water areas.

The data also includes a group of unclassified points: 0 (points processed but unclassified), which was removed from the analysis. Several models were tested: Logistic Regression, Decision Tree Classifier, Naive Bayes, Random Forest Classifier, and a model based on neural networks. A model comparison and conclusions can be found in the Lidar.ipynb file.

