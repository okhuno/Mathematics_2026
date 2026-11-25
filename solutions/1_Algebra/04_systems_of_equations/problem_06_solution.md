### Exercise 6. A System with a Parameter — Which Cases Actually Occur?
Analyze, depending on the parameter $`a`$, the system

```math
\begin{cases}
x+y=2, \\
ax+ay=4.
\end{cases}
```

Among the three possibilities — exactly one solution, infinitely many solutions, no solution — determine which actually occur and for which values of $`a`$. If one type cannot occur, explain why.

> **Why this exercise:** teaches how to analyze a parameter without assuming in advance that all theoretically possible cases must occur in a specific system.

#### Answer
- $`a=2`$: **infinitely many** solutions.
- $`a\neq2`$: **no solution**.
- **Exactly one solution never occurs.**

#### How I solved it

```math
\left(\begin{array}{cc|c}1&1&2\\a&a&4\end{array}\right)\xrightarrow{R_2\leftarrow R_2-aR_1}\left(\begin{array}{cc|c}1&1&2\\0&0&4-2a\end{array}\right)
```

- If $`a=2`$: last row $`0=0`$. Only one real equation $`x+y=2`$ for two unknowns: infinitely many solutions $`(2-t,\ t)`$.
- If $`a\ne2`$: last row $`0=4-2a\neq0`$, contradiction: no solution.

**Why a unique solution is impossible:** the second row of coefficients $`(a,a)`$ is always $`a`$ times the first row $`(1,1)`$. So after elimination the second row always has zero coefficients. We never get two pivots for two unknowns. (Geometrically the two lines are always parallel or identical, never crossing at one point.)

---
