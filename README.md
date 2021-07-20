# Heart Disease Final Project

## Why we chose our topic 
We wanted to analyze data about heart disease to see if there was a way to predict who and who does not have heart disease based on certain criterias such as age, sex, cholestorol levels etc.
## Source of data
Our data (the Cleaveland Heart Disease dataset) was obtained from the UCI repository.
## Questions we hope to answer
With this data we hope to predict heart disease in patients and discover possible trends and coorelations with heart disease and certain criterias. 

## Data Exploration 
We first started by getting to know our data. We assessed how many rows and columns they were and looked for any null values. 
We discovered that there were null values in the "maj_vess" (major vessels) and "thal" (thalassemia) columns. 
## Preliminary preprocessing 
We dealt with those null values my taking the mean of the values in that column and replacing those null values with the mean.

## Machine Learning 
### Machine Learning Model
We chose to use a Random Forest as our machine learning model. We made this descision because we wanted to get the highest possibly accuracy score. In order to do this we also increased the number of trees from 10 to 100 which kept the accuracy score in the high 80s instead of the low 80s.
Our current accuracy score is 86.88%
// limitaions of random forest model
### Spliting the data
We split the data by cloning the clean data and dropping the target column in order to create the training set. We then created a variable for the target column only in order to create the testing set.

## Database
We used PgAdmin to create a database for our data and then imported the data from PgAdmin to our jupyter notebook file where are analysis was to be performed.

![ERD relationships](https://github.com/Cmarescot/Heart_Disease_Final_Project/blob/Circle/heart-disease-ERD.png)

## Dashboard 
For our final dashboard, we have chosen to use Tableau Story. We have 2 graphs from our data. One graph shows the variation of heart disease by age and the other shows the variation by gender. Our interactive element is a filter on the variation by age graph for the factor gender. The graphs are also color coded based on heart disease being present or not. The link to our dashboard can be found here: https://public.tableau.com/shared/MS36YCW7T?:display_count=n&:origin=viz_share_link.

## Google slide presentation
// link to google slide presentation 
