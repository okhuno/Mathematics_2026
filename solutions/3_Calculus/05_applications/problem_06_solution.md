### Problem 6. Average Value of a Function
Compute the average value of the function

```math
f(x)=x^2
```

on the interval $`[0,3]`$.

Find a point $`c\in[0,3]`$ for which $`f(c)`$ is equal to this average value, and interpret the result geometrically.

> **Why this problem:** it gives the integral the interpretation of an average value and connects the numerical result with a level of the function on the graph.

#### Answer
- Average value: $`3`$.
- $`c=\sqrt3\approx1.73`$.

#### How I solved it
1. **Average:** $`\dfrac1{3-0}\int_0^3x^2dx=\dfrac13\left[\dfrac{x^3}{3}\right]_0^3=\dfrac13\cdot9=3`$.
2. **Find $`c`$:** $`c^2=3\Rightarrow c=\sqrt3`$ (positive root in $`[0,3]`$).

**Geometric meaning:** the area under the parabola on $`[0,3]`$ is $`9`$. A rectangle of width $`3`$ and height $`3`$ also has area $`9`$. So the average value is the height of the rectangle that has the same area as the region under the graph, and $`c`$ is the point where the graph reaches that height.

---
