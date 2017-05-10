---
layout: post
title:  "Machine Learning and Data Analysis Specialization"
categories: machine-learning
tags: machine-learning, data-science
---
In this post, I'd like to share my experience of getting into a fascinating field of Artificial Intelligence through the [Machine Learning and Data Analysis Specialization][mlda-link] created by my alma mater - Moscow Institute of Physics and Technology (MIPT) - and Yandex on Coursera.

I started the specialization in April 2016 and finished in December 2016. With a full-time job and warm summer days, I missed a couple of deadlines and graduated in 8 months. Nevertheless, I'm quite proud of this achievement, especially because it felt a bit like getting back to my life as a student of one of [the best universities in the world][mipt-best].

What I found exceptional about this particular specialization is the fact that almost all lessons were accompanied with a nicely formatted PDF containing lecture notes. Comparing it with a couple of Nanodegrees on Udacity that I'm in progress of pursuing, I can say that it's probably one of the very few programs created with such fantastic diligence and attention to details. I learn by reading, so these assets were of great value to me, and I keep referring back to them from time to time.

The specialization is split into six courses as follows:
1. [Maths and Python for Data Analysis](#1-maths-and-python-for-data-analysis)
2. [Supervised Machine Learning](#2-supervised-machine-learning)
3. [Unsupervised Machine Learning](#3-unsupervised-machine-learning)
4. [Statistics for Data Analysis](#4-statistics-for-data-analysis)
5. [Applied Problems of Data Analysis](#5-applied-problems-of-data-analysis)
6. [Capstone Project](#6-capstone-project)

### 1. Maths and Python for Data Analysis
Since I didn't have a chance to work with Python before, I found this introductory course very useful to get acquainted with the Python syntax, data structures and its powerful libraries for data analysis like `numpy`, `pandas`, `scipy`, `sklearn`, `seaborn`, etc. I found the fact of mentioning the ["The Zen of Python"](https://www.python.org/dev/peps/pep-0020/) quite adorable. It's always good to learn how it all started and get to know the philosophy behind the language. From the very beginning, all programming was done in Jupyter Notebooks, which is now getting so popular in the Data Science community.

Revising Maths - Statistics, Linear Algebra, and Calculus - that I studied over 7 years ago brought up fond memories. In the spirit of education at MIPT, the authors of the specialization decided to provide all Maths relevant to machine learning in the beginning rather than explain it in the context of applied problems along the programme. Thus, the course introduces multi-variable calculus, optimization problems (gradient descent, simulated annealing, differential evolution, Neldear-Mead method), singular value decomposition (SVD), statistical distributions and confidence intervals. The majority of the students, including myself, I guess, will hardly remember the maths details behind the `scipy` functions. In the end, who programs genetic algorithms on a regular basis? Still, I reckon it was a good decision to capture all Maths in one place because the foundation matters.

### 2. Supervised Machine Learning
Following the general principles of the specialization, the course started with an introduction to Machine Learning covering a wide range of topics: recommendation systems, classification and regression, ranking, data clusterization and visualization, anomaly detection. Students get a nice overview of the problems that machine learning help to solve.

The course proceeds with a detailed explanation of linear models, visualization of gradient descent, followed by stochastic gradient descent - by far the most popular optmization method - and loss functions. The section finished with practical recommendations such as under- and oversampling, transition to rectifying space by creating quadratic, polynomial and logistic features, and one-hot encoding.

I really enjoyed the concept of decision trees and the idea of combining them into random forests followed by the gradient boosting algorithm. The students have to build the latter one themselves before being introduced to [XGBoost](https://xgboost.readthedocs.io).

Even through neural networks were introduced in this course, I can't say that I fully understood the concept at that time. It's only now, after I finished the [Deep Learning Nanodegree Foundation on Udacity](https://in.udacity.com/course/deep-learning-nanodegree-foundation--nd101/), the lecture paper made complete sense to me. In the spirit of [The Phystech System](https://en.wikipedia.org/wiki/Moscow_Institute_of_Physics_and_Technology#The_Phystech_System), a neural network was was presented as a universal model due to its ability to approximate any topological surface. Russian mathematician Andrey Kolmogorov [proved](https://en.wikipedia.org/wiki/Hilbert%27s_thirteenth_problem) such theorem in 1957. The rest of the lecture covered neural networks with fully-connected layers, dropout as a regularization method, and some practical recommendations. It's fair to say that the authors of this course mentioned that neural networks deserved an entirely separate course and they didn't want to spend much time on this topic.

Nearest Neighbour method and Support Vector Machine (SVM) were introduced closer to the end of the course. While SVM was explained in great detail, including SVM with non-linear kernels, it left me with an impression that this technology has been superseded by random forests classifiers. It's true that decision trees and random forests are easier to get started with for a beginner. They require much less parameters to tune - basically, just the tree depth and the number of trees. SVM on the other hand, while requiring a fair amount of parameter tuning, can get by with much less amount of data.

Bayesian models might not be the most popular ones in machine learning but they do have some advantages. One remarkable advantage is the ability of such models to work with partially labeled data. Compared with classical probability methods, Bayesian approach allows to extract maximum available information from such models. Also worth noting that Bayesian statistics in combination with neural networks gave us autoencoders - one the of the hottest research topics in AI at the time of writing!

Looking back at the specialization as a whole, I found this particular course incredibly interesting. It even motivated me to buy ["The Elements of Statistical Learning" by T.Hastie, R.Tibshirani, J.Friedman](https://statweb.stanford.edu/~tibs/ElemStatLearn/) - the classics on Machine Learning - to study the topic further.

### 3. Unsupervised Machine Learning
Unsupervised Machine Learning was introduced with clusterization.

### 4. Statistics for Data Analysis

### 5. Applied Problems of Data Analysis

### 6. Capstone Project

[mlda-link]: https://www.coursera.org/specializations/machine-learning-data-analysis
[mipt-best]: https://www.topuniversities.com/universities/moscow-institute-physics-technology-mipt-moscow-phystech
