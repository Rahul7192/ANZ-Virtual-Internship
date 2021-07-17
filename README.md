# ANZ-Virtual-Internship: Project Overview

* This task is based on a synthesised transaction dataset containing 3 months’ worth of transactions for 100 hypothetical customers. It contains purchases, recurring transactions, and salary transactions.

* The dataset is designed to simulate realistic transaction behaviours that are observed in ANZ’s real transaction data, so many of the insights you can gather from the tasks below will be genuine.

## Resources
  * Python Version: 3.7

  * Packages: pandas, numpy, matplotlib, seaborn,sci-kit learn

  * Project Basis: Virtual Internship with ANZ


## Data Preparation and Customer Analytics
This consisted of the following stages:

  * Examined transaction data looking for inconsistencies, missing data and outliers.

  * Cleaned the data using ordinal mapping and filling of missing values and outliers with statistical best fit values.
  * Visualize the relationship between categorical variables with continuous variable.

#### Counting of transction of each month according to date with respect movement & status of card
![ANZ1](https://user-images.githubusercontent.com/72228043/126024943-f3342144-2c68-41f4-a524-36f505dbeb84.PNG)

#### Top Customers for various months below:

* August

![ANZ2](https://user-images.githubusercontent.com/72228043/126024996-8fcf4b0d-a73e-4626-93ce-e498a04bae2c.PNG)

* September

![ANZ3](https://user-images.githubusercontent.com/72228043/126025024-85b5bba8-c3d4-4920-a119-9d0efe413abc.PNG)

* October


![ANZ4](https://user-images.githubusercontent.com/72228043/126025036-44141b91-c865-4b20-b0bb-9c703a114eb7.PNG)


## Model Prediction:
* Machine Learning Algorithms used to predict the salary of various customers.
  * Linear Regression
  * Deceision Tree

* Exploring the co relation between annual salaries and various customers attributs as below:
  * Gender
  * Age
  * Balance
  * Amount
  
![ANZ7](https://user-images.githubusercontent.com/72228043/126025351-63656c17-975a-483f-9c18-97e2e8bfb3cc.PNG)

### Model Summary:
We predicted the salary of various customers using Linear Regression and Deceision Tree

![Capture8](https://user-images.githubusercontent.com/72228043/126025441-2146899b-57c4-4833-9a66-03e86b04a8ef.PNG)


* Model Accuracy:
  accuracy on train data 0.9980306118489595
  accuracy on test Data 0.9975505932575178





