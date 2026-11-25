### Problem 8. Choosing the Factors in Integration by Parts
Compute

```math
\int x\cos x\,dx.
```

Before calculating, justify why it is convenient to differentiate $`x`$ and integrate $`\cos x`$, rather than the other way around.

> **Why this problem:** it teaches that integration by parts requires a deliberate choice of factors.

#### Answer

```math
x\sin x+\cos x+C
```

#### How I solved it
**Why this choice:** if $`u=x`$, differentiating gives $`u'=1`$ (simpler), and $`v'=\cos x`$ integrates easily to $`v=\sin x`$. The other way around ($`u=\cos x`$, $`v'=x`$) would give $`v=\frac{x^2}2`$ and a new integral $`\int\frac{x^2}{2}\sin x\,dx`$ that is **harder** than the original.

**Computation:** $`\int x\cos x\,dx=x\sin x-\int1\cdot\sin x\,dx=x\sin x+\cos x+C`$.

**Verify:** $`(x\sin x+\cos x)'=\sin x+x\cos x-\sin x=x\cos x`$ ✓

---
