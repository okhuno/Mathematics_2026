### Exercise 13. Undoing a Composite Transformation
The matrices

```math
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad H=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
```

describe nonuniform scaling and shear. For $`T=HS`$, find $`T^{-1}`$ in two ways:

1. first compute $`T`$, then its inverse,
2. use $`(HS)^{-1}=S^{-1}H^{-1}`$.

Compare the results. Additionally compute $`H^{-1}S^{-1}`$ and verify that the incorrect order gives a different matrix. Explain the rule: “when undoing a composition of operations, we undo them from the end.”

> **Why this exercise:** reinforces the inverse of a product in a less direct configuration.

#### Answer

```math
T^{-1}=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix},\qquad H^{-1}S^{-1}=\begin{pmatrix}\frac12&-1\\0&1\end{pmatrix}\ne T^{-1}.
```

#### How I solved it
1. **Way 1:** $`T=HS=\begin{pmatrix}1\cdot2+1\cdot0&1\cdot0+1\cdot1\\0&1\end{pmatrix}=\begin{pmatrix}2&1\\0&1\end{pmatrix}`$, $`\det T=2`$, so $`T^{-1}=\frac12\begin{pmatrix}1&-1\\0&2\end{pmatrix}=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}`$.
2. **Way 2:** $`S^{-1}=\begin{pmatrix}\frac12&0\\0&1\end{pmatrix}`$ and $`H^{-1}=\begin{pmatrix}1&-1\\0&1\end{pmatrix}`$. Then

```math
S^{-1}H^{-1}=\begin{pmatrix}\frac12&0\\0&1\end{pmatrix}\begin{pmatrix}1&-1\\0&1\end{pmatrix}=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}.
```

Same as Way 1 ✓.
3. **Wrong order:** $`H^{-1}S^{-1}=\begin{pmatrix}1&-1\\0&1\end{pmatrix}\begin{pmatrix}\frac12&0\\0&1\end{pmatrix}=\begin{pmatrix}\frac12&-1\\0&1\end{pmatrix}`$. The top-right entry is $`-1`$, not $`-\frac12`$: different matrix.

**The rule:** $`T=HS`$ means "apply $`S`$ first, then $`H`$." To go back we must reverse the last step first: undo $`H`$ (apply $`H^{-1}`$), and then undo $`S`$ (apply $`S^{-1}`$). As a product acting on a vector this is $`S^{-1}H^{-1}`$.

---
