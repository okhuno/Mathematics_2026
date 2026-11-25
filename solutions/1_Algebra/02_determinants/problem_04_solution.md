### Exercise 4. Triangular Matrix
Without expanding the determinant, compute

```math
\det
\begin{pmatrix}
2 & 4 & 1 \\
0 & -3 & 5 \\
0 & 0 & 7 \\
\end{pmatrix}.
```

State the rule for an arbitrary triangular matrix and explain it using this example.

> **Why this exercise:** reinforces an important property of triangular matrices.

#### Answer

```math
\det=2\cdot(-3)\cdot7=-42
```

#### How I solved it
The matrix is upper triangular (all entries below the diagonal are $`0`$), so the determinant is the product of the diagonal entries: $`2\cdot(-3)\cdot7=-42`$.

**Rule:** for any triangular matrix (upper or lower), $`\det=`$ product of diagonal entries.

**Why (in this example):** expand along the first column. Only the top entry $`2`$ is nonzero, so $`\det=2\cdot\det\begin{pmatrix}-3&5\\0&7\end{pmatrix}`$. The remaining $`2\times2`$ matrix is again triangular and its determinant is $`(-3)\cdot7-5\cdot0=-21`$. So $`\det=2\cdot(-21)=-42`$, i.e. $`2\cdot(-3)\cdot7`$.

---
