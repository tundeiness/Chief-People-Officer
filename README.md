# Chief-People-Officer

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
- Using 4 algorithms:  𝐿1 L1, -Regularized Logistic,  𝐿2 L2, Regularized Logistic, Random Forests, and Boosted Trees.
#### Exercise 3.1: Code Checkpoint
- generate noisy conditional dataset.
- reshape generated noisy conditional dataset.
- Fit and plot an L1-regularized logistic regression on
  noisy conditional dataset with  𝐶=0.5

#### Exercise 3.2: Random Forest Classifier
- import Library
- create an instance of Random Forest Classifier
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
- Area under ROC curve (AUROC)

#### Exercise 4.1: Splitting Dataset
#### Exercise 4.2 - Build Model Pipelines

#### Exercise 4.3 - Declare Hyperparameter Grids

#### Exercise 4.4 - Fit and Tune Models with Cross-Validation












# Machine Learning Engineer Nanodegree
# Model Evaluation and Validation
## Project: Predicting Boston Housing Prices

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has the above packages and more included. 

### Code

Template code is provided in the `boston_housing.ipynb` notebook file. You will also be required to use the included `visuals.py` Python file and the `housing.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in `visuals.py` is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
ipython notebook boston_housing.ipynb
```  
or
```bash
jupyter notebook boston_housing.ipynb
```
or open with Juoyter Lab
```bash
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/housing/).

**Features**
1.  `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**
4. `MEDV`: median value of owner-occupied homes


# Supervised Learning (cd0025)

 Content for Udacity's Supervised Learning curriculum, which includes project starter files.

 <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. Please refer to [Udacity Terms of Service](https://www.udacity.com/legal) for further information.