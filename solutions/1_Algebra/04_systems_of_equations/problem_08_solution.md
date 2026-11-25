### Exercise 8. Two Systems with the Same Coefficient Matrix
Solve by elimination the two systems

```math
\begin{cases}
2x+y=5, \\
x-y=1,
\end{cases}
```

```math
\begin{cases}
2x+y=1, \\
x-y=4.
\end{cases}
```

Compare the successive elimination steps. Which part of the calculation is the same in both cases, and why?

> **Why this exercise:** shows the role of the coefficient matrix independently of the right-hand side.

#### Answer
- System 1: $`(x,y)=(2,\ 1)`$.
- System 2: $`(x,y)=\left(\frac53,\ -\frac73\right)`$.

#### How I solved it
**System 1:**

```math
\left(\begin{array}{cc|c}2&1&5\\1&-1&1\end{array}\right)\xrightarrow{R_1\leftrightarrow R_2}\left(\begin{array}{cc|c}1&-1&1\\2&1&5\end{array}\right)\xrightarrow{R_2\leftarrow R_2-2R_1}\left(\begin{array}{cc|c}1&-1&1\\0&3&3\end{array}\right)
```

$`3y=3\Rightarrow y=1`$, then $`x=1+y=2`$.

**System 2:**

```math
\left(\begin{array}{cc|c}2&1&1\\1&-1&4\end{array}\right)\xrightarrow{R_1\leftrightarrow R_2}\left(\begin{array}{cc|c}1&-1&4\\2&1&1\end{array}\right)\xrightarrow{R_2\leftarrow R_2-2R_1}\left(\begin{array}{cc|c}1&-1&4\\0&3&-7\end{array}\right)
```

$`3y=-7\Rightarrow y=-\frac73`$, then $`x=4+y=\frac53`$.

**Check:** system 2: $`2\cdot\frac53-\frac73=1`$ ✓ and $`\frac53+\frac73=4`$ ✓.

**What is the same:** the row operations (swap, then $`R_2-2R_1`$) are identical, and so is the left part of the matrix after elimination. They are decided only by the coefficient matrix. Only the right-hand column differs. So if many systems share a matrix, the elimination can be done once for all of them.

---
