### Exercise 12. Formula for a Matrix Power
Let

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}.
$$

Compute $A^2$, $A^3$, and $A^4$, and use them to formulate a conjecture for $A^n$. Then do not stop after checking one more case: assume the formula is true for $n$, multiply by $A$, and explain why you obtain exactly the formula for $n+1$.

> **Why this exercise:** teaches how to recognize a pattern and formulate a generalization from several computations.

#### Answer
$$A^2=\begin{pmatrix}1&2\\0&1\end{pmatrix},\ A^3=\begin{pmatrix}1&3\\0&1\end{pmatrix},\ A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix},\qquad A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}.$$

#### How I solved it
- $A^2=A\cdot A=\begin{pmatrix}1\cdot1+1\cdot0&1\cdot1+1\cdot1\\0&1\end{pmatrix}=\begin{pmatrix}1&2\\0&1\end{pmatrix}$.
- $A^3=A^2A=\begin{pmatrix}1&1+2\\0&1\end{pmatrix}=\begin{pmatrix}1&3\\0&1\end{pmatrix}$, and likewise $A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix}$.
- **Conjecture:** the top-right entry equals the exponent: $A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}$.

**Why it works for every $n$ (induction step):** suppose $A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}$. Then
$$A^{n+1}=A^nA=\begin{pmatrix}1&n\\0&1\end{pmatrix}\begin{pmatrix}1&1\\0&1\end{pmatrix}=\begin{pmatrix}1\cdot1+n\cdot0&1\cdot1+n\cdot1\\0&1\end{pmatrix}=\begin{pmatrix}1&n+1\\0&1\end{pmatrix}.$$
This is exactly the formula with $n$ replaced by $n+1$. Since it holds for $n=1$ and passes from each $n$ to the next, it holds for all $n$. This is a proof, not just a pattern.

---
