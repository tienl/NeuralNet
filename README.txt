In this challenge I've produced a Deep Neural Network learning model that learn from provided data to predict loans' likelihood of default.

I've set up 4 hidden layers each using 80 neurons for my neural model.  The model achieved 74% accuracy on training data, but 68% accuracy on test data.
In attempts to achieve better result, I've examined the input data and binned "ask amount" of the loan, since it was very uneven in distribution as well as the range were rather large.  I've also increased layers from 1 to 4 in hidden layer, implemented dropout method, as well as experimented with various activation function and their ordering.  I've even tried various optimizer and loss function.  Finally, I've attempted with higher epoch up to 200.

Alternative models that I would consider using next may include supervised learning of logistic regression, and using ensemble learning using BRF (balanced random forest) and adaboost.
