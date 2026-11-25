Answer
$$A+B=\begin{pmatrix}5&0\\-1&8\end{pmatrix},\quad A-B=\begin{pmatrix}-3&4\\-1&-2\end{pmatrix},\quad 3A-2B=\begin{pmatrix}-5&10\\-3&-1\end{pmatrix}$$

#### How I solved it
- $A+B$: add matching entries: $(1+4,\ 2-2;\ -1+0,\ 3+5)$.
- $A-B$: subtract matching entries: $(1-4,\ 2+2;\ -1-0,\ 3-5)$.
- $3A=\begin{pmatrix}3&6\\-3&9\end{pmatrix}$ and $2B=\begin{pmatrix}8&-4\\0&10\end{pmatrix}$, so $3A-2B=\begin{pmatrix}3-8&6+4\\-3-0&9-10\end{pmatrix}$.

**Why same size is needed:** the operation works position by position. Every entry of $A$ must have a partner entry in $B$ at the same position. If the sizes differ, some entries would have no partner.
