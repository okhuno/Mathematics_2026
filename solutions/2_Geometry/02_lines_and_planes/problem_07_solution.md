
### Exercise 7. A Line Relative to a Plane
For

```math
L:(x,y,z)=(1,1,0)+t(1,-1,0),\qquad \Pi:x+y+z=2,
```

determine whether the line intersects the plane at one point, is parallel to it, or lies in it. Explain the role of the dot product of the direction vector and the normal vector.

> **Why this exercise:** builds a universal test for the relative position of a line and a plane.

#### Answer
The line **lies in the plane**.

#### How I solved it
- Direction $`v=(1,-1,0)`$, normal $`n=(1,1,1)`$.
- $`v\cdot n=1-1+0=0`$, so the line runs along the plane (parallel or inside).
- To decide which, test one point of the line: $`(1,1,0)`$ gives $`1+1+0=2`$ ✓, so it is on the plane. Hence the whole line is in the plane.
- **Full check:** $`(1+t)+(1-t)+0=2`$ for every $`t`$ ✓.

**Role of $`v\cdot n`$:** if $`v\cdot n\neq0`$, the line points "through" the plane and must cross it. If $`v\cdot n=0`$, the line moves parallel to the plane and never changes its distance from it.

---
