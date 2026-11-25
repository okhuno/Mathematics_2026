### Exercise 6. Transpose
For

```math
A=
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix}
```

compute $`A^T`$, $`B^T`$, and $`AB`$. Then verify in this example that

```math
(AB)^T=B^TA^T.
```

> **Why this exercise:** teaches transposition and an important property that reverses the order of factors.

#### Answer

```math
A^T=\begin{pmatrix}1&4\\2&5\\3&6\end{pmatrix},\quad B^T=\begin{pmatrix}1&2&-1\\0&1&3\end{pmatrix},\quad AB=\begin{pmatrix}2&11\\8&23\end{pmatrix}
```

```math
(AB)^T=B^TA^T=\begin{pmatrix}2&8\\11&23\end{pmatrix}
```

#### How I solved it
- **Transposes:** rows become columns.
- **$`AB`$** ($`2\times3`$ times $`3\times2`$ gives $`2\times2`$):
  - $`(1,1)`$: $`1\cdot1+2\cdot2+3\cdot(-1)=2`$
  - $`(1,2)`$: $`1\cdot0+2\cdot1+3\cdot3=11`$
  - $`(2,1)`$: $`4\cdot1+5\cdot2+6\cdot(-1)=8`$
  - $`(2,2)`$: $`4\cdot0+5\cdot1+6\cdot3=23`$
- **$`(AB)^T`$:** swap rows and columns of $`AB`$: $`\begin{pmatrix}2&8\\11&23\end{pmatrix}`$.
- **$`B^TA^T`$** ($`2\times3`$ times $`3\times2`$):
  - $`(1,1)`$: $`1\cdot1+2\cdot2+(-1)\cdot3=2`$
  - $`(1,2)`$: $`1\cdot4+2\cdot5+(-1)\cdot6=8`$
  - $`(2,1)`$: $`0\cdot1+1\cdot2+3\cdot3=11`$
  - $`(2,2)`$: $`0\cdot4+1\cdot5+3\cdot6=23`$

  So $`B^TA^T=\begin{pmatrix}2&8\\11&23\end{pmatrix}=(AB)^T`$ ✓. (Note: $`A^TB^T`$ is a $`3\times3`$ matrix, a different thing entirely; the order must be reversed.)

---
