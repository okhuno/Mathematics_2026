### Problem 12. Several Rules at Once
For

```math
f(x)=(x^2+1)^3e^x
```

compute the derivative. Before calculating, write down a plan: which rule applies to the whole expression and which rule applies to one of its factors. Finally, organize the result by factoring out common factors.

> **Why this problem:** it practices the order of decisions when combining familiar differentiation rules.

#### Answer

```math
f'(x)=(x^2+1)^2e^x\,(x^2+6x+1)
```

#### How I solved it
**Plan:**
- The whole expression is a **product** of $`u=(x^2+1)^3`$ and $`v=e^x`$, so use the **product rule**.
- The factor $`u=(x^2+1)^3`$ is a composition, so differentiate it with the **chain rule**.

**Steps:**
1. $`u'=3(x^2+1)^2\cdot2x=6x(x^2+1)^2`$ and $`v'=e^x`$.
2. Product rule: $`f'=u'v+uv'=6x(x^2+1)^2e^x+(x^2+1)^3e^x`$.
3. **Factor out** $`(x^2+1)^2e^x`$: $`f'=(x^2+1)^2e^x\big[6x+(x^2+1)\big]=(x^2+1)^2e^x(x^2+6x+1)`$.

---
