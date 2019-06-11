---
title: Stochastic Gradient Descent
author: andrea perlato
date: '2019-06-11'
slug: stochastic-gradient-descent
categories:
  - artificial intelligence
tags:
  - stochastic gradient descent
---

<style>
body {
text-align: justify}
</style>

Is [**Gradient Descent**](https://andrea-perlato.netlify.com/theorypost/gradient-descent-step-by-step/), we used the sum of the squared residuals as the Loss Function to determine how well the initial line fit the data. Than, we took the derivative of the sum of the squared residuals with respect to the intercept and slope. We repeated that process a lot of times untill we took the maximum number of steps, or the spteps became very, very small.

Now, imag to have a Logistic Regression that used 10000 genes to predict if someone will have a disease. This means, we would have 10000 derivatives to plug the data into. so, for Big Data, Gradient Descent is too slow. This is where Stochastic Gradient Descent comes in handy.


