# motor-temp
To predict rotor temperature of a permanent synchronous motor

Train size:698649, 14
Test size:299421, 13

Data type: Float

Performed EDA and removed outliers in the data.

Checked correlation between the features and target variable. Multicollinear features were removed.
Normalized and dimension was reduced by PCA.

Models Used: Linear Regression, Random Forest Regression, knn Regression.

Random Forest Regression was choosen as it was giving error of 0.04.




