### Exercise 1. Dominant Terms in a Sequence
Compute

```math
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}.
```

Explain why the highest-degree terms determine the result.

> **Why this exercise:** introduces the idea of a dominant term and teaches how to simplify the behavior of expressions for large arguments.

#### Answer

```math
2
```

#### How I solved it
Divide the numerator and the denominator by $`n^2`$ (the highest power):

```math
\frac{4-\frac3n+\frac1{n^2}}{2+\frac5n-\frac7{n^2}}\ \xrightarrow{n\to\infty}\ \frac{4-0+0}{2+0-0}=2.
```

**Why the highest-degree terms decide:** when $`n`$ is huge, $`n^2`$ is much bigger than $`n`$ or $`1`$. So $`4n^2-3n+1\approx4n^2`$ and $`2n^2+5n-7\approx2n^2`$, and the ratio is about $`\frac{4n^2}{2n^2}=2`$.

---
