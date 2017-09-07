# deep_learning_theano

Deep learning algorithms are currently at the state-of-the-art for classifiction performance on the MNIST dataset. In particular, a hierarchical convolution neural network approach achieved an error rate of just 0.23% in 2012.

In my Logistic Regression implementation, I take the Theano API in python to train my model to read numbers. Then, I test my program against a new set of images to test its accuracy. In the best case, I got the following output:
Optimization complete with best validation score of 7.479167 %,with test performance 7.489583 %

Next Step:

While logistic regression is hardly a state of the art technique for classification purposes it does allow us to explore the Theano API, build a non-trivial model on a large dataset, train the model on both the CPU and GPU as well as predict new classifications from this model.

The next program will focus on building a neural network, such as a multilayer perceptron (MLP)
