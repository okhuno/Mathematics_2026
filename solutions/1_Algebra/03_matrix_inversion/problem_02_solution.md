### Exercise 2. Formula for a 2×2 Matrix
Find the inverse of

```math
A=
\begin{pmatrix}
3 & 2 \\
5 & 4 \\
\end{pmatrix}
```

using the formula for a $`2\times2`$ matrix. At the end, check the result by computing one product with $`A`$.

> **Why this exercise:** teaches the simplest explicit formula for an inverse and requires verification using the definition.

#### Answer

```math
A^{-1}=\frac12\begin{pmatrix}4&-2\\-5&3\end{pmatrix}=\begin{pmatrix}2&-1\\-\frac52&\frac32\end{pmatrix}
```

#### How I solved it
1. **Determinant:** $`ad-bc=3\cdot4-2\cdot5=12-10=2\ne0`$, so the inverse exists.
2. **Formula:** swap the diagonal entries ($`3\leftrightarrow4`$), change the signs of the off-diagonal entries ($`2\to-2`$, $`5\to-5`$), and divide by the determinant:

```math
A^{-1}=\frac12\begin{pmatrix}4&-2\\-5&3\end{pmatrix}.
```

**Check ($`AA^{-1}`$):**

```math
\begin{pmatrix}3&2\\5&4\end{pmatrix}\begin{pmatrix}2&-1\\-\frac52&\frac32\end{pmatrix}=\begin{pmatrix}6-5&-3+3\\10-10&-5+6\end{pmatrix}=\begin{pmatrix}1&0\\0&1\end{pmatrix}\ ✓
```

---
