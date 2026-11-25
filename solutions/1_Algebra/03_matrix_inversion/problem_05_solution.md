### Exercise 5. A 3×3 Matrix
Use Gauss–Jordan elimination to find the inverse of

```math
A=
\begin{pmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
\end{pmatrix}.
```

Check the result by multiplication.

> **Why this exercise:** provides necessary practice with the full method in a situation where the $`2\times2`$ formula no longer applies.

#### Answer

```math
A^{-1}=\frac12\begin{pmatrix}1&-1&1\\1&1&-1\\-1&1&1\end{pmatrix}
```

#### How I solved it

```math
\left(\begin{array}{ccc|ccc}1&1&0&1&0&0\\0&1&1&0&1&0\\1&0&1&0&0&1\end{array}\right)
```

1. $`R_3\leftarrow R_3-R_1`$:

```math
\left(\begin{array}{ccc|ccc}1&1&0&1&0&0\\0&1&1&0&1&0\\0&-1&1&-1&0&1\end{array}\right)
```

2. $`R_3\leftarrow R_3+R_2`$:

```math
\left(\begin{array}{ccc|ccc}1&1&0&1&0&0\\0&1&1&0&1&0\\0&0&2&-1&1&1\end{array}\right)
```

3. $`R_3\leftarrow\frac12R_3`$:

```math
\left(\begin{array}{ccc|ccc}1&1&0&1&0&0\\0&1&1&0&1&0\\0&0&1&-\frac12&\frac12&\frac12\end{array}\right)
```

4. $`R_2\leftarrow R_2-R_3`$:

```math
\left(\begin{array}{ccc|ccc}1&1&0&1&0&0\\0&1&0&\frac12&\frac12&-\frac12\\0&0&1&-\frac12&\frac12&\frac12\end{array}\right)
```

5. $`R_1\leftarrow R_1-R_2`$:

```math
\left(\begin{array}{ccc|ccc}1&0&0&\frac12&-\frac12&\frac12\\0&1&0&\frac12&\frac12&-\frac12\\0&0&1&-\frac12&\frac12&\frac12\end{array}\right)
```

**Check ($`AA^{-1}`$):** with $`A^{-1}=\frac12\begin{pmatrix}1&-1&1\\1&1&-1\\-1&1&1\end{pmatrix}`$:
- row 1 of $`A`$ $`(1,1,0)`$: $`\frac12(1+1,\ -1+1,\ 1-1)=(1,0,0)`$ ✓
- row 2 of $`A`$ $`(0,1,1)`$: $`\frac12(1-1,\ 1+1,\ -1+1)=(0,1,0)`$ ✓
- row 3 of $`A`$ $`(1,0,1)`$: $`\frac12(1-1,\ -1+1,\ 1+1)=(0,0,1)`$ ✓

So $`AA^{-1}=I`$.

---
