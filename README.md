# Linear-Regression-Model

Description and Requirements 
In the assignment, you are given a dataset. You need to implement the gradient descent algorithm to estimate (train) the weights of the linear regression model. You must use Python programming language with Jupyter Notebook. Split the given dataset into two training and test with a ratio of 8:2. Use the training set to estimate the weights and the test set to evaluate the linear regression model with the estimated weights.

Define at least three (3) functions as follows

def train_model(X, y, alpha, max_epoch):
""" Pass four arguments
Arguments:
X: input features
 y: responses
alpha: learning rate
max_epoch: maximum epochs
Returns:
 w: estimated weights
hist_loss: training loss history
 """
 
def prediction(w, X):
""" Pass two arguments
Arguments:
w: weights
 X: input features 
Returns:
 yhat: predicted values
 """
 
def loss_fn(y, yhat):
""" Pass two arguments
Arguments:
y: responses
 yhat: predicted value 
Returns:
 loss: loss value
 """

Display the training loss value for each epoch of the training loop.
Display the estimated weights (after model training).
Display the training loss against epoch graph (after model training).
Evaluate the linear regression model with the estimated weights on the test set and display at 
least R-squared and mean squared error measures.
Document the codes using markdown and comments.
