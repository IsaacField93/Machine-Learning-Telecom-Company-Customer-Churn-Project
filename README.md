### Introduction

For our Math for Machine Learning Project, myself, Qianyu Chen, and Christian Kolker analyzed and fine-tuned three machine learning models to predict customer churn for an anonymous telecommunications company.

After performing exploratory data analysis and visualizing data trends, we used fit logistic regression and XGBoost models to our data. We discovered that:

##### What is churn?

As a company, it is important to maintain a consistent customer base for steady business. 
Businesses provide services or products for customers so that they establish ongoing relationships to the consumer. 
Client retention vs Churn
Retention: Rate at which customers continue to use a product or service.
Churn: Rate at which customers stop using a product or service.
The key question to ask is: Why are we losing customers

##### Our conclusions

Month-to-Month payment plans seem to enable customer churn

Fiber Internet, surprisingly, is correlated with churn

It appeared likely that these customers were either “shopping” for the best internet elsewhere OR there could be a problem with our fiber distribution.

A lack of tech support and online security are ranked high for feature importance. This could imply that customers were lost that were not already committed to our service or did not find our service valuable

A solution that we proposed was: Upselling these features could help retain customers

##### Potential Issues and Improvements

Imbalanced Data Solutions
Get more data: quantity and quality
Bootstrapping samples
Explore correlation of features and introduce interactions
Correlated features can skew models relying on independent features
An interaction combines correlated features and incorporates them into the model


### Credits

Many thanks to my team members Qianyu and Christian.
Qianyu's github can be found here: https://github.com/rapunzel-a-c
At this moment, I am awaiting Christian's response, so I cannot link to his github. However, his LinkedIn can be found here: https://www.linkedin.com/in/christian-kolker-b06a19277/

Our dataset was originally posted by BHARTI PRASAD here: https://www.kaggle.com/code/bhartiprasad17/customer-churn-prediction


