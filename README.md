# Machine Learning by Standford University #
 Adjunct Professor: Andrew NG 


## Syllabus

### Week 1:  Introduction
    
  ####  1. Linear Regression with One Variable
    
   Linear regression predicts a real-valued output based on an input value. 
   We discuss the application of linear regression to housing price prediction, 
   present the notion of a cost function, and introduce the gradient descent
   method for learning.
    
  ####  2. Linear Algebra Review
    
   This optional module provides a refresher on linear algebra concepts. 
   Basic understanding of linear algebra is necessary for the rest of the course, 
   especially as we begin to cover models with multiple variables.
    
### Week 2: Linear Regression
    
   #### 1. Linear Regression with Multiple Variables
    
   What if your input has more than one value? In this module, 
   we show how linear regression can be extended to accommodate multiple input features. 
   We also discuss best practices for implementing linear regression.
    
   #### 2. Octave/Matlab Tutorial 
    
   This course includes programming assignments designed to help you understand 
   how to implement the learning algorithms in practice. 
   To complete the programming assignments, you will need to use Octave or MATLAB. 
   This module introduces Octave/Matlab and shows you how to submit an assignment.
    
### Week 3: Logistic Regression
    
   #### 1. Logistic Regression
    
   Logistic regression is a method for classifying data into discrete outcomes. 
   For example, we might use logistic regression to classify an email as spam or not spam. 
   In this module, we introduce the notion of classification, 
   the cost function for logistic regression, and the application of logistic regression 
   to multi-class classification.
    
   #### 2. Regularization
    
   Machine learning models need to generalize well to new examples 
   that the model has not seen in practice. In this module, 
   we introduce regularization, 
   which helps prevent models from overfitting the training data.
    
### Week 4: Multi-class Classification and Neural Networks
    
  ####  1. Neural Networks: Representation
    
   Neural networks is a model inspired by how the brain works. 
   It is widely used today in many applications: when your phone interprets
   and understand your voice commands, 
   it is likely that a neural network is helping to understand your speech; 
   when you cash a check, the machines that automatically read the digits also use neural networks.

### Week 5: Neural Network: Learning
    
   In this module, we introduce the backpropagation algorithm that is used
   to help learn parameters for a neural network. 
   At the end of this module, you will be implementing your own neural network
   for digit recognition.

### Week 6: Regularized Linear Regression and Bias/Variance
    
  ####  1. Advice for Applying Machine Learning
    
   Applying machine learning in practice is not always straightforward.
   In this module, we share best practices for applying machine learning in practice,
   and discuss the best ways to evaluate performance of the learned models.
    
  ####  2. Machine Learning System Design
    
   To optimize a machine learning algorithm, 
   you’ll need to first understand where the biggest improvements can be made.
   In this module, we discuss how to understand the performance of a machine learning system
   with multiple parts, and also how to deal with skewed data.

### Week 7: Support Vector Machines

   Support vector machines, or SVMs, is a machine learning algorithm for classification.
   We introduce the idea and intuitions behind SVMs and discuss how to use it in practice.

### Week 8: K-Means Clustering and PCA
  ####  1. Unsupervised Learning
    
   We use unsupervised learning to build models that help us understand our data better.
   We discuss the k-Means algorithm for clustering that enable us to learn groupings 
   of unlabeled data points.
    
  #### 2. Dimensionality Reduction
    
   In this module, we introduce Principal Components Analysis,
   and show how it can be used for data compression to speed up learning algorithms
   as well as for visualizations of complex datasets.
    
### Week 9: Anomaly Detection and Recommender Systems
    
  ####  1. Anomaly Detection
    
   Given a large number of data points, we may sometimes want to figure out
   which ones vary significantly from the average. For example, in manufacturing,
   we may want to detect defects or anomalies.
   We show how a dataset can be modeled using a Gaussian distribution,
   and how the model can be used for anomaly detection.
    
   #### 2. Recommender Systems
    
   When you buy a product online, 
   most websites automatically recommend other products that you may like.
   Recommender systems look at patterns of activities between different users
   and different products to produce these recommendations. 
   In this module, we introduce recommender algorithms such as 
   the collaborative filtering algorithm and low-rank matrix factorization.
 
### Week 10: Large Scale Machine Learning
    
   Machine learning works best when there is an abundance of data to leverage for training. 
   In this module, we discuss how to apply the machine learning algorithms with large datasets.

### Week 11: Application Example: Photo OCR
    
   Identifying and recognizing objects, words, and digits in an image is a challenging task.
   We discuss how a pipeline can be built to tackle this problem and how to analyze and
   improve the performance of such a system.
