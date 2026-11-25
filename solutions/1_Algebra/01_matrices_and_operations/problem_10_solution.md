### Exercise 10. Columns of a Matrix Product
Given

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & 2 \\
-1 & 0 \\
3 & 1 \\
\end{pmatrix}.
$$

Denote the columns of $B$ by $b_1,b_2$.

1. Compute $Ab_1$ and $Ab_2$.
2. Compute the matrix $AB$.
3. Compare the results and explain why the columns of $AB$ are exactly the vectors $Ab_1$ and $Ab_2$.

> **Why this exercise:** extends the interpretation of matrix-vector multiplication to a full product of two matrices instead of simply repeating another $Ax$ exercise.

#### Answer
1. $Ab_1=\begin{pmatrix}-1\\2\end{pmatrix}$, $\ Ab_2=\begin{pmatrix}2\\1\end{pmatrix}$.
2. $AB=\begin{pmatrix}-1&2\\2&1\end{pmatrix}$.
3. The columns of $AB$ are exactly $Ab_1$ and $Ab_2$.

#### How I solved it
1. $b_1=(1,-1,3)^T$ and $b_2=(2,0,1)^T$.
   - $Ab_1=\begin{pmatrix}1\cdot1+2\cdot(-1)+0\cdot3\\0\cdot1+1\cdot(-1)+1\cdot3\end{pmatrix}=\begin{pmatrix}-1\\2\end{pmatrix}$
   - $Ab_2=\begin{pmatrix}1\cdot2+2\cdot0+0\cdot1\\0\cdot2+1\cdot0+1\cdot1\end{pmatrix}=\begin{pmatrix}2\\1\end{pmatrix}$
2. $AB$ ($2\times3$ times $3\times2$ gives $2\times2$) entry by entry:
   - $(1,1)$: $1-2+0=-1$; $(1,2)$: $2+0+0=2$
   - $(2,1)$: $0-1+3=2$; $(2,2)$: $0+0+1=1$
3. **Comparison:** the first column of $AB$ is $(-1,2)^T=Ab_1$ and the second is $(2,1)^T=Ab_2$ ✓.

**Why:** the entry in row $i$, column $j$ of $AB$ uses row $i$ of $A$ and **only column $j$ of $B$**. That is exactly the $i$-th entry of $Ab_j$. So column $j$ of $AB$ is $Ab_j$: multiplying by $A$ acts on each column of $B$ separately.

---

## More Challenging Exercises
