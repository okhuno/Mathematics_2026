### Exercise 10. Paraboloids
Compare

```math
z=x^2+y^2
```

and

```math
z=x^2-y^2.
```

For each surface, describe the cross-sections $`x=0`$, $`y=0`$, and $`z=c`$, then make a qualitative sketch.

> **Why this exercise:** teaches how to distinguish two basic types of paraboloids from their cross-sections.

#### Answer

| Cross-section | $`z=x^2+y^2`$ (bowl) | $`z=x^2-y^2`$ (saddle) |
|---|---|---|
| $`x=0`$ | $`z=y^2`$: parabola opening **up** | $`z=-y^2`$: parabola opening **down** |
| $`y=0`$ | $`z=x^2`$: parabola opening **up** | $`z=x^2`$: parabola opening **up** |
| $`z=c`$ | $`c<0`$: empty; $`c=0`$: point; $`c>0`$: circle of radius $`\sqrt c`$ | $`c>0`$: hyperbola ($`x^2-y^2=c`$, opens along $`x`$); $`c<0`$: hyperbola (opens along $`y`$); $`c=0`$: two lines $`y=\pm x`$ |

**Sketch description:** the first is a round bowl (like a satellite dish) with its lowest point at the origin. The second is a saddle (like a horse saddle or a Pringles chip): it curves up along the $`x`$-direction and down along the $`y`$-direction.

#### How I solved it
For each surface I substituted $`x=0`$, $`y=0`$ or $`z=c`$ into the equation and recognized the resulting 2D curve.

- Bowl: $`x=0`$ gives $`z=y^2`$, $`y=0`$ gives $`z=x^2`$. Both are upward parabolas. For $`z=c`$ we get $`x^2+y^2=c`$: the right side must be $`\ge0`$, and for $`c>0`$ it is a circle of radius $`\sqrt c`$.
- Saddle: $`x=0`$ gives $`z=-y^2`$ (downward parabola); $`y=0`$ gives $`z=x^2`$ (upward parabola). For $`z=c`$: $`x^2-y^2=c`$. If $`c=0`$, $`x^2=y^2`$ gives lines $`y=\pm x`$. If $`c>0`$ we get a hyperbola crossing the $`x`$-axis at $`x=\pm\sqrt c`$. If $`c<0`$ it is $`y^2-x^2=-c`$, crossing the $`y`$-axis.

---
