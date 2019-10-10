# Machine Learning model exploration with R
Image classification with different machine learning models

In this project, we explored different machine learning models using R. ML models we used are Multinomial Logistic Regression, K Nearest Neighbors, Classification Tree, Random Forest, Lasso Regression, Ridge Regression, Support Vector Machines, Generalized Boosted Machine Models, and Neural Networks, and one other model that combine the results of three models with best performances. And the way we score the models is: 0.25*(run time of the model and prediction)/60 + 0.25*(size of data set)/60000 + 0.5*(proportion of incorrect predictions), where 60000 is the size of sampels we have in hand. The lower score indicates better model.

My contribution for this project: 
Voting, misclassification, iteration, scoring, and reporting functions. Code and description of SVM, Random Forest, GBM, and combined models.
