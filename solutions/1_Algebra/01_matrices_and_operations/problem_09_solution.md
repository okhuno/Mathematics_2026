### Exercise 9. Composing Transformations

Let

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1
\end{pmatrix},
\qquad
R=
\begin{pmatrix}
0 & -1 \\
1 & 0
\end{pmatrix}.
$$

The matrix $S$ describes nonuniform scaling, while $R$ describes a $90^\circ$ counterclockwise rotation.

For

$$
x=
\begin{pmatrix}
1 \\
2
\end{pmatrix}
$$

compute $RSx$ and $SRx$. Compare the results and explain geometrically why the order of these transformations matters.

> **Why this exercise:** Interprets matrix multiplication as composition of transformations.

#### Answer

$$
RSx=
\begin{pmatrix}
-2 \\
2
\end{pmatrix},
\qquad
SRx=
\begin{pmatrix}
-4 \\
1
\end{pmatrix}.
$$

The results are different.

How I solved it

1. $RSx$ (first $S$, then $R$)

First, apply the scaling transformation:

\begin{pmatrix}
2 \
2
\end{pmatrix}
$$

Then, apply the rotation:

\begin{pmatrix}
-2 \
2
\end{pmatrix}
$$

2. $SRx$ (first $R$, then $S$)

First, apply the rotation:

\begin{pmatrix}
-2 \
1
\end{pmatrix}
$$

Then, apply the scaling transformation:

\begin{pmatrix}
-4 \
1
\end{pmatrix}
$$

In $RSx$, the matrix closest to $x$ acts first.

Geometric reason:

The transformation $S$ stretches vectors horizontally while leaving their vertical components unchanged.

If scaling is performed first, the vector is stretched along the original $x$-axis and then rotated.

If rotation is performed first, the vector is rotated and then stretched horizontally in its new position.

Consequently, the two compositions produce different vectors. Matrix multiplication is therefore not commutative in general:

$$
RS\neq SR
$$
