ML Project- Fake news detection within online social media using supervised artificial intelligence algorithms

Name: 1.Kshitij Sarawagi-181CO229
      2.Sumeet Bisen-181CO254

Dataset- ISOT Fake News data set
	 This data set contains two types of news, fake and real news. Fake and real news are obtained from real-world sources.
The real news articles were collected from Reuters.com, while the fake news articles were collected from unreliable various
websites such as Politifact and Wikipedia.The data set consists of a total of 44 898 data, 21 417 real-labeled data and
23 481 false-labeled data. 10 samples from both the classes were dropped and were made into a new dataset for manually testing
them with our already trained and tested algorithms.

Supervised artificial intelligence algorithms are form of learning based on the training set. They assume that the labels
of instances in the data sets are already known. They require a training set of labeled data and return a function that
instances to the supervised data. The task of the function is to estimate the output having the minimum error rate from
the input. In the following section, information about supervised artificial intelligence algorithms used in this study is
given.The TF-IDF vectorizer is used in this study to convert the terms in the data set for each document into a vector of 
term of weights. 

1.Logistic Regression:
	Logistic regression is a statistical analysis method used to predict a data value based on prior observations of a 
data set. Logistic regression has become an important tool in the discipline of machine learning. The approach allows an algorithm 
being used in a machine learning application to classify incoming data based on historical data. As more relevant data comes in, 
the algorithm should get better at predicting classifications within data sets.

Accuracy- 98.77896613190731

2.Decision Tree:
	Tree-based learning algorithms are one of the most used supervised learning algorithms. Methods such as Decision
Trees, Random Forests, and Gradient Boosting are widely used in all kinds of data science problems. Decision Trees have
a predefined target variable. In terms of their structure, they offer a top-down strategy. A decision tree is a structure used
to divide a data set containing a large number of records into smaller clusters by applying a set of decision rules. In other
words, it is a structure used by dividing large amounts of records into very small groups of records by applying simple
decision-making steps.

Acccuracy- 99.50980392156863

3.Random Forest:
	Random forests are a way of averaging multiple deep decision trees, trained on different parts of the same training set, 
with the goal of reducing the variance. This comes at the expense of a small increase in the bias and some loss of interpretability, 
but generally greatly boosts the performance in the final model.

Accuracy- 99.11764705882354

Conclusion- In recent years, it has become difficult for users to access accurate and reliable information because of the increased
amount of information on social media. In this study, a model is proposed to detect fake news in social media by
combining text mining methods and supervised artificial intelligence algorithms. Text mining analysis and supervised
artificial intelligence algorithms have been conducted separately.



	