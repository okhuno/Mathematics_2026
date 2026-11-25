### Problem 8. The Second Derivative
For

```math
f(x)=x^4-4x^2
```

find the local extrema, intervals of convexity and concavity, and inflection points. Sketch the graph and mark all the identified features on it.

> **Why this problem:** it introduces the second derivative as a tool for describing the curvature of a graph.

#### Answer
- $`f'(x)=4x(x^2-2)`$. Critical points $`x=0,\pm\sqrt2`$.
- Local minima at $`x=\pm\sqrt2`$ with $`f=-4`$; local maximum at $`x=0`$ with $`f=0`$.
- $`f''(x)=12x^2-8`$. Concave on $`\left(-\sqrt{\tfrac23},\sqrt{\tfrac23}\right)`$, convex on the outer intervals.
- Inflection points at $`x=\pm\sqrt{\frac23}=\pm\frac{\sqrt6}3\approx\pm0.816`$, where $`f=-\frac{20}9`$.
- Zeros: $`x=0,\pm2`$. The function is even.

![P8](images/fa_p8.png)

#### How I solved it
1. **First derivative:** $`f'=4x^3-8x=4x(x^2-2)`$. Zeros: $`x=0,\ \pm\sqrt2`$.
2. **Sign of $`f'`$** (test points):
   - $`x=-2`$: $`4(-2)(2)=-16<0`$ (decreasing)
   - $`x=-1`$: $`4(-1)(-1)=4>0`$ (increasing)
   - $`x=1`$: $`4(1)(-1)=-4<0`$ (decreasing)
   - $`x=2`$: $`4(2)(2)=16>0`$ (increasing)
3. **Extrema:** $`-\to+`$ at $`x=-\sqrt2`$ and $`x=\sqrt2`$ (minima, $`f=4-8=-4`$); $`+\to-`$ at $`x=0`$ (maximum, $`f=0`$).
4. **Second derivative:** $`f''=12x^2-8=0\Rightarrow x^2=\frac23`$. For $`|x|>\sqrt{2/3}`$, $`f''>0`$ (convex, ∪). For $`|x|<\sqrt{2/3}`$, $`f''<0`$ (concave, ∩).
5. **Inflection values:** $`f\!\left(\pm\sqrt{2/3}\right)=\frac49-4\cdot\frac23=\frac49-\frac{24}{9}=-\frac{20}9`$.
6. **Zeros:** $`x^2(x^2-4)=0\Rightarrow x=0,\pm2`$.

The graph looks like a "W" with a small bump up at the middle.

---
