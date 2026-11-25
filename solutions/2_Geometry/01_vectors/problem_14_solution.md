### Exercise 14. Closest Point on a Line
Given a point $`P=(4,1)`$ and a line through the origin with direction $`v=(1,2)`$. Using projection, find the closest point on the line, the distance from $`P`$ to the line, and verify that the appropriate vector is perpendicular to the direction of the line.

> **Why this exercise:** shows projection as a complete solution to a minimum-distance problem.

#### Answer
- Closest point: $`Q=\left(\frac65,\frac{12}{5}\right)`$
- Distance: $`\dfrac{7\sqrt5}{5}\approx3.13`$
- $`\overrightarrow{QP}\cdot v=0`$ ✓

#### How I solved it
**Idea:** the shortest path from a point to a line meets the line at $`90^\circ`$. The point where it lands is the projection of $`P`$ onto the line.

1. **Dot products:** $`P\cdot v=4+2=6`$ and $`v\cdot v=1+4=5`$.
2. **Closest point:** $`Q=\frac65(1,2)=\left(\frac65,\frac{12}{5}\right)`$.
3. **Arrow from $`Q`$ to $`P`$:** $`\overrightarrow{QP}=\left(4-\frac65,\ 1-\frac{12}{5}\right)=\left(\frac{14}{5},-\frac75\right)`$.
4. **Distance = length of that arrow:** $`\sqrt{\frac{196}{25}+\frac{49}{25}}=\frac{\sqrt{245}}{5}=\frac{7\sqrt5}{5}`$ (because $`\sqrt{245}=\sqrt{49\cdot5}=7\sqrt5`$).
5. **Check:** $`\overrightarrow{QP}\cdot v=\frac{14}{5}-\frac{14}{5}=0`$ ✓

---
