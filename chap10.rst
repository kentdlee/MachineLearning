Chapter 10: Introduction to Artificial Neural Networks
---------------------------------------------------------

Week of April 18th

Tuesday - In class presentations

Thursday - Perceptrons -- Neural Networks

Here are a couple of good resources for you to watch on your own:

Neural Networks Demystified - Even if you don't follow all of the calculus these are still quite good to help you get a feeling for backpropagation.
Step by Step backpropagation Walks you through a back propagation example one step at a time. Again there is calculus involved but it can still help you get a good feel for how the learning works.

By April 25th we get to Multi-Layer Perceptrons.

Tuesday Multi-Layer Perceptrons


Starting from your mid-term project See if you can improve your recommendations by doing the following:

Do some exploratory data analysis on the incorrectly classified rows of data. What can you learn aobut this subset? How does it compare to the dataset as a whole or even look at how it compares to the set of correctly classified instances. Does this inspire any further preprocessing of the data or perhaps some additional variables that you could add? If so add them and investigate the results.
Use either the GridSearchCV or RandomizedSearchCV class to try to find the best values for the hyperparameters for one or more of your algorithms. You should use the sklearn documenation to select some hyper parameters as well as for the details of how to use the Grid or Randomized search models.
Finally, the ensemble learning idea could really help improve your results. That is use all three (or more) of your models and have them vote on the final classification. You can implement a simple Python class that provides a fit and predict method.


Reading Assignment
+++++++++++++++++++

Read by April 18th.

Exercises
+++++++++
