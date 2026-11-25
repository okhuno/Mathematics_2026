### Exercise 3. Vector Normalization
For $`v=(3,4)`$ find a unit vector $`e`$ with the same direction and orientation. Check that $`\|e\|=1`$, reconstruct $`v`$ in the form $`v=\|v\|e`$, and explain what changes during normalization and what remains unchanged.

> **Why this exercise:** teaches how to separate direction from vector length.

#### Answer
- $`\|v\|=5`$
- $`e=\left(\frac35,\frac45\right)`$
- $`\|e\|=1`$ ✓ and $`v=5e=(3,4)`$ ✓

#### How I solved it
**Idea:** a unit vector has length $`1`$. To get one, divide the vector by its own length.

1. **Length of $`v`$:** $`\sqrt{3^2+4^2}=\sqrt{25}=5`$.
2. **Divide each component by 5:** $`e=\left(\frac35,\frac45\right)`$.
3. **Check the length:** $`\sqrt{\frac{9}{25}+\frac{16}{25}}=\sqrt1=1`$ ✓
4. **Rebuild $`v`$:** $`5\cdot\left(\frac35,\frac45\right)=(3,4)`$ ✓

**What changes / what stays:** the **length** changes (from $`5`$ to $`1`$). The **direction** stays the same, because we divided by a positive number. So any vector = (its length) × (a unit vector showing its direction).

---
