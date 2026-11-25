### Exercise 15. Recognition and Sketch Without a Given Name
Consider the two equations:

```math
4x^2+9y^2-8x+36y+4=0,
```

```math
4x^2+y^2=z^2.
```

For the first equation, reduce it to canonical form, recognize the curve, give its most important features, and make a sketch.

For the second equation, do not begin by using a ready-made name for the surface. First describe the cross-sections $`z=c`$ and the cross-sections by the planes $`x=0`$ and $`y=0`$, paying attention to the different scales along the axes. Only then identify the surface and make a sketch.

> **Why this exercise:** tests transfer of the two main mechanisms of the set—moving to canonical form and recognizing an object through cross-sections—without allowing the easiest example to be chosen.

#### Answer
**First equation:** $`\dfrac{(x-1)^2}{9}+\dfrac{(y+2)^2}{4}=1`$, an ellipse with center $`(1,-2)`$, semi-axes $`3`$ (horizontal) and $`2`$ (vertical), vertices $`(4,-2),(-2,-2),(1,0),(1,-4)`$.

**Second equation:** an **elliptic cone** (vertex at the origin, axis along $`z`$). Horizontal slices are ellipses, vertical slices through the axis are pairs of lines.

#### How I solved it
**First equation (completing the square):**
1. $`4(x^2-2x)+9(y^2+4y)=-4`$.
2. $`x^2-2x=(x-1)^2-1`$ and $`y^2+4y=(y+2)^2-4`$.
3. $`4[(x-1)^2-1]+9[(y+2)^2-4]=-4\Rightarrow4(x-1)^2+9(y+2)^2=-4+4+36=36`$.
4. Divide by $`36`$: $`\frac{(x-1)^2}{9}+\frac{(y+2)^2}{4}=1`$.
5. **Check:** vertex $`(4,-2)`$ in the original: $`64+36-32-72+4=0`$ ✓. Vertex $`(1,0)`$: $`4+0-8+0+4=0`$ ✓.

**Second equation (cross-sections first):**
- **$`z=c`$:** $`4x^2+y^2=c^2`$. Divide by $`c^2`$ (for $`c\ne0`$): $`\frac{x^2}{(c/2)^2}+\frac{y^2}{c^2}=1`$. This is an ellipse with semi-axes $`|c|/2`$ along $`x`$ and $`|c|`$ along $`y`$. At $`c=0`$ it is the single point (origin). The ellipse is twice as long in the $`y`$ direction as in the $`x`$ direction at every height, and it grows with $`|c|`$.
- **$`x=0`$:** $`y^2=z^2`$, so the lines $`z=\pm y`$.
- **$`y=0`$:** $`4x^2=z^2`$, so the lines $`z=\pm2x`$ (steeper in $`x`$: narrower in the $`x`$ direction).
- **Identify:** ellipses that grow linearly with height and shrink to a point at the origin, plus straight-line vertical sections: a cone whose cross-section is an ellipse instead of a circle (an elliptic cone).
