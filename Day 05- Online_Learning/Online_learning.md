# Day 5 : Online Learning 

- defined as the process of training a machine learning model incrementally by feeding it data in small batches or one at a time, allowing it to learn and adapt continuously over time.
- We here some were that when you use our modal, it will learn from the data and improve its performance.
- we train the modal incrementally.
- we feed the modal in small batches in sequence or one by one.
- Our modal get improve its performance after every new batch.
- we prefer to train the modal with small data at ONLINE(server side).
- this is done on the Production side.
- Ex : chatGPT, Google Translate, etc.


## When to use Online Learning ?

### 1. Where here id a concept drift :

- when the concept of data changes over time.
- Ex : we create the movie recommendation system for Netflix.
- Ex : stock price prediction.

### 2. Cost-effective :

- when we have limited computational resources.
- Ex : we have a mobile app, and we want to implement the ML model on it.

### 3. Faster Solution :

- when we need a quick solution.
- Ex : fraud detection in banking.


## How to implement Online Learning ?


- sklearn have Linear_modal
  - SGDClassifier()
    - it contains fit() and partial_fit()
      - partial_fit() is used for online learning.



- River Library : 
- pip install river
- it is used for online learning.
- it contains many algorithms for online learning.
- We will see in the future.

- Vowpal Wabbit :
- it is used for online learning.
- it is used for reinforcement learning.
- it is developed by Microsoft.
- it is used for large-scale machine learning.
- we will see in the future.



## Learning Rate : 

- it is important to set the learning rate.
- if we set the learning rate too high, the model may converge too quickly and forget the previous data.
- if we set the learning rate too low, the model may take too long to converge and may not learn from the new data.
- we have to set the learning rate in such a way that it should not forget the previous data and should learn from the new data.


## Out of Core Learning :

- it is a technique used to train machine learning models on large datasets that do not fit into memory.
- it is used in online learning.
- it is used to process data in small batches.
- it is used to train the model incrementally.
- it is used to reduce the memory usage.
- it is used to improve the performance of the model.
 


## Dis-Advantages of Online Learning :

### 1. More Complex Implementation :
- it is more complex to implement than batch learning.
- it requires more careful tuning of hyperparameters.
- it requires more careful monitoring of the model's performance.

### 2. Risky :
- if the new data is noisy or contains outliers, it can negatively impact the model's
- performance.


![img.png](img.png)