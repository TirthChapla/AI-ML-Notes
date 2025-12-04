# Machine Learning Development Life Cycle (MLDLC)

---------------
- It is divided into 9 steps. 

## 1. Frame the Problem 

- ***Here we decide which type of problem is we are solving.***
  - The Problem is Supervised or Un-Supervised.
  - It will work online or offline
  - Roughly Estimation of Cost and Time.

## 2. Gathering Data

- The Data we get : 
  - .csv
  - API to required .csv
  - Web scrapping (the data present in website)
  - DataBase 

## 3. Data Pre-Processing


- Remove Duplicate , missing values , Quantifiers
- Scaling the value and Standardization.

## 4. EDA : Exploratory Data Analysis

- We understand the Data.
- We do experiments with the data. 
- Find the relations between the data internally.
- we do Visualization / Plot the Graphs.
- Imbalance Data set handling (Dog vs Cat analysis : we have more images of the Dogs compare tho the Cat).

## 5. Feature(Input) Engineering and Selection

- ***Engineering*** : We create changes in the data so that the analysis becomes easy.
- ***Selection*** : The columns which are not affect the model we try to remove them.


## 6. Model Training , Evaluation and Selection

- Here we try to bring each and every model and apply it.
- So, that we decide finally which model we have to use.
- ***Evaluation*** : This tests how our model is working.
- ***Selection*** : After selection the model we try to tune(Setting of model) accordingly to us. so that is providing best output.


## 7. Model Deployment 

- At this moment, our model is working.
- We try to deploy it into the mobile, website...

- we convert our model into binary file.
- That binary file is converted into the API (Which gives us JSON output)


## 8. Testing 

- we try to do the A/B testing 
- We test the mode on the selected members.


## 9. Optimize

- Now we open the product for all the customers.
- Before that,
  - We take the Backup of model
  - Backup of the data.
  - If our model gets blast / error, then we can roll back and back to the live. 
  - We do the Load balancing.
  - Rotting (Re-training the model)