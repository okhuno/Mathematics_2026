### Exercise 3. Inconsistent System
Solve or show that the system is inconsistent:

```math
\begin{cases}
x+2y=3, \\
2x+4y=7.
\end{cases}
```

Show how the contradiction appears in the matrix after elimination and interpret it in terms of equations.

> **Why this exercise:** teaches how to recognize that a system has no solution without guessing.

#### Answer
**No solution** (the system is inconsistent).

#### How I solved it

```math
\left(\begin{array}{cc|c}1&2&3\\2&4&7\end{array}\right)\xrightarrow{R_2\leftarrow R_2-2R_1}\left(\begin{array}{cc|c}1&2&3\\0&0&1\end{array}\right)
```

The last row says $`0\cdot x+0\cdot y=1`$, i.e. $`0=1`$, which is impossible.

**Interpretation:** the left side of the second equation is exactly twice the left side of the first ($`2x+4y=2(x+2y)`$). If $`x+2y=3`$, then $`2x+4y`$ must be $`6`$, not $`7`$. In the plane these are two **parallel** lines that never meet.

---
