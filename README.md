# Salary Prediction

Utilized classification models including SVM, logistic regression, random forest (best performing estimator),
and bagged SVMs to predict how well a data science position will pay.  The features include
location and keywords within the job title.  The data used to train the models were scraped from indeed.com using  
the BeautifulSoup library in Python and required extensive cleaning.  According to the feature importance
output of the random forest model, the city the position is located is the most important factor when it 
comes to level of salary.
