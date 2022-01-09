# Wine-Quality-Prediction

1. [Project Motivation](#ProjectMotivation)
2. [Installation](#installation)
3. [Data](#data)
4. [Implementation](#model)
5. [Results](#results)

## 1. Project Motivation <a name="ProjectMotivation"></a> 

- Building a model using Ensemble Techniques and choosing the best performing model to predict the quality of Wine

## 2. Installation <a name="installation"></a>

- [Jupyter Notebook](https://jupyter.org)
- Libraries :
  - pandas
  - matplotlib
  - seaborn
  - Scikit-learn
     - model_selection 
     - ensemble
     - AdaBoostClassifier
     - GradientBoostingClassifier
  - xgboost
 
## 3. Data<a name="data"></a> 
- [Dataset](https://github.com/piyushkumar08/Wine-Quality-Prediction/blob/main/winequality-red.csv) is related to red variants of Portugese "Vinho Verde" wine having 1599 records. 
- Attribute information:
    - fixed acidity
    - volatile acidity
    - citric acid
    - residual sugar
    - chlorides
    - free sulfur dioxide
    - total sulfur dioxide
    - density
    - pH
    - sulphates
    - alcohol
   Output variable (based on sensory data): 
    - quality
  

## 4. Implementation <a name="model"></a> 
- Preprocessing of 'quality' feature from 6 to 3 different classes
- EDA
- Checking Correlation b/w all the features 
- Extraction of Dependent and Independent variables 
- Applying Crossvalidation technique to get training and testing data 
- Modelling on training data
    - Ada Boosting, Gradient Boosting and XGboosting are performed and accuracy scores are recorded
    - Boosting is also done on feature-filtered data and accuracy for that is also recorded      

## 5. Result<a name="results"></a>
The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones). Outlier detection algorithms could be used to detect the few excellent or poor wines
Gradient Boost technique is performing the best for this dataset having 70% testing accuracy.
The details of the results - [Wine.ipynb](https://github.com/piyushkumar08/Wine-Quality-Prediction/blob/main/Wine.ipynb)
