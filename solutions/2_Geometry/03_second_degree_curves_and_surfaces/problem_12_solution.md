### Exercise 12. Recognizing a Surface from Cross-Sections
A certain surface has the following properties:
- the cross-section $`z=0`$ is a point,
- for $`z>0`$, the cross-sections $`z=\mathrm{const}`$ are circles with increasing radius,
- vertical cross-sections through the $`Oz`$ axis are parabolas.

Propose a simple equation for such a surface and justify your choice.

> **Why this exercise:** reverses the usual reasoning: from geometry to an equation.

#### Answer

```math
z=x^2+y^2
```

(a circular paraboloid).

#### How I solved it
- Circles in horizontal slices suggest the combination $`x^2+y^2`$ (it only depends on the distance from the $`z`$-axis). So try $`z=x^2+y^2`$.
- **$`z=0`$:** $`x^2+y^2=0`$ means only the point $`(0,0)`$ ✓.
- **$`z=c>0`$:** $`x^2+y^2=c`$ is a circle of radius $`\sqrt c`$, which grows as $`c`$ grows ✓.
- **Vertical section through the $`z`$-axis** (for example $`x=0`$): $`z=y^2`$, a parabola ✓. The same holds for $`y=0`$ and any plane through the $`z`$-axis.
- For $`z<0`$ there are no points (since $`x^2+y^2\ge0`$).

A cone $`z^2=x^2+y^2`$ would not work, since its vertical sections are straight lines, not parabolas.

---
