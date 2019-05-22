# Machine Learning Exam project

### Group members: Ali Raza Khan, Mohammed Murad Hossain Sarker, Rasmus Balder Nordbjærg, Yakubu Adeyemi Oseni

### Business question

We want to perform sentiment analysis based on text data. More specifically the dataset is a collection of job reviews made by employees at following large tech companies: Amazon, Microsoft, Apple, Google, Facebook, Netflix. We want to create a model which based on text data from a review will be able to predict whether the review was positive or negative.

### About the dataset

https://www.kaggle.com/petersunga/google-amazon-facebook-employee-reviews

The dataset was originally dowloaded from Kaggle at above link but by some reason the dataset has now been deleted from the website.
The data was originally obtained by webscraping the job and recruiting site Glassdoor.com. The reviews already contain an overall rating from 1-5 stars so we could use this as label values.

### About the files

The main ML parts will be found in "*ml_solution.ipynb*"

Our downloaded version of the Kaggle dataset is stored in "*employee_review.csv*".

Before working with the data we had to do some heavy data preparation so we seperated this code into its own notebook: "*data_preprocessing.ipynb*". The result of this data preparation is stored in "*all_processed.csv*".
