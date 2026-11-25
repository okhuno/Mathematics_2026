### Exercise 4. Plane Through Three Points
Find the equation of the plane through

```math
A=(1,0,0),\quad B=(0,1,0),\quad C=(0,0,1).
```

First construct two vectors lying in the plane, and then use the cross product. Check the resulting equation on all three points.

> **Why this exercise:** connects earlier vector tools with constructing the equation of a plane.

#### Answer

```math
x+y+z=1
```

#### How I solved it
1. **Two vectors in the plane:** $`\overrightarrow{AB}=(-1,1,0)`$ and $`\overrightarrow{AC}=(-1,0,1)`$.
2. **Normal = cross product:**
   - first: $`1\cdot1-0\cdot0=1`$
   - second: $`0\cdot(-1)-(-1)\cdot1=1`$
   - third: $`(-1)\cdot0-1\cdot(-1)=1`$

   So $`n=(1,1,1)`$.
3. **Equation:** $`x+y+z=d`$. Plug in $`A`$: $`d=1`$.

**Check:** $`A`$: $`1+0+0=1`$ ✓, $`B`$: $`0+1+0=1`$ ✓, $`C`$: $`0+0+1=1`$ ✓.

---
