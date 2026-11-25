### Exercise 6. Parameter and Invertibility
For

```math
A(t)=
\begin{pmatrix}
t & 1 \\
2 & t \\
\end{pmatrix}
```

find all values of $`t`$ for which the matrix is not invertible. Explain how your answer is related to the determinant being zero.

> **Why this exercise:** shows how the determinant can be used to study a family of matrices depending on a parameter.

#### Answer
Not invertible for $`t=\sqrt2`$ and $`t=-\sqrt2`$.

#### How I solved it
1. $`\det A(t)=t\cdot t-1\cdot2=t^2-2`$.
2. A matrix is **not** invertible exactly when $`\det=0`$: $`t^2-2=0\Rightarrow t=\pm\sqrt2`$.

**Connection:** for $`t=\sqrt2`$ the rows are $`(\sqrt2,1)`$ and $`(2,\sqrt2)=\sqrt2\cdot(\sqrt2,1)`$, so the second row is a multiple of the first (dependent rows). That is exactly what a zero determinant signals.

---
