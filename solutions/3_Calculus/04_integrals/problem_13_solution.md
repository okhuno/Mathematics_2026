### Problem 13. An Integral Depending on the Upper Limit
Let

```math
F(x)=\int_0^x(t^2+1)\,dt.
```

Determine $`F(x)`$, compute $`F'(x)`$, and compare the result with the integrand. Explain in your own words why the height of the function describes the local rate of increase of the accumulated area.

> **Why this problem:** it connects differentiation and integration through the idea of accumulation.

#### Answer
- $`F(x)=\dfrac{x^3}{3}+x`$
- $`F'(x)=x^2+1`$, which is exactly the integrand evaluated at $`x`$.

#### How I solved it
1. $`F(x)=\left[\frac{t^3}{3}+t\right]_0^x=\frac{x^3}3+x`$.
2. $`F'(x)=x^2+1`$.
3. **Compare:** the derivative of the accumulated area equals the height of the original function at $`x`$.

**Why:** if we move the upper limit from $`x`$ to $`x+h`$ (with $`h`$ very small), we add a thin strip of width $`h`$ and height almost $`f(x)`$. So the added area is about $`f(x)\cdot h`$, and the rate of growth is area added divided by $`h`$, which is $`f(x)`$. A taller function adds area faster.

---
