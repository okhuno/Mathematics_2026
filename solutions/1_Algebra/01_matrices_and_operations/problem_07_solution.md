### Exercise 7. Identity Matrix, Zero Matrix, and Powers
For

$$
A=
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}
$$

compute

$$
AI,\qquad IA,\qquad A+0,\qquad A^2,\qquad A^3.
$$

Explain the roles of the matrices $I$ and $0$, and describe the pattern you observe in successive powers of $A$.

> **Why this exercise:** organizes the roles of neutral elements and reveals regularity in successive powers of a matrix.

#### Answer

- $AI=IA=A+0=A$

  $$
  A=
  \begin{pmatrix}
  2 & 1 \\
  0 & 2
  \end{pmatrix}
  $$

- $A^2$

  $$
  A^2=
  \begin{pmatrix}
  4 & 4 \\
  0 & 4
  \end{pmatrix}
  $$

- $A^3$

  $$
  A^3=
  \begin{pmatrix}
  8 & 12 \\
  0 & 8
  \end{pmatrix}
  $$

  
#### How I solved it
- **$AI$ and $IA$:** multiplying by the identity leaves the matrix unchanged. **$A+0$:** adding the zero matrix leaves it unchanged.
- **$A^2=A\cdot A$:**
  - $(1,1)$: $2\cdot2+1\cdot0=4$; $(1,2)$: $2\cdot1+1\cdot2=4$
  - $(2,1)$: $0$; $(2,2)$: $0\cdot1+2\cdot2=4$
- **$A^3=A^2\cdot A$:**
  - $(1,1)$: $4\cdot2+4\cdot0=8$; $(1,2)$: $4\cdot1+4\cdot2=12$
  - $(2,1)$: $0$; $(2,2)$: $4\cdot2=8$

**Roles:** $I$ is the "1" of matrices (neutral for multiplication) and $0$ is the "0" of matrices (neutral for addition).

**Pattern:** the diagonal entries are $2^n$ ($2,4,8$), and the top-right entry is $1,\ 4,\ 12$, which equals $n\cdot2^{n-1}$ ($1\cdot1$, $2\cdot2$, $3\cdot4$). Check: $n=2$: $2\cdot2=4$ ✓; $n=3$: $3\cdot4=12$ ✓.

---
