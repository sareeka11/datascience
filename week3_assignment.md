

```python
Parameter-
A parameter is used to describe the entire population being studied.
For example, we want to know the  life span of a people in India. This is a parameter because it is states something about 
the entire population in India.Since it will be impossible to catch and measure all the
people in the India, we can consider 1000 people and can cosider there Life span. The life span of the 1000 people in India is a 
statistic that we can use to make an inference about the Life Span of people in India.
The population mean and standard deviation are two common parameters. In statistics, Greek symbols usually represent population
parameters, such as μ (mu) for the mean and σ (sigma) for the standard deviation.

1. Gaussian distribution
Gaussian distribution, also known as the Normal distribution, is a probability distribution that is symmetric about the mean, 
showing that data near the mean are more frequent in occurrence than data far from the mean. In graph form, Gaussian distribution
will appear as a bell curve.
i.  A Gaussian distribution is the proper term for a probability bell curve.
ii. In a Gaussian distribution the mean is zero and the standard deviation is 1. It has zero skew and a kurtosis of 3.
iii.Gaussian distributions are symmetrical , but not all symmetrical distributions are normal.
iv. In reality, most pricing distributions are not perfectly normal.

2. Binomial disrtibution
The binomial distribution is a probability distribution that summarizes the likelihood that a value will take one of two
independent values under a given set of parameters or assumptions. The underlying assumptions of the binomial distribution 
are that there is only one outcome for each trial, that each trial has the same probability of success, and that each trial
is mutually exclusive, or independent of each other.
i.The binomial distribution is a probability distribution that summarizes the likelihood that a value will take one of two
   independent values under a given set of parameters or assumptions.
ii.The underlying assumptions of the binomial distribution are that there is only one outcome for each trial, that each trial
   has the same probability of success, and that each trial is mutually exclusive or independent of each other.
ii.The binomial distribution is a common discrete distribution used in statistics, as opposed to a continuous distribution, 
   such as the normal distribution.
    
Difference between Binomial distribution and Guassian distribution
1.Guassian distributions are more common in statistics than binomial distributions most of the time.
2.Guassian distributions can be described by their mean and standard deviation. The mean determines
  where the center of the distribution is located. The standard deviation determines the shape of the distribution.
  Binomial distributions tell us the probability for a specific number of “successes” to happen, given a probability 
  of success and number of trials.
3.Guassian distribution tells us about the mean of dataset.
  Binomial distributions tell us the results of only two possible outcomes: success or failure.
4.Guasian distribution example-The heights of people in a country.
  Binomial distribution example-Flipping a coin, which can only result in heads or tails.
    
Logistics Regression-
1.The logistic regression is a predictive analysis. Logistic regression is used to describe data and to explain the 
  relationship between one dependent binary variable and one or more nominal, ordinal, interval or ratio-level independent 
  variables.
2.Logistic regression uses an equation as the representation, very much like linear regression.
  Input values (x) are combined linearly using weights or coefficient values (referred to as the Greek capital letter Beta)
  to predict an output value (y). A key difference from linear regression is that the output value being modeled is a binary 
  values (0 or 1) rather than a numeric value.
  Below is an example logistic regression equation:
     y = e^(b0 + b1*x) / (1 + e^(b0 + b1*x))
  Where y is the predicted output, b0 is the bias or intercept term and b1 is the coefficient for the single input value (x). 
  Each column in your input data has an associated b coefficient (a constant real value) that must be learned from your training 
  data.The actual representation of the model that you would store in memory or in a file are the coefficients in the equation 
  (the beta value or b’s).
3.Logistic Regression is used when the dependent variable(target) is categorical.
  For example,
  1.To predict whether an email is spam (1) or (0)
  2.Whether the tumor is malignant (1) or not (0)
4.Advantages-
 1. Logistic Regression performs well when the dataset is linearly separable.
 2. Logistic regression is less prone to over-fitting but it can overfit in high dimensional datasets. You should consider 
   Regularization (L1 and L2) techniques to avoid over-fitting in these scenarios.
 3. Logistic Regression not only gives a measure of how relevant a predictor (coefficient size) is, but also its direction of association (positive or negative).
 4. Logistic regression is easier to implement, interpret and very efficient to train.
5.Disadvanteges-
 1. Main limitation of Logistic Regression is the assumption of linearity between the dependent variable and the independent 
   variables. In the real world, the data is rarely linearly separable. Most of the time data would be a jumbled mess.
 2. If the number of observations are lesser than the number of features, Logistic Regression should not be used, otherwise 
    it may lead to overfit.
 3. Logistic Regression can only be used to predict discrete functions. Therefore, the dependent variable of Logistic Regression 
  is restricted to the discrete number set. This restriction itself is problematic, as it is prohibitive to the prediction of 
    continuous data.

Decision tree classifier-
1.Decision Tree is a Supervised learning technique that can be used for both classification and Regression problems, 
  but mostly it is preferred for solving Classification problems. It is a tree-structured classifier, where internal nodes
 represent the features of a dataset, branches represent It is a tree-structured classifier, where internal nodes represent 
  the features of a dataset, branches represent the decision rules and each leaf node represents the the decision rules and each 
  leaf node represents the outcome.
2.In a Decision tree, there are two nodes, which are the Decision Node and Leaf Node. Decision nodes are used to make any
  decision and have multiple branches, whereas Leaf nodes are the output of those decisions and do not contain any further branches.
3.  The decisions or the test are performed on the basis of features of the given dataset.
4.It is a graphical representation for getting all the possible solutions to a problem/decision based on given conditions.
5.It is called a decision tree because, similar to a tree, it starts with the root node, which expands on further branches and 
  constructs a tree-like structure.
6.In order to build a tree, we use the CART algorithm, which stands for Classification and Regression Tree algorithm.
7.A decision tree simply asks a question, and based on the answer (Yes/No), it further split the tree into subtrees.

Random Forest classifier-
1.Random forest is a supervised learning algorithm which is used for both classification as well as regression. 
But however, it is mainly used for classification problems.
2. As we know that a forest is made up of trees and more trees means more robust forest. Similarly, random forest algorithm
 creates decision trees on data samples and then gets the prediction from each of them and finally selects the best solution 
 by means of voting.
3.One big advantage of random forest is that it can be used for both classification and regression problems, which form 
 the majority of current machine learning systems.
4.Working of Random Forest Algorithm
We can understand the working of Random Forest algorithm with the help of following steps −
Step 1 − First, start with the selection of random samples from a given dataset.
Step 2 − Next, this algorithm will construct a decision tree for every sample. Then it will get the prediction result from every decision tree.
Step 3 − In this step, voting will be performed for every predicted result.
Step 4 − At last, select the most voted prediction result as the final prediction result.

```
