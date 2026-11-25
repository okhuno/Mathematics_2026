### Exercise 14. A System of Equations and the Determinant
Consider the system $`Ax=b`$, where

```math
A=
\begin{pmatrix}
1 & 2 \\
k & 4 \\
\end{pmatrix}.
```

For which values of $`k`$ does the system have exactly one solution for every $`b`$? For the remaining value, give an example of a right-hand side $`b`$ for which the system has infinitely many solutions, and an example for which it has no solution.

> **Why this exercise:** connects the determinant with uniqueness of solutions and requires distinguishing the exceptional cases.

#### Answer
- Exactly one solution for every $`b`$ when $`k\neq2`$.
- For $`k=2`$: $`b=(1,2)^T`$ gives infinitely many solutions; $`b=(1,3)^T`$ gives no solution.

#### How I solved it
1. **Determinant:** $`\det A=1\cdot4-2\cdot k=4-2k`$.
2. $`\det A\neq0\iff k\ne2`$. Then $`A`$ is invertible, and $`x=A^{-1}b`$ is the unique solution for **every** $`b`$.
3. **Exceptional case $`k=2`$:** $`A=\begin{pmatrix}1&2\\2&4\end{pmatrix}`$. The second row is twice the first, so the left sides satisfy $`2x+4y=2(x+2y)`$. The system is $`x+2y=b_1`$, $`2x+4y=b_2`$.
   - **Infinitely many:** need $`b_2=2b_1`$. Take $`b=(1,2)^T`$: both equations say $`x+2y=1`$ (one line, infinitely many solutions).
   - **No solution:** $`b_2\neq2b_1`$. Take $`b=(1,3)^T`$: $`x+2y=1`$ and $`2x+4y=3`$ would force $`2=3`$. Contradiction.

---
