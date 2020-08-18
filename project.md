---
mathjax: true
title: STAT 350 Summer 2020
---

{% include mathjax.html %}

# Final Project Info

## Overview

Your task is to prepare two lectures exploring two random processes. You can work with a partner on this project. 
The project is due on Friday, August 21. On that day, there will be optional final presentations. You may attend the 
final presentation session or submit a pre-recorded video.

## Task

Choose two of the following random processes.

1. Start with white noise $\\{ Z[n] \\}$ consisting of i.i.d. random variables with mean $E[Z[n]] = 1$ and 
variance $\text{Var}[Z[n]] = 4$. Study the moving average process $\\{ X[n] \\}$:

    $$ X[n] = 0.8 Z[n] + 0.3 Z[n-1] - 0.1 Z[n-2]. $$

2. Let $\Theta$ be a $\text{Uniform}(a=-\pi, b=\pi)$ random variable. Define a signal with random phase

    $$ X(t) = \cos(2\pi \cdot 300 t + \Theta). $$

3. Consider a particle moving according to $\{ B(t) \}$ be Brownian motion with scale $\alpha = 3$ mm/s. Define the difference process 

    $$ D(t) = B(t) - B(t - 5), t \geq 5, $$

    which represents how far the particle has traveled in the last 5 seconds.
    
For each scenario:

1. Graph at least three realizations of the process. (The graph can be made using any software that you choose. Even a neat handdrawing will suffice.)
2. Calculate the mean and autocovariance functions. 
3. Is the process stationary?
4. Calculate and graph the power spectral density of this process.
5. Define a linear time-invariant filter (your choice -- be creative!), and pass this process through that filter.

## Resources

You may find Chapters 7 and 8 in the textbook _Probability with Applications in Engineering, Science, and Technology_ helpful. 
A PDF of this book is available for free 
[online through the Cal Poly Library](https://link-springer-com.ezproxy.lib.calpoly.edu/book/10.1007%2F978-3-319-52401-6).

## Deliverables

1. A lesson, which can take many forms (e.g., Colab notebook, slides, video, website). You may assume that the 
audience has taken STAT 350, but they may not have studied these particular scenarios. So you don't need to spend 
time defining "autocovariance function" or the "Filter Theorem". However, it is still helpful if you connect your 
calculations to the definitions and interpret your calculations in context. In other words, it may be a good idea to remind the 
listener about definitions, but there is no need to teach the concept from scratch.
2. Your presentation of the lesson, which you can do in the presentation session or record as a video. (Note: If your lesson 
itself is a video, you may skip this step.)

## Grading

Grading will be based on the following rubric:

- Correctness (100 points): 50 points for each process, based on...
    - Graph of the process
    - Calculation of the mean and autocovariance functions
    - Calculation and graph of the power spectral density
    - Defining an appropriate filter and correct calculation of the power spectral density at the output of the filter.
- Clarity (100 points)
    - Are topics ordered in a logical way?
    - Are the verbal explanations clear and concise?
    - Does the lesson strike the right balance of equations, text, and graphics? 
    (All three are necessary. But too much of one is not desirable.)
- Aesthetics and Presentation (100 points)
    - Does the lesson capture the listener's interest?
    - Is the lesson visually appealing?
    - Is technical content (e.g., equations) formatted in a way that is easy for the audience to read?
    - For group projects, both partners should talk equally in the presentation. 
    (It is not okay to have one person present one process and the other person present the other process.) 
    One suggestion is to frame the presentation as a dialogue or conversation.
