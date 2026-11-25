### Exercise 8. A Square Root in a Function Limit
Compute

```math
\lim_{x\to4}\frac{\sqrt{x}-2}{x-4}
```

by rationalizing the numerator. Compare the idea with Exercise 3 involving a sequence.

> **Why this exercise:** reinforces transferring the same algebraic technique between two types of limits.

#### Answer

```math
\frac14
```

#### How I solved it
1. Substitution gives $`\frac00`$.
2. **Multiply and divide by the conjugate** $`\sqrt x+2`$:

```math
\frac{(\sqrt x-2)(\sqrt x+2)}{(x-4)(\sqrt x+2)}=\frac{x-4}{(x-4)(\sqrt x+2)}=\frac1{\sqrt x+2}.
```

3. **Limit:** $`\frac1{\sqrt4+2}=\frac14`$.

**Comparison with Exercise 3:** the same trick: use $`(a-b)(a+b)=a^2-b^2`$ to remove the square root. In Exercise 3 it removed $`\infty-\infty`$; here it removes $`\frac00`$ by creating a factor $`(x-4)`$ that cancels.

---
