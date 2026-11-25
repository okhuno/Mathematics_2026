Exercise 1. Matrix Size and Entries
Given

$$
A=
\begin{pmatrix}
2 & -1 & 3 \\
0 & 4 & 5 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & 0 \\
-2 & 3 \\
4 & 1 \\
\end{pmatrix}.
$$

1. State the sizes of matrices $A$ and $B$.
2. Read off the entries $a_{12}$, $a_{23}$, $b_{21}$, and $b_{32}$.
3. Write the second row of $A$ and the first column of $B$ as vectors.

> **Why this exercise:** builds basic fluency with matrix notation, indices, rows, and columns.

#### Answer
1. $A$ is $2\times3$; $B$ is $3\times2$.
2. $a_{12}=-1$, $a_{23}=5$, $b_{21}=-2$, $b_{32}=1$.
3. Second row of $A$: $(0,\ 4,\ 5)$. First column of $B$: $(1,\ -2,\ 4)^T$.

#### How I solved it
- **Size:** count rows × columns. $A$ has 2 rows and 3 columns; $B$ has 3 rows and 2 columns.
- **Entries:** $a_{ij}$ is in row $i$, column $j$. $a_{12}$: row 1, column 2 $=-1$. $a_{23}$: row 2, column 3 $=5$. $b_{21}$: row 2, column 1 $=-2$. $b_{32}$: row 3, column 2 $=1$.
- **Row / column:** read the second row of $A$ left to right; read the first column of $B$ top to bottom.

