### Exercise 13. Do Four Points Lie in One Plane?
Given

```math
A=(0,0,0),\qquad B=(1,2,0),\qquad C=(0,1,1),\qquad D=(2,5,1).
```

1. Construct $`\overrightarrow{AB}`$ and $`\overrightarrow{AC}`$.
2. Find $`n=\overrightarrow{AB}\times\overrightarrow{AC}`$.
3. Construct $`\overrightarrow{AD}`$ and check whether $`\overrightarrow{AD}\cdot n=0`$.
4. Based on this, decide whether $`D`$ lies in the plane determined by $`A,B,C`$, and justify the criterion.

> **Why this exercise:** combines the known cross and dot products into a geometric criterion needed for planes, without introducing a separate concept used only once.

#### Answer
- $`\overrightarrow{AB}=(1,2,0)`$, $`\overrightarrow{AC}=(0,1,1)`$
- $`n=(2,-1,1)`$
- $`\overrightarrow{AD}=(2,5,1)`$ and $`\overrightarrow{AD}\cdot n=0`$
- **Yes, $`D`$ lies in the plane of $`A,B,C`$.**

#### How I solved it
**Plan:** use $`A,B,C`$ to find the plane's normal $`n`$. Then test whether the arrow from $`A`$ to $`D`$ lies flat in the plane. Flat in the plane means perpendicular to $`n`$, which means dot product $`0`$.

1. **Two vectors in the plane:** $`\overrightarrow{AB}=(1,2,0)`$ and $`\overrightarrow{AC}=(0,1,1)`$.
2. **Normal vector:**
   - first: $`2\cdot1-0\cdot1=2`$
   - second: $`0\cdot0-1\cdot1=-1`$
   - third: $`1\cdot1-2\cdot0=1`$
3. **Test point $`D`$:** $`\overrightarrow{AD}=(2,5,1)`$, and $`\overrightarrow{AD}\cdot n=4-5+1=0`$.
4. **Conclusion:** the dot product is $`0`$, so $`D`$ is in the plane.

**Why the criterion works:** $`n`$ points straight out of the plane. Any arrow lying inside the plane (starting from $`A`$) is at $`90^\circ`$ to $`n`$. If $`D`$ were above or below the plane, $`\overrightarrow{AD}`$ would have a part along $`n`$ and the dot product would not be $`0`$.

**Extra check (different method):** $`\overrightarrow{AD}=2\overrightarrow{AB}+\overrightarrow{AC}=(2,4,0)+(0,1,1)=(2,5,1)`$ ✓. So $`D`$ is reached by moving only along $`AB`$ and $`AC`$, which stays in the plane.

---
