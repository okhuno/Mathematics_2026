### Problem 4. A Quotient and Domain Control
For

```math
f(x)=\frac{x^2+1}{x-1}
```

determine the domain, compute the derivative, simplify the result, and explain why the restriction $`x\neq1`$ remains important.

> **Why this problem:** it practices the quotient rule together with domain control.

#### Answer
- Domain: $`x\neq1`$.
- $`f'(x)=\dfrac{x^2-2x-1}{(x-1)^2}`$, for $`x\neq1`$.

#### How I solved it
1. **Domain:** $`x-1\ne0`$.
2. **Quotient rule:** $`\dfrac{f'g-fg'}{g^2}`$ with numerator $`2x`$ and denominator $`x-1`$:

```math
f'(x)=\frac{2x(x-1)-(x^2+1)\cdot1}{(x-1)^2}=\frac{2x^2-2x-x^2-1}{(x-1)^2}=\frac{x^2-2x-1}{(x-1)^2}.
```

**Why $`x\ne1`$ still matters:** even after simplification, the formula still has $`(x-1)^2`$ in the denominator. At $`x=1`$ the original function has a vertical asymptote (it does not exist), so there is no derivative there.

---
