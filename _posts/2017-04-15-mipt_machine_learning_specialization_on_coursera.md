---
layout: post
title:  "Machine Learning and Data Analysis Specialization"
summary: "An overview of a specialization on Coursera that got me started in Machine Learning"
categories: machine-learning
tags: machine-learning, data-science
comments: true
---
In this post, I'd like to share my experience of getting into a fascinating field of Artificial Intelligence through the [Machine Learning and Data Analysis Specialization][mlda-link] created by my alma mater - Moscow Institute of Physics and Technology (MIPT) - and Yandex on Coursera.

I started the specialization in April 2016 and finished in December 2016. With a full-time job and warm summer days, I missed a couple of deadlines and graduated in 8 months. Nevertheless, I'm quite proud of this achievement, especially because it felt a bit like getting back to my life as a student of one of [the best universities in the world][mipt-best].

What I found exceptional about this particular specialization is the fact that almost all lessons were accompanied with a nicely formatted PDF document containing lecture notes. Comparing it with a couple of Nanodegrees on Udacity that I'm in progress of pursuing, I can say that it's probably one of the very few programs created with such fantastic diligence and attention to details. I learn by reading, so these assets were of great value to me, and I keep referring back to them from time to time.

The specialization is split into six courses as follows:
1. [Maths and Python for Data Analysis](#1-maths-and-python-for-data-analysis)
2. [Supervised Machine Learning](#2-supervised-machine-learning)
3. [Unsupervised Machine Learning](#3-unsupervised-machine-learning)
4. [Statistics for Data Analysis](#4-statistics-for-data-analysis)
5. [Applied Problems of Data Analysis](#5-applied-problems-of-data-analysis)
6. [Capstone Project](#6-capstone-project)

### 1. Maths and Python for Data Analysis
Since I didn't have a chance to work with Python before, I found this introductory course very useful to get acquainted with the Python syntax, data structures and its powerful libraries for data analysis like `numpy`, `pandas`, `scipy`, `sklearn`, `seaborn`, etc. I found the fact of mentioning the ["The Zen of Python"](https://www.python.org/dev/peps/pep-0020/) quite adorable. It's always good to learn how it all started and get to know the philosophy behind the language. From the very beginning, all programming was done in Jupyter Notebooks, which is now getting so popular in the Data Science community.

Revising Maths - Statistics, Linear Algebra, and Calculus - that I studied over 7 years ago brought up fond memories. In the spirit of education at MIPT, the authors of the specialization decided to provide all Maths relevant to machine learning in the beginning rather than explain it in the context of applied problems along the programme. Thus, the course introduces multi-variable calculus, optimization problems (gradient descent, simulated annealing, differential evolution, Neldear-Mead method), singular value decomposition (SVD), statistical distributions and confidence intervals. The majority of the students, including myself, I guess, will hardly remember the maths details behind the `scipy` functions. In the end, how many of us program genetic algorithms on a regular basis? Still, I reckon it was a good decision to capture all Maths in one place because the foundation matters.

### 2. Supervised Machine Learning
Following the general principles of the specialization, the course started with an introduction to Machine Learning covering a wide range of topics: recommendation systems, classification and regression, ranking, data clusterization and visualization, anomaly detection. Students get a nice overview of the problems that machine learning help to solve.

The course proceeds with a detailed explanation of linear models, visualization of gradient descent, followed by stochastic gradient descent - by far the most popular optmization method - and loss functions. The section finished with practical recommendations such as under- and oversampling, transition to rectifying space by creating quadratic, polynomial and logistic features, and one-hot encoding.

I really enjoyed the concept of decision trees and the idea of combining them into random forests followed by the gradient boosting algorithm. The students have to build the latter one themselves before being introduced to [XGBoost](https://xgboost.readthedocs.io).

Even though neural networks were introduced in this course, I can't say that I fully understood the concept at that time. It's only now, after I finished the [Deep Learning Nanodegree Foundation on Udacity](https://in.udacity.com/course/deep-learning-nanodegree-foundation--nd101/), the lecture paper has made complete sense to me. In the spirit of [The Phystech System](https://en.wikipedia.org/wiki/Moscow_Institute_of_Physics_and_Technology#The_Phystech_System), a neural network was was presented as a universal model due to its ability to approximate any topological surface. Russian mathematician Andrey Kolmogorov [proved](https://en.wikipedia.org/wiki/Hilbert%27s_thirteenth_problem) such theorem in 1957. The rest of the lecture covered neural networks with fully-connected layers, dropout as a regularization method, and some practical recommendations. It's fair to say that the authors of this course mentioned that neural networks deserved an entirely separate course and they didn't want to spend much time on this topic.

Nearest Neighbour method and Support Vector Machine (SVM) were introduced closer to the end of the course. While SVM was explained in great detail, including SVM with non-linear kernels, it left me with an impression that this technology has been superseded by random forests classifiers. It's true that decision trees and random forests are easier to get started with for a beginner. They require much less parameters to tune - basically, just the tree depth and the number of trees. SVM on the other hand, while requiring a fair amount of parameter tuning, can get by with much less amount of data.

Bayesian models might not be the most mainstream ones in machine learning but they do have certain advantages. A remarkable one is the ability of such models to work with partially labelled data. Compared with frequentist statistics methods, Bayesian approach allows to extract maximum available information from such models. Also worth noting that Bayesian statistics in combination with neural networks gave us autoencoders - one the of the hottest research topics in AI at the time of writing!

Looking back at the specialization as a whole, I found this particular course incredibly interesting. It even motivated me to buy ["The Elements of Statistical Learning" by T.Hastie, R.Tibshirani, J.Friedman](https://statweb.stanford.edu/~tibs/ElemStatLearn/) - the classics on Machine Learning - to study the topic further.

### 3. Unsupervised Machine Learning
Unsupervised Machine Learning was introduced with clusterization, matrix decomposition, dimensionality reduction, data visualization and anomaly detection. We also had a chance to practice topic modelling with the [BigARTM](http://bigartm.org/) library. Overall, I felt that unsupervised machine learning, when there are no correct labels for the data, is less popular than supervised machine learning. However, having made a dive into the world of neural networks, I realized that there is much more unlabelled data in the world, and semi-supervised Generative Adversarial Networks that use such data are at the forefront of modern research in artificial intelligence.

### 4. Statistics for Data Analysis
Quite to my surprise, I genuinely enjoyed this course. It's most certainly because of the way the authors managed to talk about such a seemingly dry and boring topic as Statistics. As they said, "*Statistics may cause frustration in those with a weak spirit, but we are above all that!*"

Confidence intervals, p-value, statistical hypothesis testing, Student's t-test and Z-factor, A/B testing - all these topics are covered in the fourth module of the specialization.

### 5. Applied Problems of Data Analysis
While the full specialization has been focused on the most practical aspects of Machine Learning, in the fifth module, the authors took a step further and talked about a number of modern applied problems. In particular, they covered predicting time series with the help of ARMA, ARIMA, and ARIMAX models. I loved the idea behind them but to my regret I learned that quite often supervised machine learning show better results when trying to predict a particular value in the future.

The course also gave a thorough introduction to a mathematical concept of convolution, the basic principle of convolutional neural networks. In addition, students get an overview of recurrent neural networks, word2vec, and sentiment analysis. To be honest, I have to say that I got a much better understanding of how neural networks work from a Deep Learning Nanodegree Foundation on Udacity.

### 6. Capstone Project
The final course of the specialization offered students four guided projects.
1. Identifying Users by Their Internet Browsing History
2. Customer Churn Prediction
3. Predicting Time Series of New York Taxi Usage
4. Customer Feedback Sentiment Analysis

All projects sounded very interesting but I chose the first one because of interesting potential use cases that I could create out of it in the future. In particular, I am thinking of something related to personalised customer experience. I was one of the first ones to carry out this project and pointed out a few issues with it. In addition, I even managed to contribute to Vowpal Wabbit - a very powerful machine learning library - by reporting a minor [bug](https://github.com/JohnLangford/vowpal_wabbit/issues/1164) that was promptly fixed.

### Conclusion
Quite often, we are daunted by an idea of committing to something the results of which we would see in a few months. Looking back, I am happy that I had made such commitment and finished this specialization, which not only helped me acquire the necessary foundation to get started in Machine Learning but also gave me confidence that with persistence and clear goal in sight I can successfully progress through a subject of any difficulty.

[mlda-link]: https://www.coursera.org/specializations/machine-learning-data-analysis
[mipt-best]: https://www.topuniversities.com/universities/moscow-institute-physics-technology-mipt-moscow-phystech
