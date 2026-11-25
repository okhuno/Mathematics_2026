### Problem 11. Choose the Method First
For each integral, first write which method you choose and how you recognize it, and then compute:

1. $`\int\sin(3x)\,dx`$,
2. $`\int x\ln x\,dx`$,
3. $`\int\frac{x}{\sqrt{x^2+1}}\,dx`$.

> **Why this problem:** it tests the choice of method based on the structure of the problem.

#### Answer
1. $`-\frac13\cos(3x)+C`$
2. $`\frac{x^2}2\ln x-\frac{x^2}{4}+C`$ (for $`x>0`$)
3. $`\sqrt{x^2+1}+C`$

#### How I solved it
1. **Method: substitution.** Recognized by: $`\sin`$ of a linear inside $`3x`$, whose derivative is the constant $`3`$. Let $`u=3x`$, $`du=3\,dx`$: $`\frac13\int\sin u\,du=-\frac13\cos u=-\frac13\cos3x+C`$.
2. **Method: integration by parts.** Recognized by: a product of $`x`$ (easy to integrate) and $`\ln x`$ (hard to integrate, but its derivative $`\frac1x`$ is simple). Take $`u=\ln x`$, $`v'=x`$, so $`u'=\frac1x`$, $`v=\frac{x^2}2`$:

```math
\int x\ln x\,dx=\frac{x^2}{2}\ln x-\int\frac{x^2}{2}\cdot\frac1x\,dx=\frac{x^2}2\ln x-\int\frac x2dx=\frac{x^2}{2}\ln x-\frac{x^2}{4}+C.
```

3. **Method: substitution.** Recognized by: inside the root is $`x^2+1`$ and its derivative $`2x`$ matches the numerator (up to a constant). Let $`u=x^2+1`$, $`x\,dx=\frac12du`$: $`\frac12\int u^{-1/2}du=\frac12\cdot2u^{1/2}=\sqrt{x^2+1}+C`$.

**Verify:**
- (1) $`\left(-\frac13\cos3x\right)'=\sin3x`$ ✓
- (2) $`\left(\frac{x^2}{2}\ln x-\frac{x^2}{4}\right)'=x\ln x+\frac x2-\frac x2=x\ln x`$ ✓
- (3) $`\left(\sqrt{x^2+1}\right)'=\frac{2x}{2\sqrt{x^2+1}}=\frac{x}{\sqrt{x^2+1}}`$ ✓

---
