# Practice for 5511 Deeplearning : Text Mining for Amazon Musical Instruments Reviews


*June 2023*


### **Problem Statement**

The objective of this project is to perform Sentimental Analysis for the customer review data. Help the organization to understand better about their customer feedback's So that they can concentrate on those issues customer's are facing. Build the model which has highest accuracy in classifying the feedback as positive,Negative and neutral.

### **Data Source:**

https://www.kaggle.com/datasets/eswarchandt/amazon-music-reviews


The data set includes 10261 records, including columns: reviewer ID , User ID, Reviewer Name, Reviewer text, helpful, Summary(obtained from Reviewer text),Overall Rating on a scale 5, Review time
Description of columns in the file:

| **Column Name** | **Description**                               |
|-----------------|-----------------------------------------------|
| reviewerID      |  ID   of the reviewer, e.g. A2SUAM1J3GNN3B    |
| asin            |  ID of the product, e.g. 0000013714           |
| reviewerName    |  name of the reviewer                         |
| helpful         |  helpfulness rating of the review,   e.g. 2/3 |
| reviewText      |  text of the review                           |
| overall         |  rating of the product                        |
| summary         |  summary of the review                        |
| unixReviewTime  |  time of the review (unix time)               |
| reviewTime      |  time of the review (raw)                     |


### **Methodology**

RNN will be built for this project.  

By completing this project, we hope to enhance our knowledge of RNN and its applicability in real-world scenarios.

### **Detail steps** 


**1. Exploratory Data Analysis (EDA)** 

Firstly we will explore and visualize the data to understand the structure and distribution of the data.  

**2. Model Training & Evaluation**

Next, we will build RNN with training data set and check the performance on photo dataset. 
Different architecture such as LSTM & GRU will be tried.


**3. Conclusions**

Finally, we will summarize the results and see what can be improved in the future. 
