# DEBI-Task
### CNN with transfer learning use case

- In this exercise you need to implement a LeNet-5 network to recognize the Fashion
  MNIST digits. 
- Modify hyperparameters to get to the best performance you can achieve. 
- Evaluate the model using 5-fold cross-validation.
- In the report, provide a plot of accuracy improvement using the previously
   mentioned techniques. Also plot the convergence curve for LeNet-5.  
- Try to use other two CNN models (using transfer learning) and compare the
   results with the full trained LeNet-5.
---------------------------------------------------------------------------------------------------------------

### Deep learning use case

- In this project, you need to implement a 3-layer MLP model (one input layer, one hidden layer
  with tanh activation and one output layer) which will be used to classify the data  
- You can use the built-in modules in keras to build your model.
  You also need to write the training function (training), and should explore the following
  hyperparameter settings:
     Batch size: Number of examples per training iteration.
     Hidden size: Try using different number of hidden nodes in your model and compare the performances.
     Dropout is an effective strategy to defend against overfitting. Adding a dropout layer
     after the hidden layer, and try using different dropout rate to compare the performances. 
     Optimizer: Try using different optimizers such as SGD, Adam, RMSProp.
     Regularization (weight decay): L2 regularization can be specified by setting the
     weight_decay parameter in optimizer. Try using different regularization factor and check the performance. 
---------------------------------------------------------------------------------------------------------------

### Session 6 live  assignment

- you should submit at least two experiments with different models (Linear Regression, Lasso , Ridge and SGR regressor).

- you should also add the normality checks (QQ-plot / Shapiro wilk test).
- you should also use the Sklearn pipeline  with all the preprocessing steps including the outlier removal , normalization and any other preprocessing you think it will be needed.
  Learning rate, Learning rate scheduler: Learning rate is key hyperparameter in model
  training, and you can gradually decreasing the learning rate to further improve your model. 
---------------------------------------------------------------------------------------------------------------
