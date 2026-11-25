### Exercise 7. Using Properties Instead of Recomputing
Suppose that for a $`3\times3`$ matrix, $`\det A=-4`$. Compute

```math
\det(2A),\qquad \det(A^T),\qquad \det(A^2),\qquad \det(-A).
```

Justify each answer using the appropriate property.

> **Why this exercise:** teaches how to use determinant properties instead of repeating a full calculation.

#### Answer
- $`\det(2A)=-32`$
- $`\det(A^T)=-4`$
- $`\det(A^2)=16`$
- $`\det(-A)=4`$

#### How I solved it
- $`\det(2A)`$: $`2A`$ multiplies **each of the 3 rows** by $`2`$, and each row multiplication multiplies the determinant by $`2`$. So $`\det(2A)=2^3\det A=8\cdot(-4)=-32`$.
- $`\det(A^T)=\det A=-4`$ (transposing does not change the determinant).
- $`\det(A^2)=\det(A\cdot A)=\det A\cdot\det A=(-4)^2=16`$.
- $`\det(-A)=(-1)^3\det A=-1\cdot(-4)=4`$ (same rule as the first with $`k=-1`$ and $`n=3`$).

---
