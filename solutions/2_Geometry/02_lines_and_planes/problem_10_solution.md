### Exercise 10. Projection of a Point onto a Plane
Find the orthogonal projection of $`P=(2,1,3)`$ onto the plane $`x+y+z=3`$, and then find the reflection of $`P`$ across this plane. Check that the midpoint of the segment joining the point and its reflection lies on the plane.

> **Why this exercise:** combines the normal, intersection, and distance into the construction of a projection and reflection.

#### Answer
- Projection: $`(1,0,2)`$
- Reflection: $`P'=(0,-1,1)`$
- Midpoint $`(1,0,2)`$ lies on the plane ✓.

#### How I solved it
1. **Normal:** $`n=(1,1,1)`$, $`n\cdot n=3`$.
2. **How far off the plane is $`P`$?** $`n\cdot P-d=2+1+3-3=3`$.
3. **Move back along the normal:** projection $`=P-\frac{3}{3}n=(2,1,3)-(1,1,1)=(1,0,2)`$.
4. **Check on the plane:** $`1+0+2=3`$ ✓.
5. **Reflection:** go twice as far: $`P'=P-2n=(2,1,3)-(2,2,2)=(0,-1,1)`$.
6. **Midpoint of $`P`$ and $`P'`$:** $`\left(\frac{2+0}{2},\frac{1-1}{2},\frac{3+1}{2}\right)=(1,0,2)`$. It equals the projection and lies on the plane ✓.

---
