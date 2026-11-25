### Exercise 1. Definition of the Inverse
For

```math
A=
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & -1 \\
-1 & 2 \\
\end{pmatrix}
```

check, without using a formula, whether $`B=A^{-1}`$. Compute $`AB`$ and $`BA`$ and relate the result to the definition of the inverse.

> **Why this exercise:** starts from the definition of the inverse through multiplication before any formulas or computational methods are introduced.

#### Answer
$`AB=BA=I`$, so $`B=A^{-1}`$.

#### How I solved it

```math
AB=\begin{pmatrix}2\cdot1+1\cdot(-1)&2\cdot(-1)+1\cdot2\\1\cdot1+1\cdot(-1)&1\cdot(-1)+1\cdot2\end{pmatrix}=\begin{pmatrix}1&0\\0&1\end{pmatrix}
```

```math
BA=\begin{pmatrix}1\cdot2+(-1)\cdot1&1\cdot1+(-1)\cdot1\\-1\cdot2+2\cdot1&-1\cdot1+2\cdot1\end{pmatrix}=\begin{pmatrix}1&0\\0&1\end{pmatrix}
```

**Relation to the definition:** $`B`$ is the inverse of $`A`$ exactly when $`AB=I`$ and $`BA=I`$. Both hold, so $`B=A^{-1}`$.

---
