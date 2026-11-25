### Problem 5. The Chain Rule as Working Through Layers
For

```math
f(x)=(3x^2-2x+1)^5
```

identify the inner and outer functions, compute their derivatives, and combine the result according to the chain rule. Explain the origin of the additional factor.

> **Why this problem:** it teaches how to recognize the structure of a composition instead of memorizing the rule as a meaningless pattern.

#### Answer

```math
f'(x)=5(3x^2-2x+1)^4\cdot(6x-2)=10(3x-1)(3x^2-2x+1)^4
```

#### How I solved it
- **Outer function:** $`g(u)=u^5`$, with $`g'(u)=5u^4`$.
- **Inner function:** $`h(x)=3x^2-2x+1`$, with $`h'(x)=6x-2`$.
- **Chain rule:** outer derivative (evaluated at the inner function) times inner derivative: $`5(3x^2-2x+1)^4\cdot(6x-2)`$.
- **Simplify (optional):** $`6x-2=2(3x-1)`$.

**Origin of the extra factor $`(6x-2)`$:** the inner function itself changes with $`x`$. A small change in $`x`$ changes $`h`$ by $`h'(x)`$ times as much, and a change in $`h`$ changes $`f`$ by $`g'(h)`$ times as much. Rates multiply.

---
