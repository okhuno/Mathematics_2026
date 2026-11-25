### Exercise 10. Triangle Area from Vectors
The points $`A=(0,0,0)`$, $`B=(2,1,0)`$, and $`C=(1,3,2)`$ form a triangle. Construct $`\overrightarrow{AB}`$ and $`\overrightarrow{AC}`$, compute the area of the parallelogram using the cross product, and then find the area of the triangle. Explain the factor $`\frac12`$.

> **Why this exercise:** shows the interpretation of the length of the cross product as area.

#### Answer
- $`\overrightarrow{AB}=(2,1,0)`$, $`\overrightarrow{AC}=(1,3,2)`$
- $`\overrightarrow{AB}\times\overrightarrow{AC}=(2,-4,5)`$
- Parallelogram area $`=3\sqrt5\approx6.71`$
- Triangle area $`=\dfrac{3\sqrt5}{2}\approx3.35`$

#### How I solved it
**Idea:** the **length** of the cross product equals the area of the parallelogram built on the two vectors.

1. **Two sides as vectors** (end minus start): $`\overrightarrow{AB}=(2,1,0)`$ and $`\overrightarrow{AC}=(1,3,2)`$.
2. **Cross product:**
   - first: $`1\cdot2-0\cdot3=2`$
   - second: $`0\cdot1-2\cdot2=-4`$
   - third: $`2\cdot3-1\cdot1=5`$
3. **Length:** $`\sqrt{2^2+(-4)^2+5^2}=\sqrt{45}=3\sqrt5`$. This is the parallelogram area.
4. **Triangle:** half of that, $`\frac{3\sqrt5}{2}`$.

**Why $`\frac12`$:** one diagonal of the parallelogram cuts it into two identical triangles. Triangle $`ABC`$ is one of them, so it has half the area.

---
