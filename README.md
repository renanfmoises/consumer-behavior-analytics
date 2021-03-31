<picture>
<img src="/images/cbanalytics.png" width="900" height="450">
</picture>

# Consumer Behavior Analytics

<small>
<p style="text-align:right;">Last update: March 31, 2021</p></small>

<small>**To view notebooks go to the following directory:**</small>
<br>
[<small>/notebooks</small>](https://github.com/renanfmoises/consumer-behavior-analytics/tree/master/notebooks)
_____________________________
## Schedule

## DATA CLEANING

- Check primary key integrity
- Check for duplicates
- Remove unimportant variables
- Check for missing values
- Check and handle outliers:
    - in numerical variables;
    - in categorical variables (with absurd values);
- Save dataset into a new csv file, cleaned


## DATA ANALYSIS
#### Exploratory Data Analysis
- Feature Engineering: discretizing and combining some variables;
- Investigation on `AcceptedCmp`s variables;


## DATA MODELLING
- Data Preparation
- Data Scaling:
    - RobustScaler for features with outliers
    - StandScaler for all other features
- Modelling Customers dataset with whole data:
    - LogisticRegression - Baseline
    - LogisticRegression - Tunned
    - KNeighborsClassifier
    - SVC
    - RandomForestClassifier
    - AdaBoostClassifier
    - GradientBoostClassifier
    - XGBoostClassifier
- Modelling Customers dataset with customers effectively exposed to the Marketing Campaing;
    - _same models as above, but different dataset._

## INTERPRETABILITY
### Schedule
- Best Model Analysis and Interpretability (with SHAP)

</small>
