### Exercise 15. Two Methods for Solving the Same System
For

```math
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
7 \\
8 \\
\end{pmatrix}
```

solve $`Ax=b`$ in two ways:

1. using $`A^{-1}b`$,
2. using Gaussian elimination.

Compare both solutions, the number of essential steps, and state which method was simpler in this example.

> **Why this exercise:** compares two known methods and prepares the student to choose a solution method consciously.

#### Answer

```math
x=\begin{pmatrix}\frac{13}5\\[2pt]\frac95\end{pmatrix}
```

(the same by both methods). For a single system, Gaussian elimination is simpler.

#### How I solved it
**Method 1: inverse.**
- $`\det A=6-1=5`$, so $`A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix}`$.
- $`x=A^{-1}b=\frac15\begin{pmatrix}3\cdot7-1\cdot8\\-1\cdot7+2\cdot8\end{pmatrix}=\frac15\begin{pmatrix}13\\9\end{pmatrix}`$.

**Method 2: Gaussian elimination.**

```math
\left(\begin{array}{cc|c}2&1&7\\1&3&8\end{array}\right)\xrightarrow{R_1\leftrightarrow R_2}\left(\begin{array}{cc|c}1&3&8\\2&1&7\end{array}\right)\xrightarrow{R_2\leftarrow R_2-2R_1}\left(\begin{array}{cc|c}1&3&8\\0&-5&-9\end{array}\right)
```

- $`-5y=-9\Rightarrow y=\frac95`$.
- $`x=8-3y=8-\frac{27}5=\frac{13}5`$.

**Check:** $`2\cdot\frac{13}5+\frac95=\frac{35}5=7`$ ✓ and $`\frac{13}5+3\cdot\frac95=\frac{40}5=8`$ ✓.

**Comparison:** both give $`\left(\frac{13}5,\frac95\right)`$. Counting steps: the inverse method needs the determinant, building the inverse (4 entries), then a matrix–vector multiplication. Elimination needs one swap, one row operation, and back substitution. So for **one** right-hand side, elimination is simpler. The inverse pays off when the same $`A`$ is used with many different $`b`$'s.
