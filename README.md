# customer-classification-banking
Classify whether a customer belongs to a high net worth or low net worth group and offer discounts on the commission for trading transactions.

**Project Description**
**Company Introduction**
Your client for this project is a retail banking institution.

  They are going to float a stock trading facility for their existing customers.
  The idea is to use data to classify whether a customer belongs to a high net worth or low net worth group.
  They will have to incentivize their customers to adopt their offerings.
  One way to incentivize is to offer discounts on the commission for trading transactions.
  
**Current Scenario**
The company rolled out this service to about 10,000+ of its customers and observed their trading behavior for 6 months and after that, they labeled them into two revenue grids 1 and 2.

**Problem Statement**
The current process suffers from the following problems:

  One issue is that only about 10% of the customers do enough trades for earnings after discounts to be profitable.
  The company wants to figure out, which are those 10% customers so that it can selectively offer them a discount.

**Task**
  You are given datasets of past customers and their status (Revenue Grid 1 or 2).
  Your task is to build a classification model using the datasets.
  You need to build the best possible model.
  
**Project Deliverables**

Deliverable: Predict whether a customer belongs to a high net worth or low net worth group.
Machine Learning Task: Classification
Target Variable: Status (high net worth (1) / low net worth (2))
Win Condition: N/A (best possible model)

**Evaluation Metric**

The model evaluation will be based on the F1 Score score.

**Data Description**
  We are provided with a dataset containing all the necessary information about the customers like their occupation, family income, gender, region, balance transfer, children, etc.
  Also included in the dataset is the column Revenue_Grid which classifies the customers into high net worth customers (1) and low net worth customers (2).
  This is the data that we have to predict for future customers.

The dataset is divided into two parts: Train, and Test sets.

**Train Set:**
The train set contains 8124 rows and 32 columns. The last column Revenue_Grid is the target variable.

**Test Set:**
The test set contains 2031 rows and 31 columns. The test set doesn’t contain the Revenue_Grid column. It needs to be predicted for the test set.
