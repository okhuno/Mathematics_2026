### Exercise 15. Associativity of Multiplication and Different Calculation Paths
Given

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\quad B=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix},\quad C=
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix}.
$$

Compute $(AB)C$ and $A(BC)$. Compare the results and the number of intermediate operations. Explain what associativity of matrix multiplication means in this example.

> **Why this exercise:** reinforces associativity by comparing two mathematically equivalent calculation paths.

#### Answer
$$(AB)C=A(BC)=\begin{pmatrix}10&3\\2&-3\end{pmatrix}$$

#### How I solved it
**Path 1: $(AB)C$.**
- $AB=\begin{pmatrix}1+4+0&0+2+0\\0+2-1&0+1+3\end{pmatrix}=\begin{pmatrix}5&2\\1&4\end{pmatrix}$ ($2\times2$).
- $(AB)C=\begin{pmatrix}5\cdot2+2\cdot0&5\cdot1+2\cdot(-1)\\1\cdot2+4\cdot0&1\cdot1+4\cdot(-1)\end{pmatrix}=\begin{pmatrix}10&3\\2&-3\end{pmatrix}$.

**Path 2: $A(BC)$.**
- $BC=\begin{pmatrix}1\cdot2+0&1\cdot1+0\\2\cdot2+1\cdot0&2\cdot1+1\cdot(-1)\\-1\cdot2+3\cdot0&-1\cdot1+3\cdot(-1)\end{pmatrix}=\begin{pmatrix}2&1\\4&1\\-2&-4\end{pmatrix}$ ($3\times2$).
- $A(BC)=\begin{pmatrix}1\cdot2+2\cdot4+0&1\cdot1+2\cdot1+0\\0\cdot2+1\cdot4+1\cdot(-2)&0\cdot1+1\cdot1+1\cdot(-4)\end{pmatrix}=\begin{pmatrix}10&3\\2&-3\end{pmatrix}$.

**Compare:** both give the same matrix ✓.

**Number of multiplications** (an $m\times n$ times $n\times p$ product needs $m\cdot n\cdot p$ multiplications):
- Path 1: $AB$: $2\cdot3\cdot2=12$; $(AB)C$: $2\cdot2\cdot2=8$. Total $20$.
- Path 2: $BC$: $3\cdot2\cdot2=12$; $A(BC)$: $2\cdot3\cdot2=12$. Total $24$.

So path 1 is a bit cheaper here.

**Meaning of associativity:** we may group the factors in any way, $(AB)C=A(BC)$, and the result is the same. What we may **not** do is change the order of the matrices (noncommutativity). Different groupings are different calculation paths to the same answer, but with different amounts of work.
