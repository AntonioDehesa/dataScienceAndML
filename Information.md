# What is Machine Learning

## Supervised learning

By showing tons of examples of what we want to a computer, it will learn about it (super simplification). That is supervised learning. 

# Data Science

Turning data into value. 

## Data mining

The application of specific algorithms for extracting patterns from data. 

## Business intelligence

Using this harvested data to be able to market your products in a more efficient way. 

## Hierarchy of (Data Science) needs

From lowest to highest: 

### Collect
Instrumentation, logging, sensors, external data, user generated content

### Move/Store

Reliable data flow, infrastructure, pipelines, etl, structured and unstructured data storage

### Explore/Transform

Cleaning, anomaly detection, prep

### Aggregate/Label

Analytics, metrics, segments, aggregates, features, training data

### Learn/optimize

A/B testing, experimentation, simple ML algorithms

### AI, Deep Learning

## Steps to solve a problem

### Formulate question

it is the most important step. It will affect everything: the research, the kind of data to gather, etc. 

### Gather data

Gather the data that you think will help you solve the problem 

### Clean data

In the real world, the data you get is messy. So, you have to clean it and prepare it

### Explore and visualize

See the gathered data, which will help you understand better 

### Train algorithm

In this case, linear regression (for a first step)

### Evaluate

Evaluate the results from your algorithm / model

## Intuition behind the Linear Regression

It uses an independent variable (known as Feature) and a dependent variable, known as Target. 
It represents their relationship. 

It is the slope of the change => y = m*x + c

The values of c and m would be parameters, which we would not know in true machine learning. 

y = m*x + c ::: h \theta (x) = theta0 + theta1*x

### Residuals

They are the difference between the predicted value with the slope, and the actual value. 

We need to use the slope that minimizes the sum of the square of the residuals. 


## Section 4 

Introduction to Optimization and the Gradient Descent Algorithm

We are going to see how a machine learns. 
I have already taken college classes about it, but its good to see it again. 

### How a machine learns

Step 1: Make a prediction: for example, the coefficients in a linear function. 
Step 2: Calculate the error: test how good was the prediction
Step 3: Learn
Then go back to step one, over and over again. 


### Introduction to Cost Functions

Optimization involves finding the solution with the lowest cost. those are the cost functions. 

Also named loss or error function. 

#### Residual sum of squares (RSS)

The sum of the squares of the differences between the predicted values and the actual values. This gives us a metric for how good our, say, coefficients, are. 

It basically measures the side of out error. 


* Concave functions are like mountains: a peak, and the rest of it is at a lower point
* Convex is like a valley: a lower point, surrounded by higher points. 

#### Gradient Descent

An algorith to find the minimum of a function. It looks, step by step, a lower point, and a lower point, until it cannot find a lower point. It has the disadvantage of falling into a false bottom, a local minimum, and not a global minimum. 