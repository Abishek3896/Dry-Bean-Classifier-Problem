# Dry-Bean-Classifier-Problem
An Explanatory Data Analysis would be done on the Dataset and also normalized by using box-cox power transformation in the preprocessing phase to be applied to the different classification algorithms for the accuracy and also identifying the differences between the algorithms. 

Brief about data:

Food authentication in the industries and global market, is always a big challege. Claim over grade and no adulteration with other varities, increases the price of the prdouct. This study tries to classifiy the dry beans in seven different varities on the basis of 16 different features.

Overview:

It is very important for checking out few boxes before going for data exploration or modeling,

Checking for missing values,
Checking Duplicates,
Checking the distribution of the data (multivariate normal is more suitable),
Outlier Detection (extreme value),
Checking for Colinearity.
Under preprocessing we checked all the peculiarities of the dataset and treated with suitable statistical solutions.

Pre-processing stages with the tools used,

Autoscaling with Standard Scaler,
Joint Normality/Multivariate Normality checking with Chi-square plot and Shapiro-Wilk's test,
Individual distribution checking with Histogram,
Box-Cox transformation for converting non-normal data into normal data,
Outlier detection with Mahalnobis Distance and PCA biplot for each class,
Perfect and Absolute Colinearity checking with rank of the matrix and pearson correlation-heat map.


Finally we went ahead with three types of data to check how modeling gets affected by the above pecuilarities
![image](https://user-images.githubusercontent.com/24876021/195545870-4fd47b0c-5c6d-427c-9c93-928f7612a9c9.png)
