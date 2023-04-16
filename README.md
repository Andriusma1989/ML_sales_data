# ML training on sales data

The dataset used in this project has two features (age and estimated salary) and a binary target variable.

In this project, we used GridSearchCV with k-fold cross-validation to find the best parameters for three different models: K-Nearest Neighbors (K-NN), Decision Tree, and Random Forest. The best parameters were chosen based on their ability to maximize the accuracy of the models. The optimal parameters found for each model can be attributed to various factors, such as the data distribution, shape, and decision boundary.

Based on the results, the K-Nearest Neighbors (K-NN) model has been identified as the best model. The best parameters found for K-NN are as follows: 'algorithm': 'auto', 'metric': 'chebyshev', 'n_neighbors': 7, 'p': 1, and 'weights': 'uniform'. The K-NN model achieved a cross-validation F1-score of 0.913, a test F1-score of 0.930, and a test accuracy of 0.940.

Although the test accuracies of all three models are the same, the K-NN model has a slightly higher cross-validation and test F1-score, indicating that it is the best model among the three.

![image](https://user-images.githubusercontent.com/74529160/232306721-a2948932-3b16-4ef7-8713-720abcf1909f.png)

## Getting Started
To get started, you will need to have a Google account to access the Colab platform. Once you have access, you can open the picture_slicing.ipynb notebook file in Colab and execute the code cells.
