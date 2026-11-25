### Exercise 15. Combining Determinant Properties
Let $`A`$ and $`B`$ be invertible $`2\times2`$ matrices with

```math
\det A=-2,\qquad \det B=3.
```

Without finding the entries of the matrices, compute

```math
\det\left(B^{-1}A^TB\right).
```

State the determinant properties you use in order and explain why the factors involving $`B`$ eventually cancel.

> **Why this exercise:** tests the transfer of several known properties into one short problem instead of checking a single property again with numbers.

#### Answer

```math
\det\left(B^{-1}A^TB\right)=-2
```

#### How I solved it
1. **Product rule:** $`\det(B^{-1}A^TB)=\det(B^{-1})\cdot\det(A^T)\cdot\det(B)`$.
2. **Inverse rule:** $`\det(B^{-1})=\frac1{\det B}=\frac13`$.
3. **Transpose rule:** $`\det(A^T)=\det A=-2`$.
4. **Multiply:** $`\frac13\cdot(-2)\cdot3=-2`$.

**Why the $`B`$ factors cancel:** the numbers $`\det(B^{-1})=\frac1{\det B}`$ and $`\det B`$ multiply to $`1`$: $`\frac13\cdot3=1`$. (Because determinants are just numbers, the order of the factors does not matter, even though the matrices $`B^{-1}`$, $`A^T`$, $`B`$ do not commute.) What remains is $`\det A^T=\det A=-2`$.
