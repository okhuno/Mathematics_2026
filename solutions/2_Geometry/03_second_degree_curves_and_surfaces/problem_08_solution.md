### Exercise 8. Sphere
Reduce

```math
x^2+y^2+z^2-4x+2y-6z-2=0
```

to canonical form. Find the center and radius. Give two points on the sphere and check them in the equation.

> **Why this exercise:** transfers the technique known from circles from two dimensions to three.

#### Answer
- Canonical form: $`(x-2)^2+(y+1)^2+(z-3)^2=16`$
- Center $`(2,-1,3)`$, radius $`4`$
- Points: $`(6,-1,3)`$ and $`(2,3,3)`$.

#### How I solved it
1. **Complete the square in each variable:**
   - $`x^2-4x=(x-2)^2-4`$
   - $`y^2+2y=(y+1)^2-1`$
   - $`z^2-6z=(z-3)^2-9`$
2. **Substitute:** $`(x-2)^2+(y+1)^2+(z-3)^2-4-1-9-2=0`$, so the right side becomes $`16`$.
3. **Read off:** center $`(2,-1,3)`$, radius $`\sqrt{16}=4`$.

**Check two points** (move $`4`$ units from the center along an axis):
- $`(6,-1,3)`$: canonical $`16+0+0=16`$ ✓. Original: $`36+1+9-24-2-18-2=0`$ ✓.
- $`(2,3,3)`$: canonical $`0+16+0=16`$ ✓. Original: $`4+9+9-8+6-18-2=0`$ ✓.

---
