### Exercise 5. Matrix Times Vector
Let

```math
A=
\begin{pmatrix}
2 & -1 \\
1 & 3 \\
\end{pmatrix},\qquad x=
\begin{pmatrix}
4 \\
2 \\
\end{pmatrix}.
```

Compute $`Ax`$. Then express $`Ax`$ as a linear combination of the columns of $`A`$, with coefficients coming from the vector $`x`$.

> **Why this exercise:** shows that multiplying a matrix by a vector can be understood as a linear combination of the matrix columns.

#### Answer

```math
Ax=\begin{pmatrix}6\\10\end{pmatrix}=4\begin{pmatrix}2\\1\end{pmatrix}+2\begin{pmatrix}-1\\3\end{pmatrix}
```

#### How I solved it
- **Row times vector:** $`2\cdot4+(-1)\cdot2=6`$ and $`1\cdot4+3\cdot2=10`$.
- **As a combination of columns:** the columns of $`A`$ are $`(2,1)^T`$ and $`(-1,3)^T`$. The coefficients are the entries of $`x`$: $`4`$ and $`2`$.

```math
4\begin{pmatrix}2\\1\end{pmatrix}+2\begin{pmatrix}-1\\3\end{pmatrix}=\begin{pmatrix}8\\4\end{pmatrix}+\begin{pmatrix}-2\\6\end{pmatrix}=\begin{pmatrix}6\\10\end{pmatrix}\ ✓
```

Both ways give the same vector.

---
