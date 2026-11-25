### Exercise 12. A Normal Vector to a Plane
Given $`A=(1,0,2)`$, $`B=(2,1,0)`$, and $`C=(0,3,1)`$. Construct two vectors lying in the plane, find a vector perpendicular to both, and check the perpendicularity using dot products.

> **Why this exercise:** creates a direct bridge from vectors to the description of a plane.

#### Answer
- In-plane vectors: $`\overrightarrow{AB}=(1,1,-2)`$, $`\overrightarrow{AC}=(-1,3,-1)`$
- Normal vector: $`n=(5,3,4)`$
- $`n\cdot\overrightarrow{AB}=0`$ ✓ and $`n\cdot\overrightarrow{AC}=0`$ ✓

#### How I solved it
**Idea:** three points define a plane. A **normal vector** sticks straight out of the plane at $`90^\circ`$. We get it as the cross product of two vectors lying in the plane.

1. **Two vectors in the plane:** $`\overrightarrow{AB}=(2-1,\ 1-0,\ 0-2)=(1,1,-2)`$ and $`\overrightarrow{AC}=(0-1,\ 3-0,\ 1-2)=(-1,3,-1)`$.
2. **Cross product:**
   - first: $`1\cdot(-1)-(-2)\cdot3=-1+6=5`$
   - second: $`(-2)\cdot(-1)-1\cdot(-1)=2+1=3`$
   - third: $`1\cdot3-1\cdot(-1)=3+1=4`$
3. **Check:**
   - $`n\cdot\overrightarrow{AB}=5+3-8=0`$ ✓
   - $`n\cdot\overrightarrow{AC}=-5+9-4=0`$ ✓

---
