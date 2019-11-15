# Classification Analysis on Adult Census Income from Kaggle

## Contributors:
- Ramachandra Gopal Posina
- Akhil Morampudi
- Mahanth Mukesh Dadisetty
- Bharadwaj Aryasomayajula
- Dinesh Deshi

## Domain:
Census Bureau : https://www.census.gov/academy  
  
## Objective:

An individual’s annual income results from various factors. Intuitively, it is influenced by the individual’s education level, age, gender, occupation, and etc.
In this project report we have a summary of our analysis and exploration of the Adult Census Data to come
up with meaningful, important and interesting attributes of the data. Further, after having sufficient
knowledge about the attributes we have performed a predictive task of classification, whether income
exceeds $50K/yr. based on this data.
In our project, we worked on the Census data set. In our initial stages, we preprocessed the data and
developed understanding of the data and its useful features that explain the variances by doing various
types of exploratory analysis. Later, we moved on to a classification task of predicting whether the income
is >=50k/year from a person’s attributes, by using important features. For the classification task, we
implemented various machine learning models, that after the initial task would prove useful. After
implementing various machine learning models, we compared their results on the training and the test
set to arrive at a model that works best for the predictive task on both test and training data set with 87%
accuracy. 
We are interested to learn how well we can  predict whether an individual’s annual income exceeds $50,000 using the set of variables in this data set. The question is inspected in two different approaches – traditional statistical modeling and machine learning techniques. Logistic regression is used as the statistical modeling tool as the outcome is binary.
The goal of this project is to make prediction analysis to determine whether a person makes over $50K a year by applying the machine learning classification algorithms.

## Data and Source Description
#### Dataset : Adult Census Income from Kaggle
#### Source of the Data :  
https://www.kaggle.com/uciml/adult-census-income

This data was extracted from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). The prediction task is to predict whether income exceeds $50k per year based on the provided. census data provided above. The Datasets consists of a list of records , each of which explains various features of a person along with his income per year. 

<b>A brief description of the features are as follows:</b>  
<b>Target:</b>  
income : >50K, <=50K  
  
<b>Predictors:</b>  
age: continuous
workclass: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked  
fnlwgt: continuous  
education: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool  
education-num: continuous  
marital-status: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse  
occupation: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces  
relationship: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried  
race: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black  
sex: Female, Male  
capital-gain: continuous  
capital-loss: continuous
hours-per-week: continuous
native-country: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands  
  
## Application of the CRISP-DM Process
   - Data Understanding Phase
   - Data Preparation Phase
   - Modeling Phase
   - Evaluation Phase
   - Deployment Phase

## Data Understanding and Data Preparation

Data Pre-Processing and Exploratory Data Analysis has been performed on the data and below are the observations

1. The no of records having income less than 50k dollars is more than the no of records having income more than 50k dollars income. The dataset neeeds to be balanced with the target values so that the models do not overfit the data.
2. The capital.gain and capital.loss values contain zeroes ,so these columns can be dropped.
3. Scatter plots and bar plots are plotted to find the distribution of various values of categorical values.
4. Hours.per.week has a value of 40 in most of the records, so this field can be dropped.
5. The fnlwgt values are moslty in the range of 0-40,000 and are of age 20 to 40.
6. The outliers are present in some of the contiuous variables which need to the handled properly.
    
    
## Machine Learning

1.Performed Logistic Regression on the model and calculated the performance metrics of the model and computed the scores 
    
    
## Evaluation
    [Work in progress]  
    
## Conclusion
Finally from the dataset we predict whether a person makes over $50K a year or not.
