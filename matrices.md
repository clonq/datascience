Matrices
===

Definitions
---

A `matrix` is an ordered rectangular array of numbers or functions.

The numbers, symbols or expressions in the matrix are called its `entries` or its `elements`. The horizontal and vertical lines of entries in a matrix are called `rows` and `columns`, respectively.

The number of rows and columns that a matrix has is called its `order` or its `dimension`.

A matrix with m rows and n columns is called an `m × n matrix` or `m-by-n matrix`, while m and n are called its `dimensions`.

Matrices which have a single row are called `row vectors`, and those which have a single column are called `column vectors`. 

A matrix is said to be a `column matrix` if it has only one column.

A matrix is said to be a `row matrix` if it has only one row.

A matrix in which the number of rows is equal to the number of columns is said to be a `square matrix`.

A square matrix is said to be a `diagonal matrix` if all its non diagonal elements are zero.

A diagonal matrix is said to be a `scalar matrix` if its diagonal elements are equal.

An `identity matrix` is a special case of scalar matrix, with the diagonal elements equal to one.

A matrix is said to be `zero matrix` or `null matrix` if all its elements are zero.

A square matrix is called `lower triangular` if all the entries above the main diagonal are zero. Similarly, a square matrix is called `upper triangular` if all the entries below the main diagonal are zero.

A `submatrix` of a matrix is obtained by deleting any collection of rows and/or columns.


Basic Operations
---

The `sum` A+B of two m-by-n matrices A and B is calculated entrywise:

```
(A + B)i,j = Ai,j + Bi,j, where 1 ≤ i ≤ m and 1 ≤ j ≤ n. 
```
Two matrices must have an equal number of rows and columns to be added.

`Scalar multiplication`, the product cA of a number c and a matrix A is computed by multiplying every entry of A by c: 

```
(cA)i,j = c · Ai,j
```

The `transpose` of an m-by-n matrix A is the n-by-m matrix AT (also denoted Atr or tA) formed by turning rows into columns and vice versa:

```
(AT)i,j = Aj,i
``` 

If A is an m-by-n matrix and B is an n-by-p matrix, then their `matrix product` AB is the m-by-p matrix whose entries are given by dot product of the corresponding row of A and the corresponding column of B:

![](https://upload.wikimedia.org/math/6/a/f/6afda1b6d29007cd0b93b39e653784d9.png)

The `dot product` of two vectors A = [A1, A2, ..., An] and B = [B1, B2, ..., Bn] is defined as:

![](https://upload.wikimedia.org/math/9/4/d/94d092558445b6aa77739fa99dea4dbc.png")

Multiplication of two matrices is defined if and only if the number of columns of the left matrix is the same as the number of rows of the right matrix.
