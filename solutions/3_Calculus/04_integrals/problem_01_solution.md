### Problem 1. Antiderivative and Verification
For

```math
f(x)=3x^2-4x+5
```

find one antiderivative $`F(x)`$. Write the entire family of antiderivatives, verify the result by differentiation, and explain the meaning of the constant $`C`$.

> **Why this problem:** it introduces integration as the inverse operation to differentiation.

#### Answer
- One antiderivative: $`F(x)=x^3-2x^2+5x`$.
- Family: $`x^3-2x^2+5x+C`$.

#### How I solved it
Integrate term by term with the power rule:
- $`\int3x^2dx=3\cdot\frac{x^3}3=x^3`$
- $`\int-4x\,dx=-4\cdot\frac{x^2}{2}=-2x^2`$
- $`\int5\,dx=5x`$

**Verify:** $`(x^3-2x^2+5x+C)'=3x^2-4x+5+0`$ ✓

**Meaning of $`C`$:** the derivative of a constant is $`0`$, so adding any constant does not change the derivative. All antiderivatives differ only by a constant: their graphs are copies of each other shifted up or down.

---
