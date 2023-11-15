# HR ANALYTICS PROJECT

## Problem statement:
Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

They first identify a set of employees based on recommendations/ past performance
Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion

For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle. 


They have provided multiple attributes around Employee's past and current performance along with demographics. 

Now, the task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

### DATASET DESCRIPTION:-

Here are some key details for the dataset:
    
    employee_id: Unique ID for each employee.
    
    department: The department in which the employee works.
    
    region: Region of employment (unordered).
    
    education: Education level of the employee.
    
    gender: Gender of the employee.
    
    recruitment_channel: Channel through which the employee was recruited.
    
    no_of_trainings: Number of other trainings completed in the previous year on soft skills, technical skills, etc.
    
    age: Age of the employee.
   
    previous_year_rating: Employee rating for the previous year.
   
    length_of_service: Length of service in years.
    
    KPIs_met >80%: Whether the percent of Key Performance Indicators (KPIs) is greater than 80% (1 for yes, 0 for no).
    
    awards_won?: Whether the employee won awards during the previous year (1 for yes, 0 for no).
    
    avg_training_score: Average score in current training evaluations.

Target Variable:

    is_promoted: The target variable indicating whether the employee is recommended for promotion (1 for yes, 0 for no).

Evaluation Metric:

    The performance of your predictions will be evaluated using the F1 Score.

### Evaluation Metric:-

The evaluation metric for this competition was F1 Score.

### Best Score:

XGBoostClassifier : 0.44