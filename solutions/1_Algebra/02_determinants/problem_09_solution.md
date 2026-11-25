### Exercise 9. Area and the Determinant
The vectors

```math
u=
\begin{pmatrix}
3 \\
1 \\
\end{pmatrix},\qquad v=
\begin{pmatrix}
1 \\
4 \\
\end{pmatrix}
```

span a parallelogram. Compute its area using a determinant. Then reverse the order of the vectors and explain what changes in the determinant and what does not change in the area.

> **Why this exercise:** gives the determinant a geometric interpretation and distinguishes its sign from the value of the area.

#### Answer
- $`\det[u\ v]=11`$, so the area is $`11`$.
- Reversed order: $`\det[v\ u]=-11`$, but the area is still $`11`$.

#### How I solved it
- Put the vectors as columns: $`\det\begin{pmatrix}3&1\\1&4\end{pmatrix}=3\cdot4-1\cdot1=11`$. Area $`=|11|=11`$.
- Reverse the order: $`\det\begin{pmatrix}1&3\\4&1\end{pmatrix}=1\cdot1-3\cdot4=-11`$. Area $`=|-11|=11`$.

**What changes / what stays:** swapping the order is a column swap, which flips the **sign** of the determinant. The sign tells the orientation (whether going from the first vector to the second turns counterclockwise or clockwise). The **area** is the absolute value, and the parallelogram is the same shape, so it does not change.

---
