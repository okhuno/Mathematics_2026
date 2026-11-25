### Problem 14. Reconstructing Information from the Derivative
It is known that

```math
f'(x)=(x-1)(x+2).
```

Determine the monotonicity and the locations of the extrema, and sketch a possible qualitative shape of the function. Then, for

```math
g(x)=\frac{x^3}{3}+\frac{x^2}{2}-2x
```

verify that $`g'(x)=(x-1)(x+2)`$, and compare the specific graph with the earlier qualitative sketch.

> **Why this problem:** it teaches how to read the behavior of a function directly from its derivative.

#### Answer
- $`f'>0`$ on $`(-\infty,-2)`$ and $`(1,\infty)`$; $`f'<0`$ on $`(-2,1)`$.
- $`f`$ increases, then decreases, then increases. Local **maximum** at $`x=-2`$, local **minimum** at $`x=1`$.
- $`g'(x)=x^2+x-2=(x-1)(x+2)`$ ✓
- For $`g`$: local max at $`\left(-2,\frac{10}3\right)`$, local min at $`\left(1,-\frac76\right)`$.

#### How I solved it
1. **Sign of $`f'`$:** zeros $`x=-2,1`$. A parabola opening upward is positive outside its zeros. Test: $`x=-3`$: $`(-4)(-1)=4>0`$; $`x=0`$: $`(-1)(2)=-2<0`$; $`x=2`$: $`(1)(4)=4>0`$.
2. **Extrema:** $`+\to-`$ at $`x=-2`$ (max); $`-\to+`$ at $`x=1`$ (min).
3. **Qualitative sketch:** a curve that goes up, reaches a peak at $`x=-2`$, goes down to a valley at $`x=1`$, then rises forever (like a cubic with positive leading coefficient).
4. **Verify $`g'`$:** $`g'(x)=\frac{3x^2}{3}+\frac{2x}2-2=x^2+x-2=(x-1)(x+2)`$ ✓
5. **Values:** $`g(-2)=-\frac83+2+4=\frac{10}3`$. $`g(1)=\frac13+\frac12-2=-\frac76`$.

**Comparison:** $`g`$ is one specific curve with exactly the shape from step 3. The derivative alone only fixes the shape: $`g(x)+C`$ for any constant $`C`$ has the same derivative, so the sketch can be shifted up or down.

---
