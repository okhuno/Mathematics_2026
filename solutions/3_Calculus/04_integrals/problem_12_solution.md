### Problem 12. Symmetry, Sign, and Absolute Value
Compare

```math
\int_{-2}^{2}x\,dx
```

and

```math
\int_{-2}^{2}|x|\,dx.
```

Before calculating, predict the results from symmetry and a sketch, then carry out the calculation and explain the difference.

> **Why this problem:** it teaches how to use symmetry and geometry before applying a computational procedure.

#### Answer
- $`\int_{-2}^2x\,dx=0`$
- $`\int_{-2}^2|x|\,dx=4`$

#### How I solved it
**Prediction:**
- $`y=x`$ is symmetric about the origin: the triangle on the left is below the axis and exactly cancels the equal triangle on the right above the axis. So the integral should be $`0`$.
- $`y=|x|`$ is a "V" shape, entirely above the axis: two triangles, each with base $`2`$ and height $`2`$ (area $`2`$ each). Total $`4`$.

**Calculation:**
- $`\left[\frac{x^2}2\right]_{-2}^2=2-2=0`$ ✓
- $`\int_{-2}^2|x|dx=2\int_0^2x\,dx=2\cdot\left[\frac{x^2}2\right]_0^2=2\cdot2=4`$ ✓

**Difference:** in the first integral the left half counts negatively and cancels the right half. With the absolute value, nothing is negative, so the two halves add up.

---
