### Exercise 10. Continuity of a Piecewise Function
Find $`a`$ so that

```math
f(x)=
\begin{cases}
ax+1,&x<2, \\
x^2-1,&x\ge2
\end{cases}
```

is continuous at $`x=2`$. Explicitly compare the left-hand limit, right-hand limit, and function value.

> **Why this exercise:** organizes the definition of continuity as agreement among three quantities.

#### Answer

```math
a=1
```

#### How I solved it
Continuity at $`2`$ needs: left limit = right limit = $`f(2)`$.
- **Left-hand limit:** $`\lim_{x\to2^-}(ax+1)=2a+1`$.
- **Right-hand limit:** $`\lim_{x\to2^+}(x^2-1)=3`$.
- **Function value:** $`f(2)=2^2-1=3`$.

Set the left limit equal to the others: $`2a+1=3\Rightarrow a=1`$.

**Check with $`a=1`$:** left limit $`=3`$, right limit $`=3`$, $`f(2)=3`$ ✓.

---
