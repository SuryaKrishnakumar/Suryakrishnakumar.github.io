---
layout: post
title: Machine Learning
author: "KN"
tags: [Machine Learning, Linear Regression, Gradient Descent, Python, R]
---

### Predict the Winner (Miami Marathon 2017)

> Done for <strong>COMP 551 (Applied Machine Learning)</strong> course at McGill University


The purpose of this project is to predict the final finishing time of the list of participants who have participated in the Miami Marathon 2017. To achieve this, I employed Linear Regression optimized with Gradient Descent Approach. Python was used for implementation.  

* The input was a raw data set which was curated from the web. It contained the performance of past participants' in Miami Marathon. The dataset included the details from 2003 to 2016

* Data Manipulation was done using 'R'. The raw dataset was widened across years. Each tuple is unique and referred to one participant.

* Then, the missing data issue was handled by Data Imputation (Predictive Mean Matching)

* This project involved K-Fold Cross Validation

* The final prediction was done and the Mean Squared Error was around 4000!
