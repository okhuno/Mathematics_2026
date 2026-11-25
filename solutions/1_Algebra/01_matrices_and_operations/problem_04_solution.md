### Exercise 4. Matrix Multiplication and Noncommutativity
For

$$
A=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
2 & 0 \\
3 & 1 \\
\end{pmatrix}
$$

compute $AB$ and $BA$. Is $AB=BA$? Use this example to explain what noncommutativity of matrix multiplication means.

> **Why this exercise:** shows one of the most important differences between matrix multiplication and multiplication of numbers.

#### Answer
$$AB=\begin{pmatrix}8&2\\3&1\end{pmatrix},\qquad BA=\begin{pmatrix}2&4\\3&7\end{pmatrix},\qquad AB\neq BA.$$

#### How I solved it
Each entry is (row of the first matrix) $\cdot$ (column of the second).

$AB$:
- $(1,1)$: $1\cdot2+2\cdot3=8$
- $(1,2)$: $1\cdot0+2\cdot1=2$
- $(2,1)$: $0\cdot2+1\cdot3=3$
- $(2,2)$: $0\cdot0+1\cdot1=1$

$BA$:
- $(1,1)$: $2\cdot1+0\cdot0=2$
- $(1,2)$: $2\cdot2+0\cdot1=4$
- $(2,1)$: $3\cdot1+1\cdot0=3$
- $(2,2)$: $3\cdot2+1\cdot1=7$

**Meaning:** $AB\neq BA$. Unlike numbers ($2\cdot3=3\cdot2$), the **order of matrix multiplication matters**: multiplying in a different order gives a different result in general.

---
