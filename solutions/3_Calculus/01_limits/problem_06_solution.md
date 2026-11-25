### Exercise 6. From a Sequence to a Function — Limit at Infinity
Compute

```math
\lim_{x\to\infty}\frac{3x^2-x+1}{5x^2+4x-2}.
```

Compare the method with Exercise 1. Explain what changes when moving from $`n`$ to a real variable $`x`$, and what stays the same.

> **Why this exercise:** deliberately transfers a technique from sequence limits to function limits.

#### Answer

```math
\frac35
```

#### How I solved it
Divide numerator and denominator by $`x^2`$:

```math
\frac{3-\frac1x+\frac1{x^2}}{5+\frac4x-\frac2{x^2}}\ \xrightarrow{x\to\infty}\ \frac{3}{5}.
```

**What stays the same:** the method (divide by the highest power, dominant terms) and the result (ratio of leading coefficients).

**What changes:** $`n`$ was a natural number ($`1,2,3,\dots`$), while $`x`$ is a real number that increases continuously. The idea "as the variable gets huge" is the same.

---
