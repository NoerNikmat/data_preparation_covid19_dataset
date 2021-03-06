# Data preparation for Machine Learning Model

##### Novel Coronavirus COVID-19 Dataset

Original dataset, name, and data definitions/structures
    Source : https://github.com/MohammadFebriyanto/Bangkit_Project/tree/master/DATA

###### File Dataset

    patient.csv                 22 columns  (Main File)
    time.csv                    24 columns  
    route.csv                    7 columns
    case.csv                     8 columns
    trend.csv                    5 columns
    TotalCaseConvir_INA.csv      2 columns  (dataset file for country: Indonesia)

## The steps to do data preparation are as follows

#### Import Library
- Pandas and Numpy used data analysis and manipulation tools and computation.
- Matplotlib and Seaborn used to visualization data.
- Math used to mathematical functions defined by the C standard.

#### Load the dataset
used to read the data frame.

#### Find information and insights from the dataset.

#### Missing Value
Identify and handling missing values for data training and data test.

#### Create New Features
In COVID-19 data, date and range of age can be metrics for approving confirmed cases. New features often referred to as interaction terms.

#### Aggregating Numerical Variable
In such a scenario, limiting the count of these labels can be a solution. In the data, the variable 'infection_reason' has several numerical (numerical_infection), which can be displayed.

#### Log Transform
Log transform did quantile capping of the income variable and also done logarithmic transformation to treat extreme values. That had represented with confirmed_date_transform.

#### Split the dataset into Training Set and Test Set (80/20) 

#### Modeling for optional.

## Result or Insight Data Preparation

1. Based on this result, we conclude that older people are with an age range of 80 to 90 years more susceptible to coronavirus than younger people. And the number of Female patients is more than Male Patients. The graph is displayed more persuasively than before.
2. The most reason why people get infected by a coronavirus is direct contact with another patient and visit Daegu. Output data results in numerical form.
3. Handling in missing value can provide optimized performance on the preparation data, especially on the target variable.
4. The main difference from all of them is the use of Log Transform for positive skewness. That is when the tail on the right side of the distribution is longer. With the Log Transform method, the goal value is to reduce the slope.

## Data Visualization

**Handling Missing Values**

![misval](data_prep/misval.png)
---

**Aggregate dates**

![aggdate](data_prep/aggdate.png)
---
**Optimize data to be easily understood**

![agerange](data_prep/agerange.png)
---
**Numerical number of confirmed based on infection reason**

![num](data_prep/num.png)
---
**Handling Skewness**

![skew](data_prep/skew.png)
