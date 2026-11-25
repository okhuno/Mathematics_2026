### Exercise 10. A Polynomial Through Three Points
Find a polynomial $`p(x)=ax^2+bx+c`$ whose graph passes through $`(0,1)`$, $`(1,3)`$, and $`(2,9)`$. Reduce the problem to a system of equations and check the result by substituting all three points.

> **Why this exercise:** shows that finding unknown coefficients can be reduced to solving a linear system.

#### Answer

```math
p(x)=2x^2+1
```

#### How I solved it
Each point gives one equation (put $`x`$ and $`p(x)`$ into $`ax^2+bx+c`$). The unknowns are $`a,b,c`$:
- $`(0,1)`$: $`c=1`$
- $`(1,3)`$: $`a+b+c=3`$
- $`(2,9)`$: $`4a+2b+c=9`$

Substitute $`c=1`$: $`a+b=2`$ and $`4a+2b=8`$ (i.e. $`2a+b=4`$). Subtract the first from the second: $`a=2`$. Then $`b=2-a=0`$.

**Check:** $`p(0)=1`$ ✓, $`p(1)=2+1=3`$ ✓, $`p(2)=8+1=9`$ ✓.

---
