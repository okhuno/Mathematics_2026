### Exercise 8. Inverse of a Transformation
The matrix

```math
S=
\begin{pmatrix}
2 & 0 \\
0 & \frac12 \\
\end{pmatrix}
```

describes a scaling of the plane. Find $`S^{-1}`$ and explain geometrically what the inverse transformation does. Check the action of the pair $`S,S^{-1}`$ on one simple vector.

> **Why this exercise:** gives the inverse the interpretation of undoing a transformation.

#### Answer

```math
S^{-1}=\begin{pmatrix}\frac12&0\\0&2\end{pmatrix}
```

#### How I solved it
- **Inverse:** $`S`$ is diagonal, so invert each diagonal entry: $`2\to\frac12`$ and $`\frac12\to2`$.
- **Geometry:** $`S`$ stretches the plane by $`2`$ in the $`x`$ direction and squeezes it by $`\frac12`$ in the $`y`$ direction. $`S^{-1}`$ does the opposite: it squeezes $`x`$ by $`\frac12`$ and stretches $`y`$ by $`2`$, undoing the effect.

**Check on $`(1,1)`$:**
- $`S(1,1)=(2,\ \frac12)`$
- $`S^{-1}(2,\frac12)=\left(\frac12\cdot2,\ 2\cdot\frac12\right)=(1,1)`$ ✓ We are back where we started.

---
