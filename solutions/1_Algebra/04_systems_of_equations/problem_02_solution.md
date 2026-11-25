### Exercise 2. Gaussian Elimination — One Solution
Solve using Gaussian elimination:

```math
\begin{cases}
x+y+z=6, \\
2x-y+z=3, \\
x+2y-z=2.
\end{cases}
```

After solving, substitute the result into all equations and check consistency.

> **Why this exercise:** introduces the basic method for solving a system and builds the habit of checking the result.

#### Answer

```math
(x,y,z)=(1,2,3)
```

#### How I solved it
Augmented matrix:

```math
\left(\begin{array}{ccc|c}1&1&1&6\\2&-1&1&3\\1&2&-1&2\end{array}\right)
```

1. **Clear below the first pivot:** $`R_2\leftarrow R_2-2R_1`$ and $`R_3\leftarrow R_3-R_1`$:

```math
\left(\begin{array}{ccc|c}1&1&1&6\\0&-3&-1&-9\\0&1&-2&-4\end{array}\right)
```

2. **Swap $`R_2`$ and $`R_3`$** (to get a nicer pivot):

```math
\left(\begin{array}{ccc|c}1&1&1&6\\0&1&-2&-4\\0&-3&-1&-9\end{array}\right)
```

3. **Clear below the second pivot:** $`R_3\leftarrow R_3+3R_2`$:

```math
\left(\begin{array}{ccc|c}1&1&1&6\\0&1&-2&-4\\0&0&-7&-21\end{array}\right)
```

4. **Back substitution:**
   - $`-7z=-21\Rightarrow z=3`$
   - $`y-2z=-4\Rightarrow y=-4+6=2`$
   - $`x+y+z=6\Rightarrow x=6-2-3=1`$

**Check all equations:** $`1+2+3=6`$ ✓, $`2-2+3=3`$ ✓, $`1+4-3=2`$ ✓.

---
