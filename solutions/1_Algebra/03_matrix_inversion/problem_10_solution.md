### Exercise 10. Inverse of a Diagonal Matrix
Given

```math
D=
\begin{pmatrix}
2 & 0 & 0 \\
0 & -3 & 0 \\
0 & 0 & 5 \\
\end{pmatrix},\qquad E=
\begin{pmatrix}
2 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}.
```

Without using Gauss–Jordan elimination, decide which matrix is invertible. For the invertible matrix, give the inverse and check the result by multiplication.

> **Why this exercise:** teaches how to recognize invertibility and the inverse without using a full procedure when the matrix structure gives the answer immediately.

#### Answer
- $`D`$ is invertible, $`D^{-1}=\begin{pmatrix}\frac12&0&0\\0&-\frac13&0\\0&0&\frac15\end{pmatrix}`$.
- $`E`$ is **not** invertible.

#### How I solved it
- A diagonal matrix is invertible exactly when **all diagonal entries are nonzero**, and its inverse is obtained by taking the reciprocal of each diagonal entry.
- $`D`$: entries $`2,-3,5`$ are all nonzero, so $`D^{-1}=\mathrm{diag}\left(\frac12,-\frac13,\frac15\right)`$.
- $`E`$: the middle entry is $`0`$. The whole second row is zero (a row of zeros means dependent rows, and $`\det E=2\cdot0\cdot5=0`$), so $`E`$ has no inverse.

**Check $`DD^{-1}`$:** it is diagonal with entries $`2\cdot\frac12=1`$, $`(-3)\cdot\left(-\frac13\right)=1`$, $`5\cdot\frac15=1`$, so $`DD^{-1}=I`$ ✓.

---
