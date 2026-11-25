### Exercise 11. An n-th Root
Compute

```math
\lim_{n\to\infty}\sqrt[n]{5^n+2^n}.
```

Explain which term dominates and why the transformation looks different from the case of a quotient of polynomials.

> **Why this exercise:** extends the idea of dominance to exponential expressions.

#### Answer

```math
5
```

#### How I solved it
1. **Factor out the dominant term** $`5^n`$ inside the root:

```math
\sqrt[n]{5^n+2^n}=\sqrt[n]{5^n\left(1+\left(\tfrac25\right)^n\right)}=5\cdot\sqrt[n]{1+\left(\tfrac25\right)^n}.
```

2. As $`n\to\infty`$, $`\left(\frac25\right)^n\to0`$, so the root of $`(1+\text{tiny})`$ tends to $`1`$.
3. **Limit:** $`5\cdot1=5`$.

**Check with a squeeze:** $`5=\sqrt[n]{5^n}\le\sqrt[n]{5^n+2^n}\le\sqrt[n]{2\cdot5^n}=5\cdot2^{1/n}\to5`$.

**Which term dominates:** $`5^n`$ grows much faster than $`2^n`$. The transformation looks different from polynomial quotients because we factor out the biggest exponential (not divide by a power of $`n`$) and then use that the $`n`$-th root of $`1+\text{small}`$ goes to $`1`$.

---
