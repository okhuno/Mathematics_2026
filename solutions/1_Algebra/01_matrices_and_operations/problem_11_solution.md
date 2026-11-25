### Exercise 11. When Do Matrices Commute?
Given

```math
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix}.
```

Find the conditions on $`a,b,c,d`$ under which $`AB=BA`$. Describe the general form of all such matrices $`B`$.

> **Why this exercise:** deepens the idea of noncommutativity by finding the conditions under which commutativity does hold.

#### Answer
$`AB=BA`$ exactly when $`c=0`$ and $`d=a`$:

```math
B=\begin{pmatrix}a&b\\0&a\end{pmatrix},\qquad a,b\ \text{arbitrary}.
```

#### How I solved it
- $`AB=\begin{pmatrix}1&1\\0&1\end{pmatrix}\begin{pmatrix}a&b\\c&d\end{pmatrix}=\begin{pmatrix}a+c&b+d\\c&d\end{pmatrix}`$.
- $`BA=\begin{pmatrix}a&b\\c&d\end{pmatrix}\begin{pmatrix}1&1\\0&1\end{pmatrix}=\begin{pmatrix}a&a+b\\c&c+d\end{pmatrix}`$.
- **Compare entries:**
  - $`(1,1)`$: $`a+c=a\Rightarrow c=0`$
  - $`(1,2)`$: $`b+d=a+b\Rightarrow d=a`$
  - $`(2,1)`$: $`c=c`$ (always true)
  - $`(2,2)`$: $`d=c+d\Rightarrow c=0`$ (same as before)
- So $`c=0`$, $`d=a`$, with $`a,b`$ free.

**Check:** $`B=\begin{pmatrix}2&5\\0&2\end{pmatrix}`$: $`AB=\begin{pmatrix}2&7\\0&2\end{pmatrix}`$ and $`BA=\begin{pmatrix}2&7\\0&2\end{pmatrix}`$ ✓.

---
