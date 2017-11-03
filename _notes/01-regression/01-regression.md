## What is Regression
  Find a function, input data to it and get a scalar

## Step 1: Find a set of function
  Linear model:  y = b + sum(wi * xi)

  b : bias
  wi: weight
  xi: feature, an attribute of input x

## Step 2: Goodness of function
  Loss function L
    input : a function
    output: how bad it is

  L(f) = L(w, b) = Sum((yn - (b + w * xcp)^2)

## Step 3: Best function
  Pick the best function, make the L(f) has min value
  - Gradient Descent 梯度下降
  - Learning rate
  
