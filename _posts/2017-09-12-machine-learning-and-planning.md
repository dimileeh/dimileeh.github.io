---
layout: post
title:  "Machine Learning and Planning"
summary: "Intelligent solutions lie at an intersection of two major AI areas"
categories: ai
tags: machine learning, deep learning, artificial intelligence, planning
comments: true
---
From an iRobot vacuum cleaner to industrial manufacturing robots and from parcels delivery services to aeroplane ticket search, in one way or another, these are all examples of areas where planning problems are solved with the help of artificial intelligence.

In the second half of the 20th century, significant advancements were made in the core area of artificial intelligence that focuses on planning and search problems. STRIPS, the first major action language introduced in 1971 by Fikes and Nilsson, led to the creation of PDDL – Problem Domain Description Language – in 1998 that allowed to formulate problem descriptions parsable by computer systems.

Today, machine learning - another core area of artificial intelligence - is on the rise due to the abundance of data and computing power that have become available in the last years. While machine learning aims at finding patterns in the data, combined with planning, it enables the creation of intelligent systems that are capable of taking action based on observations in the data and desired goals.

In [a recent study](https://arxiv.org/pdf/1611.00873v1.pdf), scientists proposed to extract actionable knowledge from random forests – a compelling machine-learning algorithm for classification and regression. Given the results of such a classifier for a personal credit dataset, the article formulates an "*actionability problem to a sub-optimal action planning (SOAP) problem, which is to find a plan to alter certain features of a given input so that the random forest would yield a desirable output, while minimising the total costs of actions*". As an alternative to describing the problems in PDDL, the article proposes to use a novel formalism - SAS+. A solution to the SOAP problem is then found using Weighted Partial MaxSAT (WPMaxSAT) solver.

There is a great potential to such approach. As [a study by Forrester](https://albert.ai/forrester-study-ai-marketing/) demonstrates, it allows companies to combine their CRM data with the history of purchases and allow intelligent systems to perform specific actions aimed at achieving particular goals like increasing customer satisfaction, bringing in more leads, and improving retention rate.
