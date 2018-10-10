# practical machin learning final project
Firstly, I observe that there are many Nas in both pml-training.csv and pml-testing.csv. So I remove some NearZerovariables. However, there are also some variables which contain many NAs, I use for loop to clean them. Then I get appropriate training set and test set.

Next, I use three different models to predict training set. And I also make figures for them. By comparing accuracy of these models, I decide to use randomForest.

Finally, I apply my machine learning algorithm to the 20 test cases.
