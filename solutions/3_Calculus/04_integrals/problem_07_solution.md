### Problem 7. Integration by Parts as Reversing the Product Rule
Compute

```math
\int xe^x\,dx.
```

First write the product differentiation rule and, on that basis, explain the meaning of the integration-by-parts formula. Verify the result by differentiation.

> **Why this problem:** it connects a new technique with the familiar product rule.

#### Answer

```math
(x-1)e^x+C
```

#### How I solved it
1. **Product rule:** $`(uv)'=u'v+uv'`$. Integrate both sides: $`uv=\int u'v+\int uv'`$. Rearranging:

```math
\int uv'\,dx=uv-\int u'v\,dx.
```

So the formula is just the product rule written backward.
2. **Choose:** $`u=x`$ (so $`u'=1`$, simpler) and $`v'=e^x`$ (so $`v=e^x`$).
3. **Apply:** $`\int xe^x\,dx=xe^x-\int1\cdot e^x\,dx=xe^x-e^x+C=(x-1)e^x+C`$.

**Verify:** $`\big((x-1)e^x\big)'=e^x+(x-1)e^x=xe^x`$ ✓

---
