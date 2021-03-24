# 2 Preliminaries

## 2.1 Data Manipulation

1. Run the code in this section. Change the conditional statement X == Y in this section to X < Y or X > Y, and then see what kind of tensor you can get.

2. Replace the two tensors that operate by element in the broadcasting mechanism with other shapes, e.g., 3-dimensional tensors. Is the result the same as expected?#

## 2.2 Data Preprocessing

Create a raw dataset with more rows and columns.

1. Delete the column with the most missing values.

2. Convert the preprocessed dataset to the tensor format.

## 2.3 Linear Algebra

<Skipped, refer to book forum for answers>

## 2.4 Calculus

<Skipped, refer to book forum for answers>

## 2.5

1. Why is the second derivative much more expensive to compute than the first derivative?

2. After running the function for backpropagation, immediately run it again and see what happens.

3. In the control flow example where we calculate the derivative of d with respect to a, what would happen if we changed the variable a to a random vector or matrix. At this point, the result of the calculation f(a) is no longer a scalar. What happens to the result? How do we analyze this?

Redesign an example of finding the gradient of the control flow. Run and analyze the result.

4. Let 𝑓(𝑥)=sin(𝑥) . Plot 𝑓(𝑥) and 𝑑𝑓(𝑥)𝑑𝑥 , where the latter is computed without exploiting that 𝑓′(𝑥)=cos(𝑥) .

## 2.6 Probability

<Skipped, refer to book forum for answers>

## 2.7 Documentation

1. Look up the documentation for any function or class in the deep learning framework. Can you also find the documentation on the official website of the framework?

Run `help(ones_like)` or go to [the pytorch website](https://pytorch.org/docs/stable/generated/torch.ones_like.html)
