### Exercise 13. Closest Point on a Plane
Find the point on the plane $`x+2y+2z=4`$ closest to $`P=(3,0,0)`$. Give the distance and check that the segment joining the two points is perpendicular to the plane.

> **Why this exercise:** combines projection, distance, and the normal direction in one problem.

#### Answer
- Closest point: $`Q=\left(\frac{28}{9},\ \frac29,\ \frac29\right)`$
- Distance: $`\frac13`$

#### How I solved it
1. **Normal:** $`n=(1,2,2)`$, $`n\cdot n=9`$, $`\|n\|=3`$.
2. **Offset:** $`n\cdot P-d=3-4=-1`$.
3. **Move along the normal to reach the plane:** $`Q=P-\dfrac{-1}{9}n=P+\frac19n=\left(3+\frac19,\ \frac29,\ \frac29\right)=\left(\frac{28}{9},\frac29,\frac29\right)`$.
4. **Distance:** $`\dfrac{|{-1}|}{3}=\frac13`$.

**Check on the plane:** $`\frac{28}{9}+\frac49+\frac49=\frac{36}{9}=4`$ ✓.

**Check perpendicular:** $`\overrightarrow{PQ}=\left(\frac19,\frac29,\frac29\right)=\frac19(1,2,2)=\frac19n`$. It is a multiple of the normal, so it is perpendicular to the plane ✓. Its length is $`\frac19\cdot3=\frac13`$ ✓.

---
