### Exercise 12. Intersection Line of Two Planes
Find a parametric equation of the line that is the intersection of

```math
x+y+z=3,\qquad x-y+z=1.
```

Find its direction vector in two ways: from the system of equations and from the cross product of the normal vectors. Compare the results.

> **Why this exercise:** shows the equivalence of the algebraic and geometric approaches to constructing an intersection line.

#### Answer

```math
(x,y,z)=(2,1,0)+t(-1,0,1)
```

Direction vector $`(-1,0,1)`$ (both ways).

#### How I solved it
**Way 1: from the system.**
- Subtract the second equation from the first: $`2y=2\Rightarrow y=1`$.
- Then $`x+z=2`$. Let $`z=t`$, so $`x=2-t`$.
- The line: $`(x,y,z)=(2-t,\ 1,\ t)=(2,1,0)+t(-1,0,1)`$. Direction $`(-1,0,1)`$.

**Way 2: cross product of normals.**
- $`n_1=(1,1,1)`$, $`n_2=(1,-1,1)`$.
- $`n_1\times n_2=\big(1\cdot1-1\cdot(-1),\ 1\cdot1-1\cdot1,\ 1\cdot(-1)-1\cdot1\big)=(2,0,-2)`$.
- This is $`-2\cdot(-1,0,1)`$, parallel to the previous direction ✓.

**Why they agree:** the line lies in both planes, so it is perpendicular to both normals. The cross product of two vectors is perpendicular to both. Algebra and geometry are the same fact.

**Check the point $`(2,1,0)`$:** $`2+1+0=3`$ ✓ and $`2-1+0=1`$ ✓.

---
