### Exercise 5. Relative Position of Two Lines
Analyze the position of

```math
L_1:(x,y,z)=(1,1,0)+t(1,2,1),
```

```math
L_2:(x,y,z)=(2,0,1)+s(0,1,-1).
```

If they intersect, give the intersection point. If not, determine whether they are parallel or skew. Justify the classification.

> **Why this exercise:** teaches how to distinguish qualitatively different relationships between lines in space.

#### Answer
The lines are **skew** (not parallel and they do not intersect).

#### How I solved it
1. **Parallel?** Directions $`(1,2,1)`$ and $`(0,1,-1)`$ are not multiples of each other, so the lines are not parallel.
2. **Do they intersect?** We need $`1+t=2`$, $`1+2t=s`$, $`t=1-s`$ (one for each coordinate $`x,y,z`$):
   - $`x`$: $`1+t=2\Rightarrow t=1`$
   - $`y`$: $`1+2t=0+s\Rightarrow s=3`$
   - $`z`$: $`0+t=1-s`$. With $`t=1,s=3`$: left $`=1`$, right $`=-2`$. **Contradiction.**
3. So there is no common point. Not parallel and not intersecting means **skew** (they pass each other in space, like two roads on different bridge levels).

---
