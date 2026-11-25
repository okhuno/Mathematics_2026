### Exercise 8. Determinant of a Product
Let $`A,B`$ be square matrices such that $`\det A=3`$ and $`\det B=-5`$. Compute $`\det(AB)`$, $`\det(BA)`$ and, if it exists, $`\det(A^{-1}B)`$. Explain why the first two results are equal even though usually $`AB\neq BA`$.

> **Why this exercise:** organizes how determinants behave with respect to products and inverses.

#### Answer
- $`\det(AB)=-15`$
- $`\det(BA)=-15`$
- $`\det(A^{-1}B)=-\frac53`$ (it exists because $`\det A=3\ne0`$, so $`A`$ is invertible)

#### How I solved it
- $`\det(AB)=\det A\cdot\det B=3\cdot(-5)=-15`$.
- $`\det(BA)=\det B\cdot\det A=-5\cdot3=-15`$.
- $`A^{-1}`$ exists since $`\det A\ne0`$. $`\det(A^{-1})=\frac1{\det A}=\frac13`$, so $`\det(A^{-1}B)=\frac13\cdot(-5)=-\frac53`$.

**Why $`\det(AB)=\det(BA)`$:** even though the matrices $`AB`$ and $`BA`$ may be different, their determinants are products of two **numbers**, and ordinary multiplication of numbers is commutative: $`3\cdot(-5)=(-5)\cdot3`$.

---
