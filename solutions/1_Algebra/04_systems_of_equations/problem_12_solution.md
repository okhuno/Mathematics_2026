### Exercise 12. Homogeneous System
Solve

```math
\begin{cases}
x+2y-z=0, \\
2x+4y-2z=0, \\
x-y+2z=0.
\end{cases}
```

Give all solutions in parametric form and explain why $`(0,0,0)`$ always satisfies a homogeneous system.

> **Why this exercise:** shows the special case of a system with a zero right-hand side without introducing additional theory.

#### Answer

```math
(x,y,z)=(-t,\ t,\ t),\quad t\in\mathbb R.
```

#### How I solved it

```math
\left(\begin{array}{ccc|c}1&2&-1&0\\2&4&-2&0\\1&-1&2&0\end{array}\right)\xrightarrow[R_3\leftarrow R_3-R_1]{R_2\leftarrow R_2-2R_1}\left(\begin{array}{ccc|c}1&2&-1&0\\0&0&0&0\\0&-3&3&0\end{array}\right)
```

- Third row: $`-3y+3z=0\Rightarrow y=z`$.
- First row: $`x+2y-z=0\Rightarrow x+y=0\Rightarrow x=-y`$.
- Let $`y=z=t`$: $`(x,y,z)=(-t,t,t)`$. One free variable.

**Check** with $`t=1`$: $`(-1,1,1)`$: $`-1+2-1=0`$ ✓; $`-2+4-2=0`$ ✓; $`-1-1+2=0`$ ✓.

**Why $`(0,0,0)`$ always works:** in a homogeneous system every equation has the form "(combination of $`x,y,z`$) $`=0`$." Putting in $`x=y=z=0`$ makes every left side $`0`$, which equals the right side. In matrix form, $`A\cdot0=0`$.

---
