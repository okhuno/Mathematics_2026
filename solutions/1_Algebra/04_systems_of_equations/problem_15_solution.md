### Exercise 15. Classifying Three Systems
For each of the following systems, perform only as much elimination as necessary to recognize its type:

**System 1**

```math
\begin{cases}
x+y=2, \\
x-y=0,
\end{cases}
```

**System 2**

```math
\begin{cases}
x+y=2, \\
2x+2y=4,
\end{cases}
```

**System 3**

```math
\begin{cases}
x+y=2, \\
2x+2y=5.
\end{cases}
```

For each, justify the classification: one solution, infinitely many solutions, or no solution.

> **Why this exercise:** brings together the three basic cases and requires recognizing them from the structure after elimination.

#### Answer
- System 1: **one solution**, $`(1,1)`$.
- System 2: **infinitely many** solutions, $`(2-t,\ t)`$.
- System 3: **no solution**.

#### How I solved it
- **System 1:** $`R_2\leftarrow R_2-R_1`$ gives $`-2y=-2`$, so $`y=1`$ and $`x=1`$. Two pivots for two unknowns: unique solution.
- **System 2:** $`R_2\leftarrow R_2-2R_1`$ gives $`0=0`$. Only one real equation $`x+y=2`$ with two unknowns: a free variable, infinitely many solutions.
- **System 3:** $`R_2\leftarrow R_2-2R_1`$ gives $`0=1`$. Contradiction: no solution.

**Geometric picture:** System 1: two lines cross at one point. System 2: two equal lines (the same line). System 3: two parallel lines that never meet.
