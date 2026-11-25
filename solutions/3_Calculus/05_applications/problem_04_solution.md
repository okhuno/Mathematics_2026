### Problem 4. Area Between Curves
Find the area of the region bounded by the graphs

```math
y=x
```

and

```math
y=x^2.
```

First find the intersection points and justify which function is greater on the relevant interval.

> **Why this problem:** it teaches that before integrating, one must first determine the geometry of the region and the correct order of the functions.

#### Answer

```math
\text{Area}=\frac16
```

#### How I solved it
1. **Intersections:** $`x=x^2\Rightarrow x(x-1)=0\Rightarrow x=0,\ 1`$.
2. **Which is on top on $`(0,1)`$?** Test $`x=0.5`$: $`y=x`$ gives $`0.5`$ and $`y=x^2`$ gives $`0.25`$. So $`y=x`$ is on top.
3. **Integral (top minus bottom):**

```math
\int_0^1(x-x^2)\,dx=\left[\frac{x^2}{2}-\frac{x^3}{3}\right]_0^1=\frac12-\frac13=\frac16.
```

---
