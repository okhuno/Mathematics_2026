### Exercise 3. Swapping Two Rows
For

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 3 & 1 \\
2 & 1 & 1 \\
\end{pmatrix}
$$

compute $\det A$. Then form a matrix $B$ by swapping the first and second rows of $A$.

First predict $\det B$ using a determinant property, and then verify your prediction by calculation.

> **Why this exercise:** gives a second classical calculation with a $3\times3$ determinant while teaching the precise effect of a row swap on the sign of the determinant.

#### Answer
$\det A=6$, predicted $\det B=-6$, verified $\det B=-6$.

#### How I solved it
- **$\det A$** (Sarrus): down-right: $1\cdot3\cdot1+2\cdot1\cdot2+0\cdot0\cdot1=3+4+0=7$. Up-right: $0\cdot3\cdot2+1\cdot1\cdot1+2\cdot0\cdot1=0+1+0=1$. $\det A=7-1=6$.
- **Prediction:** swapping two rows flips the sign, so $\det B=-6$.
- **Verification:** $B=\begin{pmatrix}0&3&1\\1&2&0\\2&1&1\end{pmatrix}$. Down-right: $0\cdot2\cdot1+3\cdot0\cdot2+1\cdot1\cdot1=1$. Up-right: $1\cdot2\cdot2+0\cdot0\cdot1+3\cdot1\cdot1=4+0+3=7$. $\det B=1-7=-6$ ✓.

---
