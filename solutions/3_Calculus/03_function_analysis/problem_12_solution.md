### Problem 12. A Function with an Absolute Value
Analyze

```math
f(x)=|x^2-4|.
```

First sketch $`x^2-4`$, then explain the effect of the absolute value. Indicate the points where the derivative does not exist and justify the reason geometrically.

> **Why this problem:** it shows the limits of mechanical application of calculus and the importance of the geometry of the graph.

#### Answer
- $`f(x)=x^2-4`$ for $`|x|\ge2`$, and $`f(x)=4-x^2`$ for $`|x|<2`$.
- Derivative: $`2x`$ for $`|x|>2`$, $`-2x`$ for $`|x|<2`$. **Does not exist at $`x=\pm2`$** (corners).
- Decreasing on $`(-\infty,-2)`$ and $`(0,2)`$; increasing on $`(-2,0)`$ and $`(2,\infty)`$.
- Minima at $`x=\pm2`$ ($`f=0`$); local maximum at $`x=0`$ ($`f=4`$).

![P12](images/fa_p12.png)

#### How I solved it
1. **Sketch $`x^2-4`$:** an upward parabola with vertex $`(0,-4)`$ crossing the $`x`$-axis at $`\pm2`$.
2. **Effect of $`|\cdot|`$:** every part of the graph below the $`x`$-axis (that is, for $`|x|<2`$) gets flipped upward. So on $`(-2,2)`$ the function becomes $`4-x^2`$, with its top at $`(0,4)`$.
3. **Derivative on each piece:** outside $`[-2,2]`$: $`(x^2-4)'=2x`$. Inside: $`(4-x^2)'=-2x`$.
4. **At $`x=2`$:** left-hand slope is $`-2\cdot2=-4`$, right-hand slope is $`2\cdot2=4`$. They differ, so there is no single tangent: the derivative does not exist. The same happens at $`x=-2`$ (slopes $`-4`$ on the left and $`+4`$ on the right).
5. **Monotonicity:** from the formulas: for $`x<-2`$, $`2x<0`$ (decreasing); for $`-2<x<0`$, $`-2x>0`$ (increasing); for $`0<x<2`$, $`-2x<0`$ (decreasing); for $`x>2`$, $`2x>0`$ (increasing).

**Geometric reason:** the original parabola crosses the $`x`$-axis at a slant (slope $`\pm4`$, not zero). Reflecting the lower part makes the graph "bounce" off the axis, forming a sharp V-shaped corner. A corner has no unique tangent line.

---
