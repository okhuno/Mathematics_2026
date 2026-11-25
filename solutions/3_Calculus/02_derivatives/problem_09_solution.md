### Problem 9. A Logarithm and the Chain Rule
For

```math
f(x)=\ln(x^2+1)
```

compute the derivative. Then determine the sign of $`f'(x)`$ for $`x<0`$, $`x=0`$, and $`x>0`$, and describe qualitatively how the function behaves around zero.

> **Why this problem:** it connects differentiation with sign analysis and the behavior of a function.

#### Answer
- $`f'(x)=\dfrac{2x}{x^2+1}`$
- $`f'<0`$ for $`x<0`$, $`f'(0)=0`$, $`f'>0`$ for $`x>0`$.

#### How I solved it
- **Chain rule:** outer $`\ln u`$ has derivative $`\frac1u`$; inner $`x^2+1`$ has derivative $`2x`$. So $`f'(x)=\frac{1}{x^2+1}\cdot2x`$.
- **Sign:** the denominator $`x^2+1`$ is always positive, so the sign of $`f'`$ equals the sign of $`2x`$.

**Behavior:** for $`x<0`$ the function decreases, at $`x=0`$ the tangent is horizontal, and for $`x>0`$ it increases. So the function has a **minimum** at $`x=0`$ with $`f(0)=\ln1=0`$. The graph looks like a smooth "bowl" (the function is never negative).

---
