### Exercise 13. Fundamental Trigonometric Limit
Using

```math
\lim_{x\to0}\frac{\sin x}{x}=1,
```

compute

```math
\lim_{x\to0}\frac{\sin5x}{x},\qquad \lim_{x\to0}\frac{\sin2x}{\sin3x}.
```

In each case, show how you reduce the expression to the fundamental limit.

> **Why this exercise:** teaches how to reduce new limits to one known pattern.

#### Answer
- $`\lim_{x\to0}\frac{\sin5x}{x}=5`$
- $`\lim_{x\to0}\frac{\sin2x}{\sin3x}=\frac23`$

#### How I solved it
**Idea:** make the argument inside the sine match the thing in the denominator.

1. $`\dfrac{\sin5x}{x}=5\cdot\dfrac{\sin5x}{5x}`$. As $`x\to0`$, $`5x\to0`$, so $`\frac{\sin5x}{5x}\to1`$. Result: $`5\cdot1=5`$.
2. $`\dfrac{\sin2x}{\sin3x}=\dfrac{\sin2x}{2x}\cdot\dfrac{2x}{3x}\cdot\dfrac{3x}{\sin3x}`$.
   - $`\frac{\sin2x}{2x}\to1`$
   - $`\frac{2x}{3x}=\frac23`$
   - $`\frac{3x}{\sin3x}\to1`$

   Result: $`1\cdot\frac23\cdot1=\frac23`$.

---
