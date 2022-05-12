# Pre-Processing of COVID-19 data in Piauí

In this class we learn about pre-processing of data; <br>
Some tasks we performed: Handling missing data, Handling categorical data, Splitting data into training and testing and Feature Scaling.

#### Handling missing data
We decided to take the two variables with fewer data (city, confirmed_by_100k_inhabitants) and perform the dropna with the subset with the two mentioned variables to deal with missing data.

#### Handling categorical data
To transform the variables into categorical, we use the LabelEncoder from sklearn.preprocessing package.

#### Splitting data into training
To split the data into training and testing, we use train_test_split() and 20% of the data for validation.

#### Feature Scaling
For training and standardizing test data, we use StandardScaler() from sklearn.preprocessing package.
It is interesting to perform this standardization to verify if the model reaches a higher accuracy.
