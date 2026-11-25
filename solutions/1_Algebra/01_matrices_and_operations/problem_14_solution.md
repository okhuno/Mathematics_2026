### Exercise 14. Rotation Matrices
The matrix for a rotation through an angle $`\theta`$ is

```math
R(\theta)=
\begin{pmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta \\
\end{pmatrix}.
```

Compute $`R(\alpha)R(\beta)`$ and, using the angle-sum formulas for sine and cosine, show that

```math
R(\alpha)R(\beta)=R(\alpha+\beta).
```

Explain the result geometrically.

> **Why this exercise:** shows the consistency between matrix algebra and the geometry of composing rotations.

#### Answer

```math
R(\alpha)R(\beta)=R(\alpha+\beta)
```

#### How I solved it

```math
R(\alpha)R(\beta)=\begin{pmatrix}\cos\alpha\cos\beta-\sin\alpha\sin\beta&-\cos\alpha\sin\beta-\sin\alpha\cos\beta\\\sin\alpha\cos\beta+\cos\alpha\sin\beta&-\sin\alpha\sin\beta+\cos\alpha\cos\beta\end{pmatrix}.
```

Use the angle-sum formulas:
- $`\cos(\alpha+\beta)=\cos\alpha\cos\beta-\sin\alpha\sin\beta`$
- $`\sin(\alpha+\beta)=\sin\alpha\cos\beta+\cos\alpha\sin\beta`$

So the entries become:
- $`(1,1)`$ and $`(2,2)`$: $`\cos(\alpha+\beta)`$
- $`(2,1)`$: $`\sin(\alpha+\beta)`$
- $`(1,2)`$: $`-(\cos\alpha\sin\beta+\sin\alpha\cos\beta)=-\sin(\alpha+\beta)`$

```math
R(\alpha)R(\beta)=\begin{pmatrix}\cos(\alpha+\beta)&-\sin(\alpha+\beta)\\\sin(\alpha+\beta)&\cos(\alpha+\beta)\end{pmatrix}=R(\alpha+\beta)\ ✓
```

**Geometric meaning:** rotating by $`\beta`$ and then by $`\alpha`$ is the same as one rotation by $`\alpha+\beta`$. The matrix algebra agrees with what we expect from geometry. (As a bonus, rotations in the plane commute: $`R(\alpha)R(\beta)=R(\beta)R(\alpha)`$, because $`\alpha+\beta=\beta+\alpha`$.)

---
