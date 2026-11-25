### Exercise 10. Detecting Dependence
Without carrying out a full determinant calculation, explain why

```math
\det
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & 6 \\
0 & 1 & 5 \\
\end{pmatrix}=0.
```

Identify a specific dependence between the rows and connect it with noninvertibility of the matrix.

> **Why this exercise:** teaches how to recognize a zero determinant from the structure of a matrix.

#### Answer
Row 2 $`=2\cdot`$ Row 1, so the determinant is $`0`$ and the matrix is not invertible.

#### How I solved it
- **Spot the dependence:** $`(2,4,6)=2\cdot(1,2,3)`$. The second row is twice the first.
- **Why $`\det=0`$:** doing $`R_2\leftarrow R_2-2R_1`$ does not change the determinant, but it creates a row of zeros $`(0,0,0)`$, and a matrix with a zero row has determinant $`0`$.
- **Noninvertibility:** $`\det=0`$ means the matrix is not invertible. Dependent rows mean the matrix collapses 3D space onto something flatter, which cannot be undone.

---
