### Exercise 1. From a System to a Matrix
Write the system

```math
\begin{cases}
2x-y+z=4, \\
x+3y-2z=1, \\
3x+y+z=7.
\end{cases}
```

in the form $`Ax=b`$.
Identify the coefficient matrix, the vector of unknowns, and the right-hand side vector. Explain how each row of the matrix corresponds to one equation.

> **Why this exercise:** teaches how to move between a system of equations and matrix notation.

#### Answer

```math
\underbrace{\begin{pmatrix}2&-1&1\\1&3&-2\\3&1&1\end{pmatrix}}_{A}
\underbrace{\begin{pmatrix}x\\y\\z\end{pmatrix}}_{x}=
\underbrace{\begin{pmatrix}4\\1\\7\end{pmatrix}}_{b}
```

#### How I solved it
- **Coefficient matrix $`A`$:** copy the numbers in front of $`x,y,z`$ in each equation, keeping the same order. If a variable is missing, write $`0`$.
- **Unknowns vector:** $`(x,y,z)^T`$. **Right side:** $`(4,1,7)^T`$.

**Rows ↔ equations:** the first row $`(2,-1,1)`$ multiplied by $`(x,y,z)`$ gives $`2x-y+z`$, which must equal $`4`$. So each row of $`A`$ (with the matching entry of $`b`$) is exactly one equation.

---
