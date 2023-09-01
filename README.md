# What drives the price of a car?

This data study examines a vehicle dataset and derives the factors that influence the price of a car and provide recommendations to used car dealership.

## Description
From a business perspective, the goal of this data task is to identify the key factors that influence used car prices to make more accurate pricing predictions. This information can be used by businesses to make better decisions about pricing their own used cars, as well as to understand the factors that are driving the overall market for used cars.

## Getting Started :
To get started with this project, we need to have the following dependecies :
* Python 3.6+
* Jupyter Notebook
* Vehicle Dataset
* Python libraries such as NumPy,Pandas,Scikit-learn,matplotlib, seaborn.

### Data Understanding :

###### Taking following steps to understand the data :

Explore the data: Overview of the data, such as the number of records, the number of columns, and the data types of each column and would also look for any patterns or trends in the data.

###### Data Quality Issues :

Identify any missing values in the data.
Identify any duplicate records in the data.
Identify any outliers in the data and investigate them.
Check for any inconsistencies in data type and format of the data.

##### Data Preparation :
After our initial exploration and fine tuning of the business understanding, it is time to construct our final dataset prior to modeling. Here, we want to make sure to handle any integrity issues and cleaning, the engineering of new features, any transformations that we believe should happen (scaling, logarithms, normalization, etc.), and general preparation for modeling with sklearn.

###### Data Cleaning :
As part of data cleaning, the following activities have been carried out:

* Dropping unwanted columns such as id, VIN, size and state from the dataset and extracted important features.
* Dropping missing values for year, ransmission, fuel, odometer, model
* Filling missing values for other categorical features with 'unknown'
* Removing Duplicate Values
* Handling categorical values by mapping values outside certain range into 'others' 
* Removing outliers for based on IQR for price and odometer

###### Data Encoding:
The following encoding techniques were applied to the categorical variables:

Ordinal Encoding
One-Hot Encoding

### Data Visualization :

Visualizing data correlation using heatmap.

Plotting Manufacturer vs Price Distribution.

![image]
https://github.com/ashwinisanagoudar/MLApp-UsedCarPricing/blob/main/images/manufacturer_price.png

Visualizing box plot distribution of Condition vs Price.

![image]
https://github.com/ashwinisanagoudar/MLApp-UsedCarPricing/blob/main/images/condition_price.png

Plotting Fuel vs Price Distribution.

![image]
https://github.com/ashwinisanagoudar/MLApp-UsedCarPricing/blob/main/images/fuel_price.png

Plotting Model vs Price Distribution.

![image]
https://github.com/ashwinisanagoudar/MLApp-UsedCarPricing/blob/main/images/model_price.png