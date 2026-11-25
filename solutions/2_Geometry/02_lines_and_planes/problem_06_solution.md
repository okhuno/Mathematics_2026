### Exercise 6. Angle Between Planes
Given

```math
\Pi_1:x+y+z=1,\qquad \Pi_2:x-y=2.
```

First use the normal vectors to decide whether the planes are parallel. If not, compute the angle between them and explain why the normal vectors alone are enough for this calculation.

> **Why this exercise:** focuses attention on one mechanism—using normals to analyze position and angle—without also introducing the construction of the intersection line.

#### Answer
Not parallel. The angle between the planes is $`90^\circ`$ (the planes are perpendicular).

#### How I solved it
- **Normals:** $`n_1=(1,1,1)`$ and $`n_2=(1,-1,0)`$. They are not multiples of each other, so the planes are not parallel.
- **Dot product:** $`n_1\cdot n_2=1-1+0=0`$. A zero dot product means the normals are at $`90^\circ`$, so the angle is $`90^\circ`$.

**Why normals are enough:** a plane is completely "tilted" by its normal. If you rotate a plane, its normal rotates by the same angle. So the angle between two planes equals the angle between their normals.

---
