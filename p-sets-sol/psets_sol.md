# Solution

> MIT-18.065

## Problems for Lecture 1 

**1**.

A combination of three nonzero vectors in $\mathbb{R^4}$ is the zero vector
$$
\begin{bmatrix}
1\\2\\1\\0
\end{bmatrix}+\begin{bmatrix}
1\\1\\2\\1
\end{bmatrix}-\begin{bmatrix}
2\\3\\3\\1
\end{bmatrix}=\bold{0}
$$
Form $A\bold{x}=0$
$$
\begin{bmatrix}
1&1&2\\2&1&3\\1&2&3\\0&1&3
\end{bmatrix}\begin{bmatrix}
1\\1\\-1
\end{bmatrix}=\begin{bmatrix}
0\\0\\0
\end{bmatrix}
$$
**4**.We can easily find $x=[1,-1,0]^T,y=[0,1,-1]^T,z =x+y$

**9**.$m=3,n\ge3,r=3$

**18**.
$$
\begin{bmatrix}
1\\1\\\cdots
\end{bmatrix}\begin{bmatrix}
0&\cdots&R
\end{bmatrix}
$$

## Problems for Lecture 2

**2**.yes; m by p; $a_i\times {b_j}^T$; It is a symmetric matrix 

**6**.
$$
a_ib_i^*=\begin{bmatrix}
(0)&a_i&(0)
\end{bmatrix}\qquad i=1,2,3
$$

## Problems for Lecture 3

**2**.![3ia3q.png](https://i.328888.xyz/2023/02/08/3ia3q.png)

Clearly, we have
$$
u^Tw=0
$$
[![3VStU.png](https://i.328888.xyz/2023/02/08/3VStU.png)](https://imgloc.com/i/3VStU)

**4**.
$$
(Qx)^T(Qy)=x^TQ^TQy=x^Ty
$$
6.$0$; $P^T$

## Problems for Lecture 4

**2**.the eigenvalues of $A$ are $2,1$ and the corresponding eigenvectors are $[1,1]^T$ and $[-2,1]^T$ respectively.

the eigenvalues of $A^{-1}$ are $\frac{1}{2},-1$ and the corresponding eigenvectors are $[1,1]^T$ and $[-2,1]^T$ respectively.

$A^{-1}$ has the <u>same</u> eigenvectors as $A$. When $A$ has eigenvalues $\lambda_1$ and $\lambda_2$ its inverse has eigenvalues $\frac{1}{\lambda_1}$ and $\lambda_2$

**11**.The eigenvalues of $A$ equal the eigenvalues of $A^T$. This is because $det(A-\lambda I)$ equals $det(A^T-\lambda I)$. That is true because $det[(A-\lambda I)^T]=det(A^T-\lambda I)$. 

**15**.(a) 
$$
A=\begin{bmatrix}
1&2\\0&3\\
\end{bmatrix}
$$
computing the eigenvalues of $A$, we get $1,3$ (actually we do not need to compute, because it is a upper triangular matrix ). Then computing the eigenvectors respectively, we gets $[1,0]^T$ and $[1,1]^T$ .Hence we know
$$
\Lambda=\begin{bmatrix}
1&0\\0&3
\end{bmatrix}\qquad X=\begin{bmatrix}
1&1\\0&1
\end{bmatrix}\qquad X^{-1}=\begin{bmatrix}
1&-1\\0&1
\end{bmatrix}
$$
(b) If $A=X\Lambda X^{-1}$ then $A^3=X\Lambda^3X^{-1}$ and $A^{-1}=X\Lambda^{-1}X^{-1}$

## Problems for Lecture 5

3.

The  $LDL^T$ forms are:
$$
\begin{bmatrix}
1&0\\b&1
\end{bmatrix}
\begin{bmatrix}
1&0\\0&9-b^2
\end{bmatrix}
\begin{bmatrix}
1&b\\0&1
\end{bmatrix}
$$

$$
\begin{bmatrix}
1&0\\2&1
\end{bmatrix}
\begin{bmatrix}
2&0\\0&c-8
\end{bmatrix}
\begin{bmatrix}
1&2\\0&1
\end{bmatrix}
$$

$$
\begin{bmatrix}
1&0\\b/c&1
\end{bmatrix}
\begin{bmatrix}
c&0\\0&(c^2-b^2)/c
\end{bmatrix}
\begin{bmatrix}
1&b/c\\
0&1
\end{bmatrix}
$$

The first matrix is positive definite for $-3<b<3$, the second for $c>8$, and the third both $c>0$ and $c^2-b^2>0$. The latter can be combined into $c>|b|$

14.
$$
S=4\begin{bmatrix}
1&-1&2\\-1&1&-2\\2&-2&4
\end{bmatrix}
$$
$Rank=1$ . the pivots are $4,0,0$ the eigenvalues are $24,0,0$ and the determinant is $0$

15.

$det_1=2$ $det_2=6$ $det_3=30$

$pivot_1=2$ $pivot_2=\frac{6}{2}=3$ $pivot_3=\frac{30}{6}=5$

## Problems for Lecture 6

1.

6.

## Problems for Lecture 7

2.

10.

## Problems for Lecture 8

1.

7.

## Problems for Lecture 9

2.

8.

9.

## Problems for Lecture 10

12.

17.

## Problems for Lecture 11

6.

10.

## Problems for Lecture 12

1.

## Problems for Lecture 13

1.

4.

## Problems for Lecture 14

1.

4.

## Problems for Lecture 15

1.

2.

5.

## Problems for Lecture 16

3.

12.

## Problems for Lecture 17

2.

6.

## Problems for Lecture 18

4.

10.

## Problems for Lecture 19

3.

8.

## Problems for Lecture 20

10.

12.

3.

## Problems for Lecture 21

1.

5.

## Problems for Lecture 22

1.

6.

## Problems for Lecture 23

5.

## Problems for Lecture 24

1.

2.

5.

## Problems for Lecture 25

1.

## Problems for Lecture 26

4.

7.

## Problems for Lecture 27

2.

5.

## Problems for Lecture 30

3.

1.

## Problems for Lecture 31

3.

5.

## Problems for Lecture 32

4.

## Problems for Lecture 33

5.

2.

## Problems for Lecture 34

1.

## Problems for Lecture 35

1.

