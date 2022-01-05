# Supervised_ML_Challenge
Unscaled Logistic Regression: \
Best Scores during parameter tuning gave .704 for training and .58 for testing data. \
\
Unscaled Random Forest:\
Best Scores during parameter tuning gave .998 for training and .676 for testing data.\
\
Scaled Logistic Regression:\
Best Scores during parameter tuning gave .71 for training and .72 for testing data.\
\
Scaled Random Forest:\
Best Scores during parameter tuning gave .998 for training and .704 for testing data. Using Random CV recieved a score of .65, however this can change as it is a random  sample of all possible parameter selections. 

Logistic regression performed as expected, having recieved scores higher than that of the random forest before and after scaling. Afer scaling there was a drastic improvement in model performance in the logistic regression models, whereas the random forest models remained relatively the same. Even though logistic regression received significantly worse scores on the training data, it performed better on the testing data. The random forest model on the otherhand shows evidence of overfitting, with some parameter combinations yeilding scores of 1.0. As a result the testing scores were worse, but not significantly worse than those of logistic regression. Scaled Logistic Regression is likely the most consistent model in this scenario.
