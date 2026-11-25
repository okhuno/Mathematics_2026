### Exercise 7. Limit at a Point and Canceling a Factor
Compute

```math
\lim_{x\to3}\frac{x^2-4x+3}{x-3}.
```

Explain why the value of the function at $`x=3`$ is not needed to compute the limit.

> **Why this exercise:** separates the concept of a limit from the value of a function at a point.

#### Answer

```math
2
```

#### How I solved it
1. **Direct substitution gives** $`\frac00`$ (undefined), so we must simplify.
2. **Factor the numerator:** $`x^2-4x+3=(x-1)(x-3)`$.
3. **Cancel** $`(x-3)`$ (allowed because $`x\neq3`$ while $`x\to3`$): $`\dfrac{(x-1)(x-3)}{x-3}=x-1`$.
4. **Limit:** $`\lim_{x\to3}(x-1)=2`$.

**Why the value at $`3`$ is not needed:** the function is not even defined at $`x=3`$, yet the limit exists. The limit only looks at values of $`x`$ **near** $`3`$ (but not equal to $`3`$). Near $`3`$ the function behaves like $`x-1`$, which is close to $`2`$.

---
