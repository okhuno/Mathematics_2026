### Exercise 1. Determinant of a 2×2 Matrix
Compute

```math
\det
\begin{pmatrix}
3 & -2 \\
5 & 4 \\
\end{pmatrix},\qquad \det
\begin{pmatrix}
1 & 7 \\
2 & 14 \\
\end{pmatrix}.
```

Which matrix is invertible? Justify your answer.

> **Why this exercise:** introduces the simplest determinant calculation and immediately connects it with invertibility.

#### Answer
- First: $`22`$. Second: $`0`$.
- The **first** matrix is invertible; the second is not.

#### How I solved it
- First: $`3\cdot4-(-2)\cdot5=12+10=22`$.
- Second: $`1\cdot14-7\cdot2=14-14=0`$.

**Justification:** a matrix is invertible exactly when its determinant is nonzero. $`22\neq0`$, so the first is invertible. The second has determinant $`0`$ (its second row is $`2\times`$ the first row), so it is not.

---
