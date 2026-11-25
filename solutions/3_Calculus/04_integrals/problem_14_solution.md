### Problem 14. A Piecewise-Defined Function
Let

```math
f(x)=
\begin{cases}
x+1,&-1\le x<1, \\
2,&1\le x\le3.
\end{cases}
```

Sketch the graph, decide where to split the integral, compute

```math
\int_{-1}^{3}f(x)\,dx
```

and verify the result geometrically.

> **Why this problem:** it requires understanding the definition of the function before carrying out the calculation.

#### Answer

```math
\int_{-1}^{3}f(x)\,dx=6
```

![Piecewise function](images/int_p14.png)

#### How I solved it
1. **Sketch:** a line from $`(-1,0)`$ up to $`(1,2)`$, then a horizontal line at height $`2`$ from $`x=1`$ to $`x=3`$. The two pieces meet at $`(1,2)`$.
2. **Split at $`x=1`$** (where the formula changes).
3. **First part:** $`\int_{-1}^1(x+1)dx=\left[\frac{x^2}{2}+x\right]_{-1}^1=\left(\frac12+1\right)-\left(\frac12-1\right)=\frac32+\frac12=2`$.
4. **Second part:** $`\int_1^32\,dx=2\cdot(3-1)=4`$.
5. **Total:** $`2+4=6`$.

**Geometric check:** the first part is a right triangle with base $`2`$ and height $`2`$: area $`\frac12\cdot2\cdot2=2`$. The second part is a rectangle $`2\times2`$: area $`4`$. Total $`6`$ ✓.

---
