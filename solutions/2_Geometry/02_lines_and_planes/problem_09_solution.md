### Exercise 9. Distances
Compute:

1. the distance from $`P=(2,3)`$ to the line $`3x+4y-10=0`$,
2. the distance from $`Q=(2,-1,3)`$ to the plane $`2x-2y+z-4=0`$.

Compare the two formulas and explain their common connection with the normal direction.

> **Why this exercise:** organizes two similar formulas through one geometric idea.

#### Answer
1. $`\dfrac85`$
2. $`\dfrac53`$

#### How I solved it
**Formula:** distance $`=\dfrac{|\text{left side evaluated at the point}|}{\text{length of the normal}}`$.

1. Line $`3x+4y-10=0`$, normal $`(3,4)`$ with length $`\sqrt{9+16}=5`$. At $`P`$: $`3\cdot2+4\cdot3-10=8`$. Distance $`=\frac{|8|}{5}=\frac85`$.
2. Plane $`2x-2y+z-4=0`$, normal $`(2,-2,1)`$ with length $`\sqrt{4+4+1}=3`$. At $`Q`$: $`4+2+3-4=5`$. Distance $`=\frac53`$.

**Common idea:** both formulas are the same one. The shortest path from a point to a line/plane is along the normal direction. The numerator measures how far the point is from the object "in units of the normal," and dividing by $`\|n\|`$ converts to real length.

---
