## Lab Data Analysis (1)
>- This is a basic data about DHB. And our goals are to verify if there is a relationship between independent variables and dependent variable, also to consider if we could use our model to predict the condition.

>- The size of original data is (221, 9), where are 8 independent features and 1 binary dependent variable. 
The independent features include 6 numerical variables and 2 categorical variables. The numerical variables part are all relative to the shape of cells. The categorical variables could be seperated as one ordinal feature(with 3 different level) and one nominal feature(with 7 different categories). 

>- From the above analysis of data, it is obvious to see that our data is mixed data. Also, since the 6 numerical variables are all about the shape of cells. Some of them have strong multicollinearity. Then I built a basic model based on PCA and Logistic Regression. I applied PCA on numerical part and then combine the main components with the two encoded categorical features. Based on the new set of data, I directly use the logistic regression in the scikit-learn package. 

>- This is only a basic idea for the model. And I am still working on it that I think there are something more need to be improved.

