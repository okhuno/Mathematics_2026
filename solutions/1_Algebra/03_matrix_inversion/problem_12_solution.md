### Exercise 12. Finding Inverses Without Starting from Scratch
It is known that

```math
A^{-1}=
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}.
```

Without finding $`A`$, compute $`(3A)^{-1}`$, $`(A^T)^{-1}`$, and $`(A^2)^{-1}`$. Justify each result using the appropriate property.

> **Why this exercise:** teaches how to use inverse properties instead of carrying out unnecessary full calculations.

#### Answer
- $`(3A)^{-1}=\begin{pmatrix}\frac23&-\frac13\\-1&\frac23\end{pmatrix}`$
- $`(A^T)^{-1}=\begin{pmatrix}2&-3\\-1&2\end{pmatrix}`$
- $`(A^2)^{-1}=\begin{pmatrix}7&-4\\-12&7\end{pmatrix}`$

#### How I solved it
1. **$`(3A)^{-1}=\frac13A^{-1}`$.** Property: $`(kA)^{-1}=\frac1kA^{-1}`$ (if you scale a matrix by $`3`$, its inverse is scaled by $`\frac13`$). So divide every entry by $`3`$.
2. **$`(A^T)^{-1}=(A^{-1})^T`$.** Property: the inverse of the transpose is the transpose of the inverse. Swap rows and columns of $`A^{-1}`$: $`\begin{pmatrix}2&-3\\-1&2\end{pmatrix}`$.
3. **$`(A^2)^{-1}=(A^{-1})^2`$.** Property: $`(AA)^{-1}=A^{-1}A^{-1}`$ (the product rule with $`B=A`$). Compute:

```math
\begin{pmatrix}2&-1\\-3&2\end{pmatrix}^2=\begin{pmatrix}2\cdot2+(-1)(-3)&2(-1)+(-1)2\\-3\cdot2+2(-3)&(-3)(-1)+2\cdot2\end{pmatrix}=\begin{pmatrix}7&-4\\-12&7\end{pmatrix}.
```

---
