### Exercise 8. Row Operations and Their Reversibility
For

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
2 & 4 & 1 \\
-1 & 1 & 3 \\
\end{pmatrix}
$$

perform, in order:

1. $R_2\leftarrow R_2-2R_1$,
2. $R_3\leftarrow R_3+R_1$,
3. interchange $R_2$ and $R_3$.

Write the matrix after each step. Then, for each of the three operations, state an operation that reverses it.

> **Why this exercise:** prepares for elimination by showing that row operations are controlled and reversible transformations of a matrix.

#### Answer
After step 1: $\begin{pmatrix}1&2&-1\\0&0&3\\-1&1&3\end{pmatrix}$

After step 2: $\begin{pmatrix}1&2&-1\\0&0&3\\0&3&2\end{pmatrix}$

After step 3: $\begin{pmatrix}1&2&-1\\0&3&2\\0&0&3\end{pmatrix}$

Reversing operations: (1) $R_2\leftarrow R_2+2R_1$; (2) $R_3\leftarrow R_3-R_1$; (3) interchange $R_2$ and $R_3$ again.

#### How I solved it
1. $R_2-2R_1=(2,4,1)-(2,4,-2)=(0,0,3)$.
2. $R_3+R_1=(-1,1,3)+(1,2,-1)=(0,3,2)$.
3. Swap the second and third rows.

**Reversing:** an operation "subtract $2R_1$ from $R_2$" is undone by "add $2R_1$ to $R_2$"; "add $R_1$ to $R_3$" is undone by "subtract $R_1$ from $R_3$"; a swap is undone by swapping again. To go all the way back, undo in **reverse order**: (3), then (2), then (1).

---
