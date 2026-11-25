### Exercise 8. Intersection Point of a Line and a Plane
Find the intersection point of

```math
(x,y,z)=(1,0,2)+t(1,2,-1)
```

with the plane $`x+y+z=4`$. Check the result by substituting it into both descriptions.

> **Why this exercise:** practices the most important computational case of the line–plane relationship.

#### Answer
$`t=\frac12`$, intersection point $`\left(\frac32,\ 1,\ \frac32\right)`$.

#### How I solved it
1. Write a general point of the line: $`(1+t,\ 2t,\ 2-t)`$.
2. Put it into the plane equation: $`(1+t)+2t+(2-t)=4\Rightarrow3+2t=4\Rightarrow t=\frac12`$.
3. Put $`t=\frac12`$ back: $`\left(\frac32,1,\frac32\right)`$.

**Check:** plane: $`\frac32+1+\frac32=4`$ ✓. Line: $`(1+\frac12,\ 2\cdot\frac12,\ 2-\frac12)=\left(\frac32,1,\frac32\right)`$ ✓.

---
