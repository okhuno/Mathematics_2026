### Problem 10. Definite Integral and Checking the Result
Before carrying out the exact calculation, estimate the possible range of values of the integral

```math
\int_0^2(x^2+1)\,dx,
```

using

```math
1\le x^2+1\le5
```

on $`[0,2]`$. Only then compute the integral exactly, compare the result with the earlier estimate, and explain what type of computational error such a check can detect.

> **Why this problem:** it teaches how to predict the possible range of a result and check the calculation.

#### Answer
- Estimate: $`2\le\int_0^2(x^2+1)dx\le10`$.
- Exact value: $`\frac{14}{3}\approx4.67`$, which is inside the range ✓.

#### How I solved it
1. **Estimate:** the interval has length $`2`$ and the function is between $`1`$ and $`5`$. So the area is between (height $`1`$)×(length $`2`$) $`=2`$ and (height $`5`$)×(length $`2`$) $`=10`$.
2. **Exact:** $`\left[\frac{x^3}{3}+x\right]_0^2=\frac83+2=\frac{14}{3}`$.
3. **Compare:** $`2\le\frac{14}3\le10`$ ✓.

**What the check can detect:** big errors, such as a wrong sign, a forgotten term, swapped bounds, or arithmetic that gives a result like $`-3`$ or $`50`$. It cannot catch small mistakes that keep the result inside the range.

---
