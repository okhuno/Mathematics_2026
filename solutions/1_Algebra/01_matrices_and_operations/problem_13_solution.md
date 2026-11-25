### Exercise 13. A Recurrence Written in Matrix Form
Let

$$
F=
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}.
$$

Compute $F^2$, $F^3$, $F^4$, and $F^5$. Compare the numbers obtained with the sequence

$$
0,1,1,2,3,5,8,\ldots
$$

and describe the relationship you observe. Then compute

$$
F
\begin{pmatrix}
a \\
b \\
\end{pmatrix}
$$

and explain how this multiplication performs one recurrence step: it creates the sum of two consecutive terms and keeps one of them for the next step.

> **Why this exercise:** shows the connection between matrix powers and a simple numerical recurrence.

#### Answer
$$F^2=\begin{pmatrix}2&1\\1&1\end{pmatrix},\ F^3=\begin{pmatrix}3&2\\2&1\end{pmatrix},\ F^4=\begin{pmatrix}5&3\\3&2\end{pmatrix},\ F^5=\begin{pmatrix}8&5\\5&3\end{pmatrix}$$
$$F\begin{pmatrix}a\\b\end{pmatrix}=\begin{pmatrix}a+b\\a\end{pmatrix}$$

#### How I solved it
- Multiply step by step: $F^2=F\cdot F$, $F^3=F^2F$, etc. For example $F^3=\begin{pmatrix}2&1\\1&1\end{pmatrix}\begin{pmatrix}1&1\\1&0\end{pmatrix}=\begin{pmatrix}3&2\\2&1\end{pmatrix}$.
- **Relationship:** the entries are Fibonacci numbers. With $F_0=0,F_1=1,F_2=1,F_3=2,F_4=3,F_5=5,F_6=8$:
$$F^n=\begin{pmatrix}F_{n+1}&F_n\\F_n&F_{n-1}\end{pmatrix}.$$
For example $F^5=\begin{pmatrix}F_6&F_5\\F_5&F_4\end{pmatrix}=\begin{pmatrix}8&5\\5&3\end{pmatrix}$ ✓.
- **One recurrence step:** $F\begin{pmatrix}a\\b\end{pmatrix}=\begin{pmatrix}1\cdot a+1\cdot b\\1\cdot a+0\cdot b\end{pmatrix}=\begin{pmatrix}a+b\\a\end{pmatrix}$.

If $(a,b)$ are two consecutive terms (the newer first), then the top entry $a+b$ is the next term (sum of the last two), and the bottom entry keeps $a$ for the next step. Starting from $(1,0)^T$: $(1,1)$, $(2,1)$, $(3,2)$, $(5,3)$, ... walks along the Fibonacci sequence.

---
