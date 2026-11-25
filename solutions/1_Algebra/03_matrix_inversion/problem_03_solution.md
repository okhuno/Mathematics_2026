### Exercise 3. When Does the Inverse Not Exist?
For

```math
A=
\begin{pmatrix}
2 & 4 \\
1 & 2 \\
\end{pmatrix}
```

explain in two ways why $`A^{-1}`$ does not exist: using the determinant and using dependence between the rows.

> **Why this exercise:** connects two signs of noninvertibility instead of treating them as unrelated facts.

#### Answer
$`\det A=0`$, and row 1 $`=2\cdot`$ row 2, so $`A`$ is not invertible.

#### How I solved it
- **Determinant:** $`\det A=2\cdot2-4\cdot1=4-4=0`$. The $`2\times2`$ formula divides by $`\det A`$, and we cannot divide by $`0`$.
- **Dependent rows:** $`(2,4)=2\cdot(1,2)`$, so the first row is a multiple of the second. The rows are linearly dependent.

**Connection:** dependent rows mean the matrix squashes the whole plane onto a line: different vectors are sent to the same result. That information cannot be recovered, so no inverse exists. And exactly in this situation the determinant is $`0`$.

---
