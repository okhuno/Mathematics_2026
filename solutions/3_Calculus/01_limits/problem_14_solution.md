### Exercise 14. A $`0/0`$ Limit with Trigonometry
Compute

```math
\lim_{x\to0}\frac{1-\cos x}{x^2}.
```

Justify the result without using l'Hôpital's rule, using a trigonometric identity and the fundamental limit.

> **Why this exercise:** requires combining two known tools in one argument.

#### Answer

```math
\frac12
```

#### How I solved it
1. Substitution gives $`\frac00`$.
2. **Multiply and divide by $`1+\cos x`$:**

```math
\frac{1-\cos x}{x^2}\cdot\frac{1+\cos x}{1+\cos x}=\frac{1-\cos^2x}{x^2(1+\cos x)}.
```

3. **Identity** $`1-\cos^2x=\sin^2x`$: $`\ \dfrac{\sin^2x}{x^2(1+\cos x)}=\left(\dfrac{\sin x}{x}\right)^2\cdot\dfrac{1}{1+\cos x}`$.
4. **Limit:** $`\left(\frac{\sin x}{x}\right)^2\to1^2=1`$ and $`\frac1{1+\cos x}\to\frac1{1+1}=\frac12`$.

Result: $`1\cdot\frac12=\frac12`$.

---
