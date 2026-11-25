### Exercise 7. Inverse of a Product
For

```math
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
2 & 0 \\
0 & 3 \\
\end{pmatrix}
```

compute $`(AB)^{-1}`$ and $`B^{-1}A^{-1}`$. Check that the results are the same and explain the meaning of the reversed order.

> **Why this exercise:** reinforces the inverse-of-a-product property and requires its interpretation.

#### Answer

```math
(AB)^{-1}=B^{-1}A^{-1}=\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}
```

#### How I solved it
1. **Product:** $`AB=\begin{pmatrix}1\cdot2&1\cdot3\\0&3\end{pmatrix}=\begin{pmatrix}2&3\\0&3\end{pmatrix}`$, with $`\det=6`$.
2. **$`(AB)^{-1}`$ by the formula:** $`\frac16\begin{pmatrix}3&-3\\0&2\end{pmatrix}=\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}`$.
3. **Separate inverses:** $`A^{-1}=\begin{pmatrix}1&-1\\0&1\end{pmatrix}`$ and $`B^{-1}=\begin{pmatrix}\frac12&0\\0&\frac13\end{pmatrix}`$.
4. **$`B^{-1}A^{-1}`$:** $`\begin{pmatrix}\frac12&0\\0&\frac13\end{pmatrix}\begin{pmatrix}1&-1\\0&1\end{pmatrix}=\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}`$.

Both agree ✓.

**Meaning of the reversed order:** $`AB`$ means "first $`B`$, then $`A`$." To undo it we must undo the **last** step first: first $`A^{-1}`$, then $`B^{-1}`$. Written as a product, that is $`B^{-1}A^{-1}`$. (Think of socks and shoes: you put on socks first, then shoes; to undo, you take off shoes first, then socks.)

---
