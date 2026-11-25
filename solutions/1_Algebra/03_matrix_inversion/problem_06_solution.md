### Exercise 6. Solving a System Using the Inverse
Solve

```math
Ax=b,
```

where

```math
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix},
```

using $`x=A^{-1}b`$. Then substitute the resulting vector back into the equation and check the result.

> **Why this exercise:** shows the connection between inverse matrices and solving a linear system.

#### Answer

```math
x=\begin{pmatrix}\frac85\\[2pt]\frac95\end{pmatrix}
```

#### How I solved it
1. **Determinant:** $`2\cdot3-1\cdot1=5`$.
2. **Inverse:** $`A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix}`$.
3. **Multiply:** $`x=A^{-1}b=\frac15\begin{pmatrix}3\cdot5-1\cdot7\\-1\cdot5+2\cdot7\end{pmatrix}=\frac15\begin{pmatrix}8\\9\end{pmatrix}`$.

**Check:** $`2\cdot\frac85+\frac95=\frac{25}5=5`$ ✓ and $`\frac85+3\cdot\frac95=\frac{35}{5}=7`$ ✓.

**Why it works:** multiply $`Ax=b`$ on the left by $`A^{-1}`$: $`A^{-1}Ax=Ix=x=A^{-1}b`$.

---
