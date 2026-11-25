### Exercise 9. Composing Transformations
Let

```math
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad R=
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix}.
```

The matrix $`S`$ describes nonuniform scaling, while $`R`$ describes a $`90^\circ`$ counterclockwise rotation.
For

```math
x=
\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}
```

compute $`RSx`$ and $`SRx`$. Compare the results and explain geometrically why the order of these transformations matters.

> **Why this exercise:** interprets matrix multiplication as composition of transformations.

#### Answer

```math
RSx=\begin{pmatrix}-2\\2\end{pmatrix},\qquad SRx=\begin{pmatrix}-4\\1\end{pmatrix}
```

The results are different.

#### How I solved it
- **$`RSx`$ (first $`S`$, then $`R`$):** $`Sx=\begin{pmatrix}2\cdot1\\1\cdot2\end{pmatrix}=\begin{pmatrix}2\\2\end{pmatrix}`$. Then $`R\begin{pmatrix}2\\2\end{pmatrix}=\begin{pmatrix}0\cdot2-1\cdot2\\1\cdot2+0\cdot2\end{pmatrix}=\begin{pmatrix}-2\\2\end{pmatrix}`$.
- **$`SRx`$ (first $`R`$, then $`S`$):** $`Rx=\begin{pmatrix}0\cdot1-1\cdot2\\1\cdot1+0\cdot2\end{pmatrix}=\begin{pmatrix}-2\\1\end{pmatrix}`$. Then $`S\begin{pmatrix}-2\\1\end{pmatrix}=\begin{pmatrix}-4\\1\end{pmatrix}`$.

(In $`RSx`$ the matrix closest to $`x`$ acts first.)

**Geometric reason:** $`S`$ stretches only in the $`x`$ direction. If we stretch first, the vector is stretched along the original $`x`$-axis and then rotated. If we rotate first, the stretching afterward acts on a rotated vector, along the same $`x`$-axis but on a different part of the vector. Different directions get stretched, so the result differs.

---
