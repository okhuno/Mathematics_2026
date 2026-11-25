### Problem 1. A Cubic Polynomial
Analyze the monotonicity and extrema of

```math
f(x)=x^3-3x^2+2.
```

Sketch the graph based on the results and mark the critical points.

> **Why this problem:** it teaches how to use the first derivative to describe the shape of a polynomial.

#### Answer
- $`f'(x)=3x(x-2)`$, critical points $`x=0`$ and $`x=2`$.
- Increasing on $`(-\infty,0)`$ and $`(2,\infty)`$; decreasing on $`(0,2)`$.
- Local maximum at $`(0,2)`$; local minimum at $`(2,-2)`$.

![P1](images/fa_p1.png)

#### How I solved it
1. **Derivative:** $`f'(x)=3x^2-6x=3x(x-2)`$.
2. **Critical points:** $`f'(x)=0\Rightarrow x=0`$ or $`x=2`$.
3. **Sign of $`f'`$** (test points):
   - $`x=-1`$: $`3(-1)(-3)=9>0`$
   - $`x=1`$: $`3(1)(-1)=-3<0`$
   - $`x=3`$: $`3(3)(1)=9>0`$
4. **Conclusions:** up, then down, then up. So $`x=0`$ is a local max ($`+\to-`$) with $`f(0)=2`$, and $`x=2`$ is a local min ($`-\to+`$) with $`f(2)=8-12+2=-2`$.
5. **Extra points for the sketch:** $`f(1)=0`$ (so the graph crosses the $`x`$-axis at $`1`$); $`f(x)\to-\infty`$ as $`x\to-\infty`$ and $`+\infty`$ as $`x\to\infty`$.

---
