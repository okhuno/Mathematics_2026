### Problem 2. Powers, Roots, and the Domain
For

```math
f(x)=2\sqrt{x}-\frac{3}{x^2}+x^{3/2}
```

1. rewrite the function using powers,
2. determine the domain,
3. compute the derivative,
4. compare the domain of the function with the domain of its derivative.

> **Why this problem:** it teaches how to rewrite different forms so that the power rule can be applied and how to keep track of the domain.

#### Answer
1. $`f(x)=2x^{1/2}-3x^{-2}+x^{3/2}`$
2. Domain of $`f`$: $`x>0`$
3. $`f'(x)=x^{-1/2}+6x^{-3}+\frac32x^{1/2}=\dfrac1{\sqrt x}+\dfrac6{x^3}+\dfrac32\sqrt x`$
4. Domain of $`f'`$: $`x>0`$, the same as the domain of $`f`$.

#### How I solved it
1. Roots become fractional powers and fractions become negative powers: $`\sqrt x=x^{1/2}`$, $`\frac1{x^2}=x^{-2}`$.
2. **Domain:** $`\sqrt x`$ needs $`x\ge0`$; $`\frac{3}{x^2}`$ needs $`x\ne0`$; $`x^{3/2}`$ needs $`x\ge0`$. Together: $`x>0`$.
3. **Power rule:** $`(2x^{1/2})'=x^{-1/2}`$; $`(-3x^{-2})'=6x^{-3}`$; $`(x^{3/2})'=\frac32x^{1/2}`$.
4. The derivative has $`\frac1{\sqrt x}`$ and $`\frac{6}{x^3}`$, which need $`x>0`$, so the domains agree here. (Note: they would not always agree. For example $`\sqrt x`$ alone is defined at $`0`$, but its derivative $`\frac{1}{2\sqrt x}`$ is not.)

---
