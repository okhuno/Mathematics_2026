### Problem 9. Definite Integral and Geometric Area
Compute

```math
\int_{-1}^{2}x\,dx.
```

Then separately compute the areas of the parts of the graph below and above the $`x`$-axis and explain the difference between the definite integral and geometric area.

> **Why this problem:** it clarifies the difference between signed accumulation and area.

#### Answer
- Integral: $`\frac32`$.
- Area below the axis ($`-1\le x\le0`$): $`\frac12`$. Area above the axis ($`0\le x\le2`$): $`2`$. Total geometric area: $`\frac52`$.

#### How I solved it
1. **Integral:** $`\left[\frac{x^2}{2}\right]_{-1}^{2}=\frac{4}{2}-\frac{1}{2}=\frac32`$.
2. **Areas** (they are triangles under/over $`y=x`$):
   - From $`-1`$ to $`0`$ (below the axis): base $`1`$, height $`1`$: area $`\frac12\cdot1\cdot1=\frac12`$.
   - From $`0`$ to $`2`$ (above): base $`2`$, height $`2`$: area $`\frac12\cdot2\cdot2=2`$.
3. **Compare:** the integral counts the below-axis part as **negative**: $`2-\frac12=\frac32`$. The geometric area counts everything as positive: $`2+\frac12=\frac52`$.

---
