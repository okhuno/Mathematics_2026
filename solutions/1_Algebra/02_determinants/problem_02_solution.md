### Exercise 2. Determinant of a 3×3 Matrix
For

```math
A=
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 4 \\
2 & 1 & 5 \\
\end{pmatrix}
```

compute $`\det A`$ using Sarrus' rule. Then perform one simple check using a chosen property of the determinant.

> **Why this exercise:** teaches a basic method for $`3\times3`$ matrices and builds the habit of checking the result without adding a second full solution.

#### Answer

```math
\det A=33
```

#### How I solved it
**Sarrus:** write the first two columns again to the right of the matrix.

```math
\begin{array}{ccc|cc}1&2&-1&1&2\\0&3&4&0&3\\2&1&5&2&1\end{array}
```

- **Down-right diagonals (add):** $`1\cdot3\cdot5+2\cdot4\cdot2+(-1)\cdot0\cdot1=15+16+0=31`$.
- **Up-right diagonals (subtract):** $`(-1)\cdot3\cdot2+1\cdot4\cdot1+2\cdot0\cdot5=-6+4+0=-2`$.
- $`\det A=31-(-2)=33`$.

**Check with a property:** replacing $`R_3`$ by $`R_3-2R_1`$ does not change the determinant: $`R_3=(2,1,5)-(2,4,-2)=(0,-3,7)`$. The new matrix $`\begin{pmatrix}1&2&-1\\0&3&4\\0&-3&7\end{pmatrix}`$ has first column $`(1,0,0)^T`$, so its determinant is $`1\cdot(3\cdot7-4\cdot(-3))=21+12=33`$ ✓.

---
