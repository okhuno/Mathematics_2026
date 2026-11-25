### Problem 10. Complete Function Analysis
Perform a complete analysis of

```math
f(x)=\frac{x}{x^2+1}.
```

Include the domain, symmetry, zeros, limits, monotonicity, extrema, and convexity. Finally, produce a sketch based only on this information.

> **Why this problem:** it combines all the basic elements of function analysis into one organized process.

#### Answer
- Domain: all real $`x`$ (since $`x^2+1>0`$).
- Symmetry: odd, $`f(-x)=-f(x)`$ (symmetric about the origin).
- Zero: $`x=0`$. Limits: $`f\to0`$ as $`x\to\pm\infty`$ ($`y=0`$ is a horizontal asymptote).
- $`f'(x)=\dfrac{1-x^2}{(x^2+1)^2}`$: decreasing on $`(-\infty,-1)`$, increasing on $`(-1,1)`$, decreasing on $`(1,\infty)`$.
- Local minimum $`\left(-1,-\frac12\right)`$, local maximum $`\left(1,\frac12\right)`$.
- $`f''(x)=\dfrac{2x(x^2-3)}{(x^2+1)^3}`$: concave on $`(-\infty,-\sqrt3)`$, convex on $`(-\sqrt3,0)`$, concave on $`(0,\sqrt3)`$, convex on $`(\sqrt3,\infty)`$. Inflection points at $`x=-\sqrt3,\ 0,\ \sqrt3`$.

![P10](images/fa_p10.png)

#### How I solved it
1. **Domain:** $`x^2+1\ge1>0`$, so no problems.
2. **Symmetry:** $`f(-x)=\frac{-x}{x^2+1}=-f(x)`$, odd.
3. **Zero:** numerator $`x=0`$.
4. **Limits:** divide top and bottom by $`x^2`$: $`\frac{1/x}{1+1/x^2}\to0`$.
5. **First derivative (quotient rule):** $`f'=\dfrac{(x^2+1)-x\cdot2x}{(x^2+1)^2}=\dfrac{1-x^2}{(x^2+1)^2}`$. The denominator is positive, so the sign is that of $`1-x^2`$: negative for $`|x|>1`$, positive for $`|x|<1`$. Zeros at $`x=\pm1`$.
6. **Extrema:** at $`x=-1`$: $`-\to+`$, minimum, $`f=-\frac12`$. At $`x=1`$: $`+\to-`$, maximum, $`f=\frac12`$.
7. **Second derivative** (quotient rule on $`f'`$ and simplifying): $`f''=\dfrac{2x(x^2-3)}{(x^2+1)^3}`$. Its sign depends on $`x(x^2-3)`$; test points give the pattern listed above. It changes sign at $`-\sqrt3,0,\sqrt3`$, so these are inflection points, with $`f(\pm\sqrt3)=\pm\frac{\sqrt3}{4}`$.

---
