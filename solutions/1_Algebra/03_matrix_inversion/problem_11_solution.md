### Exercise 11. Parameter and Invertibility
For

```math
A(t)=
\begin{pmatrix}
1 & t \\
t & 1 \\
\end{pmatrix}
```

find all $`t`$ for which the matrix is invertible, and then give a formula for $`A(t)^{-1}`$. Explain what happens to this formula at the excluded values.

> **Why this exercise:** combines a parameter, determinant, and an explicit inverse formula in one problem.

#### Answer
- Invertible exactly when $`t\neq1`$ and $`t\neq-1`$.
- $`A(t)^{-1}=\dfrac1{1-t^2}\begin{pmatrix}1&-t\\-t&1\end{pmatrix}`$.

#### How I solved it
1. **Determinant:** $`\det A(t)=1\cdot1-t\cdot t=1-t^2`$.
2. **Invertible iff $`\det\ne0`$:** $`1-t^2\neq0\Rightarrow t\neq\pm1`$.
3. **Inverse formula** ($`2\times2`$: swap the diagonal, negate the off-diagonal, divide by the determinant): $`\frac1{1-t^2}\begin{pmatrix}1&-t\\-t&1\end{pmatrix}`$.

**At the excluded values:** at $`t=\pm1`$ we would divide by $`0`$, so the formula breaks down. Indeed:
- $`t=1`$: $`A=\begin{pmatrix}1&1\\1&1\end{pmatrix}`$, two identical rows.
- $`t=-1`$: $`A=\begin{pmatrix}1&-1\\-1&1\end{pmatrix}`$, the second row is $`-1`$ times the first.

In both cases the rows are dependent, so there is no inverse.

---
