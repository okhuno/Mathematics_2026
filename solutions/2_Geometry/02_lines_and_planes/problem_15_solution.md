### Exercise 15. Complete Classification of a Line Relative to a Plane
Let

```math
L:p+tv,\qquad \Pi:n\cdot x=d.
```

State the conditions distinguishing the three cases: one intersection point, parallel with no common points, and the line contained in the plane. Then illustrate each case with your own simple numerical example.

> **Why this exercise:** requires formulating a general mathematical criterion instead of carrying out one isolated calculation.

#### Answer
Substitute the line into the plane: $`n\cdot(p+tv)=d`$, i.e. $`(n\cdot v)\,t=d-n\cdot p`$. Then:

| Case | Condition | Result |
|---|---|---|
| One intersection point | $`n\cdot v\neq0`$ | $`t=\dfrac{d-n\cdot p}{n\cdot v}`$ |
| Parallel, no common points | $`n\cdot v=0`$ and $`n\cdot p\neq d`$ | equation reads $`0=\text{nonzero}`$ |
| Line inside the plane | $`n\cdot v=0`$ and $`n\cdot p=d`$ | equation reads $`0=0`$, true for all $`t`$ |

**Examples** with plane $`x+y+z=1`$ ($`n=(1,1,1)`$, $`d=1`$):
1. **One point:** $`p=(0,0,0)`$, $`v=(1,0,0)`$. $`n\cdot v=1\ne0`$, and $`t=\frac{1-0}{1}=1`$: point $`(1,0,0)`$.
2. **Parallel:** $`p=(0,0,0)`$, $`v=(1,-1,0)`$. $`n\cdot v=0`$ and $`n\cdot p=0\neq1`$: no common points.
3. **Contained:** $`p=(1,0,0)`$, $`v=(1,-1,0)`$. $`n\cdot v=0`$ and $`n\cdot p=1=d`$: the line lies in the plane. (Check: $`(1+t)+(-t)+0=1`$ ✓.)

#### How I solved it
Plug the line $`p+tv`$ into the plane equation. Because $`n\cdot`$ is linear, $`n\cdot(p+tv)=n\cdot p+t\,(n\cdot v)`$. So we get one linear equation in $`t`$: $`(n\cdot v)t=d-n\cdot p`$. A linear equation $`at=b`$ has exactly one solution if $`a\neq0`$; no solution if $`a=0,b\ne0`$; and every $`t`$ works if $`a=0,b=0`$. These are exactly the three cases.
