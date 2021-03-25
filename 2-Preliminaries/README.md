# 2 Preliminaries

## 2.1 Data Manipulation

1. Run the code in this section. Change the conditional statement X == Y in this section to X < Y or X > Y, and then see what kind of tensor you can get.

```
X = torch.arange(12, dtype=torch.float32).reshape((3, 4))
Y = torch.tensor([[2.0, 1, 4, 3], [1, 2, 3, 4], [4, 3, 2, 1]])
torch.cat((X, Y), dim=0), torch.cat((X, Y), dim=1)
lt,gt,eq = X< Y, X > Y, X == Y
```

2. Replace the two tensors that operate by element in the broadcasting mechanism with other shapes, e.g., 3-dimensional tensors. Is the result the same as expected?

```
a = torch.arange(3).reshape((3, 1,1))
b = torch.arange(2).reshape((1, 2, 1))
a + b
```

## 2.2 Data Preprocessing

Create a raw dataset with more rows and columns.

1. Delete the column with the most missing values.

2. Convert the preprocessed dataset to the tensor format.

## 2.3 Linear Algebra

<Skipped, refer to book forum for answers>

## 2.4 Calculus

<Skipped, refer to book forum for answers>

## 2.5

## 2.6 Probability

<Skipped, refer to book forum for answers>

## 2.5 Automatic Differentiation

<Skipped, refer to book forum for answers>

## 2.7 Documentation

1. Look up the documentation for any function or class in the deep learning framework. Can you also find the documentation on the official website of the framework?

Run `help(ones_like)` or go to [the pytorch website](https://pytorch.org/docs/stable/generated/torch.ones_like.html)
