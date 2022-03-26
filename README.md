# Fan-base-classification-from-Twitter
For this task, we are predicting the fan base, either of Seattle Seahawks or New England Patriot, from the given tweets dataset. The attribute of a tweet sentiment reveals a lot of information about the author of the tweet. For example, in Super Bowl 2015 the authors of positive sentiment tweets would originate from their state in this case authors of tweets from Seattle Washington would have positive tweets about their home team Seahawks and negative tweets about the opposing team, in this case the New England Patriots.

<br>In the first half of the task, I use tweets_#superbowl.txt to predict the location of the author of each tweet, in this case either Washington or Massachusetts. The tweet file contains one tweet in each line and tweets are sorted with respect to their posting time. Since each tweet is a JSON string,  I load through Python as a dictionary, and then use Pandas to convert it as a dataframe file for further analysis. In order to track the location and encode the information, U use the encoding function to return different numbers (1, -1, 0) for different locations text input, and append results to the list of titles. In the second half of the task, I split the data into train and test datasets and then implemented 6 different binary classifiers with Logistic Regression(L1 and L2 penalty), KNN, Naive Bayes, Random Forest Classifier, Neural network classifier and SVM and applied gridsearch for finding the best parameters, and report out the Precision/Recall Scores, ROC curves and confusion matrices.


### Models used
Logistic Regression(L1 and L2 penalty) 
<br>KNN 
<br>Naive Bayes
<br>Random Forest Classifier
<br>Neural network classifier
<br>SVM
