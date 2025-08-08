# Joint_Distribution_Probability_In_Python
Practical demonstration of joint probability distribution with visualizations and analysis using Python.


📊 Introduction to Joint Distribution – Practical


This project provides a practical introduction to Joint Probability Distribution using Python. 


It demonstrates how to represent and analyze the probability of multiple random variables occurring together, along with visualizations for better understanding.

🎯 Objective


Understand the concept of Joint Probability Distribution

Represent probabilities for two or more random variables

Represent probabilities using a 2D table or matrix

Compute:

Joint probabilities

Marginal distributions

Conditional probabilities



Visualize relationships using heatmaps, bar plots, and distribution plots

Explore marginal and conditional probabilities



📚 Theoretical Background

Joint Distribution defines the probability of two (or more) random variables occurring simultaneously.

If 
𝑋
X and 
𝑌
Y are random variables:



P(X=x,Y=y)=f(x,y)


Marginal Distribution can be obtained by summing over one variable:


P(X=x)= 
y
∑
​
 P(X=x,Y=y)


Conditional Distribution:

P(X=x∣Y=y)= 
P(Y=y)
P(X=x,Y=y)
​
🔹 Key Concepts Covered


| Concept                     | Explanation                                             |
| --------------------------- | ------------------------------------------------------- |
| **Joint Probability**       | Probability of two events occurring together            |
| **Marginal Probability**    | Sum of joint probabilities across rows/columns          |
| **Conditional Probability** | Probability of one event given another                  |
| **Independence Check**      | If `P(X,Y) = P(X) * P(Y)`, then X and Y are independent |
| **Visualization**           | Heatmaps, bar plots, 3D surface plots                   |



📂 Features


Define sample space and probabilities

Create joint probability tables

Compute marginal and conditional probabilities

Visualize distributions with Matplotlib and Seaborn
