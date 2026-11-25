### Exercise 11. Decomposition into Parallel and Perpendicular Components
Decompose $`u=(3,4)`$ into components parallel and perpendicular to $`v=(1,2)`$. Check

```math
u=u_{\parallel}+u_{\perp},\qquad u_{\perp}\cdot v=0.
```

Explain why these are two independent checks of correctness.

> **Why this exercise:** deepens the idea of projection through construction and verification.

#### Answer
- $`u_\parallel=\left(\frac{11}{5},\frac{22}{5}\right)`$
- $`u_\perp=\left(\frac45,-\frac25\right)`$
- $`u_\parallel+u_\perp=(3,4)`$ ✓ and $`u_\perp\cdot v=0`$ ✓

#### How I solved it
**Idea:** same as Exercise 6. Split $`u`$ into a piece along $`v`$ and a piece at $`90^\circ`$ to $`v`$.

1. **Dot products:** $`u\cdot v=3+8=11`$ and $`v\cdot v=1+4=5`$.
2. **Parallel part (projection):** $`\frac{11}{5}(1,2)=\left(\frac{11}{5},\frac{22}{5}\right)`$.
3. **Perpendicular part (leftover):** $`(3,4)-\left(\frac{11}{5},\frac{22}{5}\right)=\left(\frac45,-\frac25\right)`$.
4. **Check 1 (sum):** $`\left(\frac{11}{5}+\frac45,\ \frac{22}{5}-\frac25\right)=(3,4)`$ ✓
5. **Check 2 (perpendicular):** $`\frac45\cdot1+\left(-\frac25\right)\cdot2=\frac45-\frac45=0`$ ✓

**Why these are two independent checks:**
- Check 1 only shows the pieces add up to $`u`$. That is true automatically, because we *defined* $`u_\perp`$ as "$`u`$ minus $`u_\parallel`$". Even a wrong projection would pass it.
- Check 2 shows the leftover really is at $`90^\circ`$ to $`v`$. A wrong projection would fail it.

So Check 2 is the one that really tests the projection.

---
