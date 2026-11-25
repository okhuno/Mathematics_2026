### Exercise 14. A Matrix That Is Its Own Inverse
Assume that a square matrix $`A`$ satisfies

```math
A^2=I.
```

Show that

```math
A^{-1}=A.
```

Then give an example of a $`2\times2`$ matrix different from $`I`$ and $`-I`$ that satisfies this condition, and verify it by multiplication.

> **Why this exercise:** requires using the definition of the inverse in a short argument and constructing an example independently, without introducing a new topic.

#### Answer
- Proof: $`A\cdot A=I`$ means $`A`$ satisfies the definition of the inverse of itself.
- Example: $`A=\begin{pmatrix}0&1\\1&0\end{pmatrix}`$.

#### How I solved it
**Proof:** by definition, $`B`$ is the inverse of $`A`$ if $`AB=BA=I`$. Take $`B=A`$. Then $`AB=A\cdot A=A^2=I`$ and $`BA=A\cdot A=I`$. Both conditions hold, so $`A`$ is its own inverse: $`A^{-1}=A`$.

**Example:** $`A=\begin{pmatrix}0&1\\1&0\end{pmatrix}`$ swaps the two coordinates.

```math
A^2=\begin{pmatrix}0\cdot0+1\cdot1&0\cdot1+1\cdot0\\1\cdot0+0\cdot1&1\cdot1+0\cdot0\end{pmatrix}=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I\ ✓
```

It is different from $`I`$ and $`-I`$. (Geometrically: swapping the coordinates twice returns every vector to where it started.) Another example: $`\begin{pmatrix}1&0\\0&-1\end{pmatrix}`$ (a reflection).

---
