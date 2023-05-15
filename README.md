# data_mining
Data Mining



# Hyperparameter optimization with MLP
For this part, I use GridSearch to do hyperparameter tuning based on MLP
Since running the code with 500,000 rows is too time-consuming, I just used first 50,000 rows to get the best parameters
Final results are following:

Best Hyperparameters of MLP: {'activation': 'tanh', 'hidden_layer_sizes': (100, 50), 'learning_rate': 'constant', 'solver': 'adam'}
Best Accuracy of MLP: 0.9980499999999999
Computation time: 1412.4333038330078
