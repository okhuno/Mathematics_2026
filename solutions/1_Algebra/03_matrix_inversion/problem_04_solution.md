### Exercise 4. Gauss–Jordan
Find $`A^{-1}`$ using the Gauss–Jordan method for

```math
A=
\begin{pmatrix}
1 & 2 \\
3 & 5 \\
\end{pmatrix}.
```

Show the augmented matrix $`[A\mid I]`$ after successive operations and explain why obtaining $`I`$ on the left gives the inverse on the right.

> **Why this exercise:** introduces the Gauss–Jordan method together with its meaning, not merely as a sequence of operations.

#### Answer

```math
A^{-1}=\begin{pmatrix}-5&2\\3&-1\end{pmatrix}
```

#### How I solved it

```math
\left(\begin{array}{cc|cc}1&2&1&0\\3&5&0&1\end{array}\right)
```

1. $`R_2\leftarrow R_2-3R_1`$:

```math
\left(\begin{array}{cc|cc}1&2&1&0\\0&-1&-3&1\end{array}\right)
```

2. $`R_2\leftarrow-R_2`$:

```math
\left(\begin{array}{cc|cc}1&2&1&0\\0&1&3&-1\end{array}\right)
```

3. $`R_1\leftarrow R_1-2R_2`$:

```math
\left(\begin{array}{cc|cc}1&0&-5&2\\0&1&3&-1\end{array}\right)
```

The left side is $`I`$, so the right side is $`A^{-1}=\begin{pmatrix}-5&2\\3&-1\end{pmatrix}`$.

**Check:** formula gives $`\frac1{5-6}\begin{pmatrix}5&-2\\-3&1\end{pmatrix}=\begin{pmatrix}-5&2\\3&-1\end{pmatrix}`$ ✓.

**Why it works:** every row operation is the same as multiplying on the left by some matrix $`E`$. After all operations, $`E\cdot A=I`$ (left side) and $`E\cdot I=E`$ (right side). Since $`EA=I`$, $`E`$ is exactly $`A^{-1}`$, and that is what appears on the right.

---
