---
layout: post
title:  "Interesting AI research that requires little compute"
date:   2019-06-08 14:30:01 +0200
categories: jekyll update
excerpt: Showing some little things to see what you can do with your machine learning knowledge with fairly little computing power.
---

- Mathematical Reasioning 
Descriptive Statement. Mathematical reasoning is the critical skill that enables a student to make use of all other mathematical skills. With the development of mathematical reasoning, students recognize that mathematics makes sense and can be understood.

- Novel activation functions
Learning Activation Functions to Improve Deep Neural Networks. Artificial neural networks typically have a fixed, non-linear activation function at each neuron. We have designed a novel form of piecewise linear activation function that is learned independently for each neuron using gradient descent.

- 2nd order optimization 
The term "first order method" is often used to categorize a numerical optimization method for say constrained minimization, and similarly for a "second order method".It uses the second order derivatives (Hessian) and has quadratic convergence rate.
<div class="imgcap">
<img src="/assets/nncompute/2ndorfder.jpg">
</div>

- Neural Ordinary Differential Equations
Instead of specifying a discrete sequence of hidden layers, we parameterize the derivative of the hidden state using a neural network. The output of the network is computed using a black-box differential equation solver. These continuous-depth models have constant memory cost, adapt their evaluation strategy to each input, and can explicitly trade numerical precision for speed. We demonstrate these properties in continuous-depth residual networks and continuous-time latent variable models. We also construct continuous normalizing flows, a generative model that can train by maximum likelihood, without partitioning or ordering the data dimensions. For training, we show how to scalably backpropagate through any ODE solver, without access to its internal operations. This allows end-to-end training of ODEs within larger models.
<div class="imgcap">
<img src="/assets/nncompute/neuraldiff.png">
</div>

Follow me on twitter for more updates [@LeonHillmann](https://twitter.com/LeonHillmann)