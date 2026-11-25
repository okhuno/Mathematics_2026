### Exercise 11. A Parameter in a System of Three Equations
Analyze the number of solutions depending on $`t`$:

```math
\begin{cases}
x+y+z=1, \\
x+ty+z=2, \\
x+y+tz=3.
\end{cases}
```

Use elimination and separately analyze the parameter values for which a standard calculation step ceases to be valid.

> **Why this exercise:** develops parametric analysis while still relying only on elimination.

#### Answer
- $`t=1`$: **no solution**.
- $`t\neq1`$: **exactly one solution**

```math
x=\frac{t-4}{t-1},\quad y=\frac1{t-1},\quad z=\frac2{t-1}.
```

- Infinitely many solutions: never.

#### How I solved it

```math
\left(\begin{array}{ccc|c}1&1&1&1\\1&t&1&2\\1&1&t&3\end{array}\right)\xrightarrow[R_3\leftarrow R_3-R_1]{R_2\leftarrow R_2-R_1}\left(\begin{array}{ccc|c}1&1&1&1\\0&t-1&0&1\\0&0&t-1&2\end{array}\right)
```

The matrix is already triangular. To continue we **divide by $`t-1`$**; this step is valid only if $`t\ne1`$.

- **If $`t\ne1`$:** $`y=\frac1{t-1}`$, $`z=\frac{2}{t-1}`$, and $`x=1-y-z=1-\frac3{t-1}=\frac{t-4}{t-1}`$. One solution.
- **If $`t=1`$:** the second row is $`0=1`$ (and the third $`0=2`$): contradiction, no solution.

**Check with $`t=2`$:** $`y=1`$, $`z=2`$, $`x=-2`$. Equations: $`-2+1+2=1`$ ✓; $`-2+2+2=2`$ ✓; $`-2+1+4=3`$ ✓.

---
