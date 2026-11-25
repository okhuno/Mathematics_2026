### Exercise 12. A Parameter Revealed by a Row Operation
For

```math
A(t)=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & t \\
0 & 1 & 1 \\
\end{pmatrix}
```

find the values of $`t`$ for which the matrix is not invertible.

Before computing the determinant, perform the operation

```math
R_2\leftarrow R_2-2R_1
```

and use the resulting structure. At the end, explain what special thing happens to the rows for the value of the parameter you found.

> **Why this exercise:** combines a parameter, row operations, and recognition of dependence in one short argument.

#### Answer
Not invertible only for $`t=6`$. (In general $`\det A(t)=6-t`$.)

#### How I solved it
1. **Row operation:** $`R_2-2R_1=(2-2,\ 4-4,\ t-6)=(0,0,t-6)`$. The determinant is unchanged. The matrix becomes

```math
\begin{pmatrix}1&2&3\\0&0&t-6\\0&1&1\end{pmatrix}.
```

2. **Determinant:** expand along the first column (only the $`1`$ is nonzero): $`1\cdot\det\begin{pmatrix}0&t-6\\1&1\end{pmatrix}=0\cdot1-(t-6)\cdot1=6-t`$.
3. **Not invertible when $`\det=0`$:** $`6-t=0\Rightarrow t=6`$.

**What happens for $`t=6`$:** the original second row is $`(2,4,6)=2\cdot(1,2,3)`$, a multiple of the first row. After the operation it becomes the zero row $`(0,0,0)`$. So the rows are dependent, which is why the matrix is not invertible.

---
