### Exercise 15. Comparing Directions Using the Cosine of the Angle
Given

```math
a=(1,2,1),\qquad b=(2,4,2),\qquad c=(2,0,3).
```

For each pair, compute

```math
\frac{u\cdot v}{\|u\|\,\|v\|}.
```

Order the pairs by increasing angle between the vectors. Explain why for $`a`$ and $`b`$ the value is $`1`$ even though the vectors have different lengths.

> **Why this exercise:** reinforces the connection between the dot product and angle, and the distinction between direction and length.

#### Answer

| Pair | Cosine | Angle |
|---|---|---|
| $`a,b`$ | $`1`$ | $`0^\circ`$ |
| $`a,c`$ | $`\dfrac{5}{\sqrt{78}}\approx0.566`$ | $`\approx55.5^\circ`$ |
| $`b,c`$ | $`\dfrac{5}{\sqrt{78}}\approx0.566`$ | $`\approx55.5^\circ`$ |

Order by increasing angle: $`(a,b)<(a,c)=(b,c)`$.

#### How I solved it
**Idea:** the formula is the cosine of the angle. A **bigger cosine means a smaller angle**.

1. **Lengths:** $`\|a\|=\sqrt{1+4+1}=\sqrt6`$, $`\|b\|=\sqrt{24}=2\sqrt6`$, $`\|c\|=\sqrt{4+0+9}=\sqrt{13}`$.
2. **Dot products:**
   - $`a\cdot b=2+8+2=12`$
   - $`a\cdot c=2+0+3=5`$
   - $`b\cdot c=4+0+6=10`$
3. **Cosines:**
   - $`a,b`$: $`\dfrac{12}{\sqrt6\cdot2\sqrt6}=\dfrac{12}{12}=1`$
   - $`a,c`$: $`\dfrac{5}{\sqrt6\cdot\sqrt{13}}=\dfrac{5}{\sqrt{78}}`$
   - $`b,c`$: $`\dfrac{10}{2\sqrt6\cdot\sqrt{13}}=\dfrac{5}{\sqrt{78}}`$
4. **Order:** largest cosine means smallest angle, so $`(a,b)`$ comes first, then $`(a,c)`$ and $`(b,c)`$ tied.

**Why $`a,b`$ gives exactly $`1`$ even though the lengths differ:** $`b=2a`$, so they point in exactly the same direction. The angle is $`0^\circ`$ and $`\cos0^\circ=1`$. The formula divides by both lengths, so it measures only **direction** and ignores length. For the same reason $`(a,c)`$ and $`(b,c)`$ give the same value: $`b`$ is just a longer copy of $`a`$.
