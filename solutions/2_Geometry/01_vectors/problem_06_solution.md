### Exercise 6. Projection and Perpendicular Component
Find the projection of $`u=(4,2)`$ onto the direction $`v=(1,1)`$. Then compute

```math
r=u-\mathrm{proj}_v\,u
```

and verify that $`r\cdot v=0`$. Explain this result geometrically.

> **Why this exercise:** shows projection as a decomposition into parallel and perpendicular components.

#### Answer
- $`\mathrm{proj}_v u=(3,3)`$
- $`r=(1,-1)`$
- $`r\cdot v=0`$ ✓

#### How I solved it
**Idea:** the projection is the "shadow" of $`u`$ on the line that goes in the direction of $`v`$.

1. **Dot products:** $`u\cdot v=4\cdot1+2\cdot1=6`$ and $`v\cdot v=1+1=2`$.
2. **Projection:** $`\dfrac{6}{2}(1,1)=3(1,1)=(3,3)`$.
3. **Leftover:** $`r=(4,2)-(3,3)=(1,-1)`$.
4. **Check:** $`r\cdot v=1\cdot1+(-1)\cdot1=0`$ ✓

**Geometric meaning:** we split $`u`$ into two pieces. One piece, $`(3,3)`$, lies along $`v`$. The other, $`r=(1,-1)`$, sticks out at exactly $`90^\circ`$ from $`v`$. Together they rebuild $`u`$: $`(3,3)+(1,-1)=(4,2)`$.

---
