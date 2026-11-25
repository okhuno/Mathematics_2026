### Exercise 5. Row Operations
For

```math
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 1 & 0 \\
-1 & 4 & 2 \\
\end{pmatrix}
```

find $`\det A`$ by simplifying the matrix with row operations. At each step, indicate whether and how the determinant changes.

> **Why this exercise:** connects determinants with row operations and requires conscious tracking of every step.

#### Answer

```math
\det A=21
```

#### How I solved it
1. $`R_2\leftarrow R_2-2R_1`$: $`(2,1,0)-(2,4,6)=(0,-3,-6)`$. **Determinant unchanged.**
2. $`R_3\leftarrow R_3+R_1`$: $`(-1,4,2)+(1,2,3)=(0,6,5)`$. **Determinant unchanged.**

```math
\begin{pmatrix}1&2&3\\0&-3&-6\\0&6&5\end{pmatrix}
```

3. $`R_3\leftarrow R_3+2R_2`$: $`(0,6,5)+(0,-6,-12)=(0,0,-7)`$. **Determinant unchanged.**

```math
\begin{pmatrix}1&2&3\\0&-3&-6\\0&0&-7\end{pmatrix}
```

4. The matrix is triangular: $`\det=1\cdot(-3)\cdot(-7)=21`$.

Since only "add a multiple of a row to another row" operations were used, $`\det A=21`$.

**Check (Sarrus on the original):** down-right: $`1\cdot1\cdot2+2\cdot0\cdot(-1)+3\cdot2\cdot4=2+0+24=26`$. Up-right: $`3\cdot1\cdot(-1)+1\cdot0\cdot4+2\cdot2\cdot2=-3+0+8=5`$. $`26-5=21`$ ✓.

---
