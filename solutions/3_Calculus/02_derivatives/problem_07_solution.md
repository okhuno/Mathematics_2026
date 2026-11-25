### Problem 7. A Trigonometric Composition
For

```math
f(x)=\sin(x^2+1)
```

compute the derivative. Explicitly identify the outer function, the inner function, and the derivative of the inner function. Finally, determine the sign of $`f'(0)`$.

> **Why this problem:** it reinforces the chain rule in a different type of composition.

#### Answer
- $`f'(x)=2x\cos(x^2+1)`$
- $`f'(0)=0`$ (neither positive nor negative).

#### How I solved it
- **Outer:** $`\sin u`$, derivative $`\cos u`$.
- **Inner:** $`u=x^2+1`$, derivative $`2x`$.
- **Chain rule:** $`f'(x)=\cos(x^2+1)\cdot2x`$.
- $`f'(0)=\cos(1)\cdot0=0`$.

**Sign:** the derivative at $`0`$ is exactly zero (because of the factor $`2x`$), so the tangent there is horizontal.

---
