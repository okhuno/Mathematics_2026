### Problem 9. Minimizing the Material Used for a Can
A closed cylinder has fixed volume $`V`$.

1. Write the volume constraint.
2. Eliminate one of the variables.
3. Express the surface area as a function of the radius $`r`$.
4. Find the relation between the height $`h`$ and the radius $`r`$ for which the material usage is minimal.

Interpret the obtained relation geometrically.

> **Why this problem:** it requires independent reduction of a problem with two variables to one objective function and control of the geometric constraint.

#### Answer
- Constraint: $`\pi r^2h=V`$.
- $`S(r)=2\pi r^2+\dfrac{2V}{r}`$.
- Minimum when $`r=\sqrt[3]{\dfrac V{2\pi}}`$, and then $`h=2r`$.

#### How I solved it
1. **Constraint:** $`V=\pi r^2h`$.
2. **Eliminate $`h`$:** $`h=\dfrac{V}{\pi r^2}`$.
3. **Surface area** (two circles plus the side): $`S=2\pi r^2+2\pi rh=2\pi r^2+2\pi r\cdot\dfrac{V}{\pi r^2}=2\pi r^2+\dfrac{2V}{r}`$.
4. **Derivative:** $`S'(r)=4\pi r-\dfrac{2V}{r^2}=0\Rightarrow r^3=\dfrac{V}{2\pi}`$.
5. **Find $`h`$:** $`V=2\pi r^3`$, so $`h=\dfrac{V}{\pi r^2}=\dfrac{2\pi r^3}{\pi r^2}=2r`$.
6. **Minimum check:** $`S''(r)=4\pi+\dfrac{4V}{r^3}>0`$, so it is a minimum.

**Geometric meaning:** $`h=2r`$ means the height equals the diameter. Looking at the can from the side you see a **square**.

---
