### Exercise 11. Shortening the Calculation with Row Operations
Compute

```math
\det
\begin{pmatrix}
1 & 2 & 3 \\
1 & 3 & 4 \\
1 & 4 & 6 \\
\end{pmatrix}
```

by first performing row operations that create as many zeros as possible. State which operations do not change the determinant.

> **Why this exercise:** develops planning instead of mechanically repeating the same procedure.

#### Answer

```math
\det=1
```

#### How I solved it
1. $`R_2\leftarrow R_2-R_1`$: $`(0,1,1)`$.
2. $`R_3\leftarrow R_3-R_1`$: $`(0,2,3)`$.

```math
\begin{pmatrix}1&2&3\\0&1&1\\0&2&3\end{pmatrix}
```

3. $`R_3\leftarrow R_3-2R_2`$: $`(0,0,1)`$.

```math
\begin{pmatrix}1&2&3\\0&1&1\\0&0&1\end{pmatrix}
```

4. Triangular: $`\det=1\cdot1\cdot1=1`$.

**Which operations do not change the determinant:** all three were of the type "add (or subtract) a multiple of one row to/from another row." These never change the determinant. (Swapping rows would flip the sign, and multiplying a row by $`k`$ would multiply the determinant by $`k`$; we used neither.)

**Check (Sarrus on the original):** down-right: $`1\cdot3\cdot6+2\cdot4\cdot1+3\cdot1\cdot4=18+8+12=38`$. Up-right: $`3\cdot3\cdot1+1\cdot4\cdot4+2\cdot1\cdot6=9+16+12=37`$. $`38-37=1`$ ✓.

---
