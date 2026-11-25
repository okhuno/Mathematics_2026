### Problem 3. A Rational Function
Analyze the domain, zeros, asymptotes, and monotonicity of

```math
f(x)=\frac{x+1}{x-2}.
```

Finally, sketch a graph consistent with all the information obtained.

> **Why this problem:** it teaches how to combine the domain, limits, and derivative in the analysis of a rational function.

#### Answer
- Domain: $`x\neq2`$.
- Zero: $`x=-1`$; $`f(0)=-\frac12`$.
- Vertical asymptote $`x=2`$; horizontal asymptote $`y=1`$.
- $`f'(x)=-\dfrac{3}{(x-2)^2}<0`$: decreasing on $`(-\infty,2)`$ and on $`(2,\infty)`$. No extrema.

![P3](images/fa_p3.png)

#### How I solved it
1. **Domain:** the denominator $`x-2\ne0`$.
2. **Zero:** numerator $`x+1=0\Rightarrow x=-1`$.
3. **Vertical asymptote:** at $`x=2`$ the numerator is $`3\neq0`$ and the denominator is $`0`$. As $`x\to2^+`$, $`f\to+\infty`$; as $`x\to2^-`$, $`f\to-\infty`$.
4. **Horizontal asymptote:** $`\lim_{x\to\pm\infty}\frac{x+1}{x-2}=1`$ (divide top and bottom by $`x`$).
5. **Derivative (quotient rule):** $`f'=\dfrac{1\cdot(x-2)-(x+1)\cdot1}{(x-2)^2}=\dfrac{-3}{(x-2)^2}`$. The denominator is a square (positive), so $`f'<0`$ everywhere on the domain.
6. **Sketch:** the left branch comes in from $`y=1`$ (from below), passes through $`(-1,0)`$ and $`(0,-\frac12)`$ and falls to $`-\infty`$ at $`x=2`$. The right branch comes down from $`+\infty`$ and approaches $`y=1`$ from above.

---
