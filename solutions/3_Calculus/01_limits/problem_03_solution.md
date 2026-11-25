### Exercise 3. A Square Root and Removing an Indeterminate Form
Compute

```math
\lim_{n\to\infty}\left(\sqrt{n^2+5n}-n\right).
```

Use the conjugate expression and explain why this transformation removes the difficulty.

> **Why this exercise:** introduces conjugation as a deliberate technique for removing an indeterminate form.

#### Answer

```math
\frac52
```

#### How I solved it
1. **The problem:** both $`\sqrt{n^2+5n}`$ and $`n`$ go to $`\infty`$, so we have "$`\infty-\infty`$", which is undefined.
2. **Multiply and divide by the conjugate** $`\sqrt{n^2+5n}+n`$:

```math
\left(\sqrt{n^2+5n}-n\right)\cdot\frac{\sqrt{n^2+5n}+n}{\sqrt{n^2+5n}+n}=\frac{(n^2+5n)-n^2}{\sqrt{n^2+5n}+n}=\frac{5n}{\sqrt{n^2+5n}+n}.
```

3. **Divide top and bottom by $`n`$:** $`\dfrac{5}{\sqrt{1+\frac5n}+1}\to\dfrac{5}{1+1}=\dfrac52`$.

**Why the conjugate helps:** the difference of squares formula $`(a-b)(a+b)=a^2-b^2`$ removes the square root and cancels the two huge $`n^2`$ terms. What remains is a quotient we can handle.

---
