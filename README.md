# Exploratory-Data-Analysis-EDA-Features-Engineering

## Exploratory Data Analysis
Technically, The primary motive of EDA is to

- Examine the data distribution
- Handling missing values of the dataset(a most common issue with every dataset)
- Handling the outliers
- Removing duplicate data
- Encoding the categorical variables
- Normalizing and Scaling

## Steps:
### Step 1
- First, we will import all the python libraries that are required for this, which include NumPy for numerical calculations and scientific computing, Pandas for handling data, and Matplotlib and Seaborn for visualization.

### Step 2
- Then we will load the data into the Pandas data frame.

### Step 3
- We can observe the dataset by checking a few of the rows using the head() method, which returns the first five records from the dataset.

### Step 4
- Using shape, we can observe the dimensions of the data.

### Step 5
- info() method shows some of the characteristics of the data such as Column Name, No. of non-null values of our columns, Dtype of the data, and Memory Usage.

### Step 6
- We will use describe() method, which shows basic statistical characteristics of each numerical feature (int64 and float64 types): number of non-missing values, mean, standard deviation, range, median, 0.25, 0.50, 0.75 quartiles.

### Step 7
Data visualization
- Univariate analysis
- Bi-variate analysis
- Multivariate analysis

### Step 8
Handling missing values in the dataset.
- Drop the missing values – If the dataset is huge and missing values are very few then we can directly drop the values because it will not have much impact.
- Replace with mean values – We can replace the missing values with mean values, but this is not advisable in case if the data has outliers.
- Replace with median values – We can replace the missing values with median values, and it is recommended in case if the data has outliers.
- Replace with mode values – We can do this in the case of a Categorical feature.

### Step 9
- Handling the outliers in the data, i.e. the extreme values in the data. We can find the outliers in our data using a Boxplot, IQR(Interquartile Range Method).

### Step 10
Encoding the categorical variables
- one-hot-encoding
- label encoding
- mean encoding

### Step 10
features selections:
- ANOVA
- Chi2 test
- We can find the pairwise correlation between the different columns of the data using the corr() method. (Note – All non-numeric data type column will be ignored.)

### Step 11
- Normalizing and Scaling – Data Normalization or feature scaling is a process to standardize the range of features of the data as the range may vary a lot. So we can preprocess the data using ML algorithms. So for this, we will use StandardScaler for the numerical values, which uses the formula as x-mean/std deviation.












