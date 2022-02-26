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