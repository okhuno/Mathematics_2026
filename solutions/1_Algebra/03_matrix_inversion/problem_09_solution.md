### Exercise 9. Matrix Equation
Given

```math
A=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}.
```

Solve the equation $`AX=B`$ for $`X`$. Before calculating, decide on which side of the equation $`A^{-1}`$ must be used. Then check the result by computing $`AX`$.

> **Why this exercise:** teaches that order matters in matrix equations and must guide the solution.

#### Answer

```math
X=\begin{pmatrix}-1&-7\\2&4\end{pmatrix}
```

#### How I solved it
**Which side:** in $`AX=B`$ the matrix $`A`$ stands on the **left** of $`X`$. To cancel it we must multiply both sides **on the left** by $`A^{-1}`$: $`A^{-1}AX=A^{-1}B\Rightarrow X=A^{-1}B`$. (Multiplying on the right would give $`AXA^{-1}`$, which does not simplify, because matrices do not commute.)

1. **Inverse of $`A`$:** $`\det A=1`$, so $`A^{-1}=\begin{pmatrix}1&-2\\0&1\end{pmatrix}`$.
2. **Multiply:** $`X=A^{-1}B=\begin{pmatrix}1\cdot3-2\cdot2&1\cdot1-2\cdot4\\2&4\end{pmatrix}=\begin{pmatrix}-1&-7\\2&4\end{pmatrix}`$.

**Check ($`AX`$):** $`\begin{pmatrix}1&2\\0&1\end{pmatrix}\begin{pmatrix}-1&-7\\2&4\end{pmatrix}=\begin{pmatrix}-1+4&-7+8\\2&4\end{pmatrix}=\begin{pmatrix}3&1\\2&4\end{pmatrix}=B`$ ✓

---
