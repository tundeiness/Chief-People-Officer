# Project: Chief-People-Officer

The client is the HR department. of a large software company. The department is rolling out a new initiative called proactive retention. The idea is to use data to predict whether an employee is likely to leave. Once these employees are identified, HR can be more proactive by reaching out to the disgruntled employees before it's too late. 

For this initiative they only care about permanent i.e non-temporary employees. Currently the employee retention process is very retrospective. Once an employee leaves, he/she takes an exit interview stating reason for leaving. HR then tries to learn insight from the interview and make changes around the company accordingly.   

I have been hired by the HR department to build a model to predict the probability that a current employee would leave. I have been given data of past employee of the company and their status. The task is to build a classification model using this dataset. This solution will compliment the existing approach because there is no precedent. 

## Specifics
- Deliverables: An executable model script
- Task : Classification
- Target Variable: Status(Employed/Left)
- Input Features: As seen in the dataset
- Win Condition: NA (best possible model)


## Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Jupyter Notebook](http://jupyter.org/install.html)



### Data
Employee data in csv format.

**Features**
1.  `avg_monthly_hrs`
2. `last_evaluation`
3. `satisfaction`

**Target Variable**
4. `Status`


### Module one: Exploratory analysis Plus
- Explored basic information about the dataset.
- Plotted distributions of numeric and categorical features.
- Segmented dataset by 'status'.
- Explored bivariate segmentations.


### Module Two: Analytical base Table Construction
- cleaning & dropping irrelevant observations from the dataset.
- fixing various structural errors, such as wannabe indicator variables.
- handling missing data.
- Feature engineering leveraging exploratory analysis.
- creating dummy variables before saving the ABT.
 #### Exercise 2.1: Drop unwanted observations
 - drop duplicates using drop_duplicates
 - remove unwanted data in department feature

 #### Exercise 2.2: Fix Structural Errors
- Fill missing values with 0
 #### Exercise 2.3: Handle missing data
 - Check dataset for missing data
 - Label Missing values
 - Fill in original missing values

  #### Exercise 2.4: Handle missing data
 - Engineer Features
 - Exploratory analysis as a basis for re-engineering
   #### Exercise 2.5: Handle missing data
   - Saving the ABT
   - convert target variable into an indicator variable
   - convert other categorical features into dummy variables


### Module Three: Classification Algorithms

- key terminology for binary classification, such as "positive" vs. "negative" classes.
- regularizing logistic regression.
- applying settings for penalty strength.
- Using 4 algorithms:  ????1 L1, -Regularized Logistic,  ????2 L2, Regularized Logistic, Random Forests, and Boosted Trees.
#### Exercise 3.1: Code Checkpoint
- generate noisy conditional dataset.
- reshape generated noisy conditional dataset.
- Fit and plot an L1-regularized logistic regression on
  noisy conditional dataset with  ????=0.5

#### Exercise 3.2: Random Forest Classifier
- import Library.
- create an instance of Random Forest Classifier.
- Fit and plot a random forest with its default hyperparameter values and the random state 123.
- Tune the number of estimators included in the ensemble.
- fit and plot random forests that set a higher minimum leaf size. 

#### Exercise 3.3: Gradient Boosted Classifiers

- import Library
- Fit and plot a gradient boosted tree with its default hyperparameter values and the random     
  state 123
- tune the number of estimators.
- fit and plot boosted trees with different max depth values.


### Module Four: Model Classification
- Accuracy vs imbalanced classes
- True positive rate vs False positive rate
- Area under ROC curve (AUROC) as a more effective metric for classification.
  than simple accuracy.

#### Exercise 4.1: Splitting Dataset
- use sklearn model_selection library to split dataset into training and test sets.
#### Exercise 4.2 - Build Model Pipelines
- Set up model pipelines and hyperparameter grids using make_pipeline(), StandardScaler(), and other ML algorithm.
#### Exercise 4.3 - Declare Hyperparameter Grids
- declare hyperparameter dictionary for 'L1' and 'L2' logistic regression, random forest, gradient boosting tree.
#### Exercise 4.4 - Fit and Tune Models with Cross-Validation

- Tune models using cross-validation (GridSearchCV).
#### Exercise 4.5 - AUROC Review
- evaluate models by looking at their cross-validated performance.via best_score_, predict() and predict_proba().
- plot ROC.
- calculate ROC AUC scores.

#### Exercise 4.6 - Pick the Winner
- run A.U.R.O.C performance on each model in fitted model object
- Save winning model into a pickle file.


### Module Five: Project Delivery

#### Exercise 5.1 - Confirm your Model
- load analytical base table and apply the model to it.
#### Exercise 5.2 - Write Pre-Modeling Functions
- compile data cleaning and feature engineering into functions.

#### Exercise 5.3 - Construct Custom Model Class
- compile data cleaning and feature engineering functions into a single class. 
#### Exercise 5.4 - Deploying Models: Method 1: Jupyter Notebook
- apply model to raw data in Jupyter Notebook.
#### Exercise 5.5 - Deploying Models: Method 2: Executable Script (Pptional)
- run scripts via the machine terminal.













 <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. 