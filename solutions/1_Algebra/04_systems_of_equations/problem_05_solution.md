### Exercise 5. Row Echelon Form and Number of Solutions
For the augmented matrix

```math
\begin{pmatrix}
1 & 2 & -1 & \mid & 3 \\
0 & 1 & 2 & \mid & 1 \\
0 & 0 & 0 & \mid & 0 \\
\end{pmatrix}
```

determine the number of solutions and write them in parametric form. Explain how you know how many variables may be chosen freely.

> **Why this exercise:** teaches how to read information about solutions directly from row echelon form.

#### Answer
Infinitely many solutions:

```math
(x,y,z)=(1+5t,\ 1-2t,\ t),\quad t\in\mathbb R.
```

#### How I solved it
- The last row is $`0=0`$: harmless (no contradiction), so the system is consistent.
- There are **2 pivots** (in columns 1 and 2) and **3 unknowns**, so $`3-2=1`$ free variable. The column without a pivot is the third, so $`z=t`$ is free.
- **Back substitution:** second row: $`y+2z=1\Rightarrow y=1-2t`$. First row: $`x+2y-z=3\Rightarrow x=3-2(1-2t)+t=1+5t`$.

**How many free variables:** (number of unknowns) − (number of pivots) $`=3-2=1`$.

**Check ($`t=0`$):** $`(1,1,0)`$: $`1+2-0=3`$ ✓ and $`1+0=1`$ ✓.

---
