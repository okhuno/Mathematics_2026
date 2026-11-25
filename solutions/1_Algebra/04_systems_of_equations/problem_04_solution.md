### Exercise 4. Infinitely Many Solutions
Solve

```math
\begin{cases}
x+y+z=2, \\
2x+2y+2z=4, \\
x-y+z=0.
\end{cases}
```

Give the solution in parametric form, identify a free variable, and for one chosen parameter value check that the resulting point really satisfies the system.

> **Why this exercise:** shows the case of multiple solutions and teaches a simple parametric description.

#### Answer

```math
(x,y,z)=(1-t,\ 1,\ t),\quad t\in\mathbb R.
```

Free variable: $`z=t`$.

#### How I solved it

```math
\left(\begin{array}{ccc|c}1&1&1&2\\2&2&2&4\\1&-1&1&0\end{array}\right)\xrightarrow[R_3\leftarrow R_3-R_1]{R_2\leftarrow R_2-2R_1}\left(\begin{array}{ccc|c}1&1&1&2\\0&0&0&0\\0&-2&0&-2\end{array}\right)
```

- The second row became $`0=0`$ (the second equation was just twice the first, so it gave no new information).
- Third row: $`-2y=-2\Rightarrow y=1`$.
- First row: $`x+y+z=2\Rightarrow x+z=1`$. The unknown $`z`$ has no pivot, so it is **free**: let $`z=t`$. Then $`x=1-t`$.

**Check** with $`t=0`$, point $`(1,1,0)`$: $`1+1+0=2`$ ✓; $`2+2+0=4`$ ✓; $`1-1+0=0`$ ✓.
With $`t=1`$, point $`(0,1,1)`$: $`0+1+1=2`$ ✓; $`0+2+2=4`$ ✓; $`0-1+1=0`$ ✓.

---
