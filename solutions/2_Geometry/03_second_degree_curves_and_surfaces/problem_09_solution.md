### Exercise 9. Ellipsoid and Its Cross-Sections
Consider

```math
\frac{x^2}{9}+\frac{y^2}{4}+\frac{z^2}{16}=1.
```

Give the semiaxis lengths, describe the cross-section $`z=0`$, and explain how the cross-sections $`z=c`$ change for $`|c|<4`$.

> **Why this exercise:** teaches how to understand a 3D surface through a family of simpler 2D cross-sections.

#### Answer
- Semi-axes: $`3`$ (along $`x`$), $`2`$ (along $`y`$), $`4`$ (along $`z`$).
- $`z=0`$: the ellipse $`\frac{x^2}{9}+\frac{y^2}{4}=1`$.
- $`z=c`$, $`|c|<4`$: an ellipse with semi-axes $`3\sqrt{1-\frac{c^2}{16}}`$ and $`2\sqrt{1-\frac{c^2}{16}}`$. It shrinks as $`|c|`$ grows and becomes a single point at $`|c|=4`$.

#### How I solved it
- Denominators $`9,4,16`$ give semi-axes $`3,2,4`$.
- **Cross-section $`z=0`$:** the $`z`$-term disappears, leaving $`\frac{x^2}{9}+\frac{y^2}{4}=1`$.
- **Cross-section $`z=c`$:** move the $`z`$ term to the right: $`\frac{x^2}{9}+\frac{y^2}{4}=1-\frac{c^2}{16}`$. Let $`k=1-\frac{c^2}{16}`$. If $`|c|<4`$ then $`k>0`$, so dividing by $`k`$ gives an ellipse with semi-axes $`3\sqrt k`$ and $`2\sqrt k`$.
- **Behavior:** at $`c=0`$, $`k=1`$ (the biggest ellipse). As $`|c|\to4`$, $`k\to0`$ and the ellipse shrinks. At $`|c|=4`$ only the point $`(0,0,\pm4)`$ remains. For $`|c|>4`$, $`k<0`$ and there are no points.

So the ellipsoid is a stack of ellipses that grow and then shrink: like an egg shape.

---
