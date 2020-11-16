## Data comprehension
- is the target cont or categorical?

- figure out what a row represecnt? event, person, geo location etc

- comprehend all the feature

## 1. Data Clean
* Shape--- to find the # of obs and features
* Info ---- preview the columns and number of obs in each column
- Missing values -- no missing values
- Data types --- all floats and ints, no objects
-Outliers
-Duplicates
- Check for data integrity (any filler characters or values)--- too large obs, operands or characters in place of dayta
## 2. Data Preparation
- drop 'Unnamed' column

- replace white spaces in column names


## 3. EDA
- see if there are relationships between variables that can be used to create additional variable
    
    - categories of variables and see if the distributions clump in specific ways
        -if so, bin them
    
    - look at scatterplots of cont variables
        -if there are groupings in those catter plots, bin the categoriacal variables
        - if there are trends, we can create additional variables that specify the relationship
            - if we see an expoenetial curve, we can create a new variable taking the log, etc
            
            
## 4. Modeling
- split into train/test sets

- Because the target is a categorial variable. pick classification models to run
  - logistic regression
  - knn

-Run cross_validation process for initial models for each of the models for each of the above to get a basliune for how the models do
  - run cross_val procedure on X_train and y_train
  - generate preds on train set, metrics.....
  - generate metrics on predictions against actual values
    - accuracy? Why not? (here just for you to think about)
    - look at recall, because we want to select the models that do best at minimizing the negatives
    
  - generate both training and testing metrics through

## 5. Final Analysis Interpretation











