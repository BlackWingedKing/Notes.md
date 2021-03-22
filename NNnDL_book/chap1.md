# Chapter-1

### Hand Written Digit Recognition

This section gives us a basic idea of what neural networks or what machine learning in general do. Take in a lot of training samples and they gain the ability to predict over unknown data. Explains a bit on MNIST dataset

### Perceptrons

Simplest models for artificial neurons...

* Developed in 50's and 60's itself by  [Frank Rosenblatt](http://en.wikipedia.org/wiki/Frank_Rosenblatt) (inspired by earlier [work](http://scholar.google.ca/scholar?cluster=4035975255085082870) by [Warren McCulloch](http://en.wikipedia.org/wiki/Warren_McCulloch) and [Walter Pitts](http://en.wikipedia.org/wiki/Walter_Pitts))

  ![img](http://neuralnetworksanddeeplearning.com/images/tikz0.png)

Binary inputs and Binary output. Rule for computing the output is

* Weights ($w_{i}$) corresponding to each input $i$

* calculate the weighted sum $\sum_{j}w_{j}x_{j}$ 
  $$
  \begin{eqnarray}
    \mbox{output} & = & \left\{ \begin{array}{ll}
        0 & \mbox{if } \sum_j w_j x_j \leq \mbox{ threshold} \\
        1 & \mbox{if } \sum_j w_j x_j > \mbox{ threshold}
        \end{array} \right.
  \end{eqnarray}
  $$

#### A simple example is given here

* Varying the weights of input and threshold at o/p it showed how it would affect the decision

#### Biological inspiration
check these links [1](https://subscription.packtpub.com/book/big_data_and_business_intelligence/9781788397872/1/ch01lvl1sec9/inspiration-for-neural-networks), [2](https://www.inetsoft.com/company/inspiration_for_artificial_neural_networks/)
