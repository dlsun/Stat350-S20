---
layout: post
mathjax: true
title: STAT 350 Summer 2020
---

# Final Project Info

## Overview

Your task is to prepare two lectures exploring two random processes. You can work with a partner on this project. 
The project is due on Friday, August 19. On that day, there will be optional final presentations. You may attend the 
final presentation session or submit a pre-recorded video.

## Task

Choose two of the following random processes.

1. Let $\{ Z[n] \}$ be white noise with power $\sigma^2 = 4$. Define the moving average process
\[ X[n] = 0.8 Z[n] + 0.3 Z[n-1] - 0.1 Z[n-2].  \]
2. Let $\Theta$ be a $\text{Uniform}(a=-\pi, b=\pi)$ random variable. Define a signal with random phase
\[ X(t) = \cos(2\pi \cdot 300 t + \Theta). \]
3. Consider a particle moving according to $\{ B(t) \}$ be Brownian motion with scale $\sigma = 3$ mm. Define the difference process 
\[ D(t) = B(t) - B(t - 5), t \geq 5 \]
which represents how far the particle has traveled in the
    
For each scenario:

1. Graph at least three realizations of the process.
2. Calculate the mean and autocovariance functions. 
3. Is the process stationary?
4. Calculate and graph the power spectral density of this process.
5. Define a linear time-invariant filter, and pass this process through that filter.

## Resources

You may find Chapters 7 and 8 in this textbook (_Probability with Applications in Engineering, Science, and Technology_) helpful. 
A PDF of this book is available for free online 
[https://link-springer-com.ezproxy.lib.calpoly.edu/book/10.1007%2F978-3-319-52401-6](through the Cal Poly Library).

## Deliverables

1. A lesson, which can take many forms (e.g., Colab notebook, slides, video, website).
2. Your presentation of the lesson, which you can do in the presentation session or record as a video. (Note: If your lesson 
itself is a video, you may skip this step.)

## Grading

Grading will be based on correctness (100 points), clarity (100 points), and aesthetics (100 points).
