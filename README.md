This is a personal project, the idea and data sets come from Kaggle--Photo Quality Prediction 

Given anonymized information on thousands of photo albums, predict whether a human evaluator would mark them as 'good'.

Background
We have a large collection of user-generated photos. We want to automatically pick out particularly enjoyable or impressive ones to highlight, especially travel-related, using only the meta-data associated with the images such as caption text, image dimensions and approximate location in the world. We know from our preliminary experiments and intuition that certain words and places are correlated with good photos, and others are indicators of less enjoyable pictures, but we would like to develop an algorithm to tie together these multiple signals.

My main work on this project is to analize text type of information and successfully add them into a binomial linear model to get a relatively lower error rate.

Methods used in this project: Exploratory data analysis; 1 gram vectorization to generate a large sparse matrix; glmnet
