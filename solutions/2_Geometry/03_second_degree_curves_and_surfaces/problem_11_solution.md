### Exercise 11. Two Similar Surfaces
Compare

```math
x^2+y^2-z^2=1
```

and

```math
x^2+y^2-z^2=-1.
```

For several values $`z=c`$, check whether the cross-section exists and what its radius is. Based on this, describe qualitatively the difference between the surfaces and make sketches.

> **Why this exercise:** teaches how to recognize the shape of a surface from cross-sections instead of from a memorized catalog of names.

#### Answer

| $`z=c`$ | $`x^2+y^2-z^2=1`$ | $`x^2+y^2-z^2=-1`$ |
|---|---|---|
| general | $`x^2+y^2=1+c^2`$ | $`x^2+y^2=c^2-1`$ |
| $`c=0`$ | circle, $`r=1`$ | **no points** |
| $`c=\pm1`$ | circle, $`r=\sqrt2`$ | a single point (radius $`0`$) |
| $`c=\pm2`$ | circle, $`r=\sqrt5`$ | circle, $`r=\sqrt3`$ |

- First surface: a circle exists for **every** $`c`$, with the smallest radius ($`1`$) at $`z=0`$. It is one connected piece shaped like an hourglass tube or cooling tower (**hyperboloid of one sheet**).
- Second surface: circles exist only for $`|c|\ge1`$. There are two separate pieces, one above $`z=1`$ and one below $`z=-1`$, like two bowls facing away from each other (**hyperboloid of two sheets**).

#### How I solved it
Move $`z^2`$ to the right side: $`x^2+y^2=1+z^2`$ (first) or $`x^2+y^2=z^2-1`$ (second). Put $`z=c`$.
- First: the right side $`1+c^2\ge1>0`$ for every $`c`$, so there is always a circle of radius $`\sqrt{1+c^2}`$. The radius is smallest at $`c=0`$ and grows in both directions.
- Second: we need $`c^2-1\ge0`$, so $`|c|\ge1`$. For $`|c|<1`$ there is nothing, which creates a gap between the two pieces.

---
