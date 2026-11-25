### Exercise 13. Determinant by Elimination
Compute the determinant

```math
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 5 & 7 \\
1 & 0 & 2 \\
\end{pmatrix}
```

using elimination. Record the effect of every row operation used on the value of the determinant.

> **Why this exercise:** reinforces organizing a determinant calculation through row operations without introducing an unnecessary second procedure.

#### Answer

```math
\det A=1
```

#### How I solved it
1. $`R_2\leftarrow R_2-2R_1`$: $`(2,5,7)-(2,4,6)=(0,1,1)`$. **No change** to the determinant.
2. $`R_3\leftarrow R_3-R_1`$: $`(1,0,2)-(1,2,3)=(0,-2,-1)`$. **No change.**

```math
\begin{pmatrix}1&2&3\\0&1&1\\0&-2&-1\end{pmatrix}
```

3. $`R_3\leftarrow R_3+2R_2`$: $`(0,-2,-1)+(0,2,2)=(0,0,1)`$. **No change.**

```math
\begin{pmatrix}1&2&3\\0&1&1\\0&0&1\end{pmatrix}
```

4. Triangular: $`\det=1\cdot1\cdot1=1`$.

All operations were "add a multiple of a row to another row," so the determinant stayed the same throughout: $`\det A=1`$.

**Check (Sarrus):** down-right: $`1\cdot5\cdot2+2\cdot7\cdot1+3\cdot2\cdot0=10+14+0=24`$. Up-right: $`3\cdot5\cdot1+1\cdot7\cdot0+2\cdot2\cdot2=15+0+8=23`$. $`24-23=1`$ ✓.

---
