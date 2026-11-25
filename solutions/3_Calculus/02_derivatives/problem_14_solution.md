### Problem 14. Continuity and Differentiability of a Piecewise Function
Investigate the behavior at $`x=0`$ of

```math
f(x)=
\begin{cases}
x^2,&x\ge0, \\
ax,&x<0.
\end{cases}
```

For which values of $`a`$ is the function continuous? For which values do the one-sided derivatives exist and agree? For which value of $`a`$ is the function differentiable? Explain why continuity alone is not sufficient.

> **Why this problem:** it requires an organized argument and a clear distinction between two concepts.

#### Answer
- Continuous at $`0`$ for **every** $`a`$.
- One-sided derivatives exist for every $`a`$: right derivative $`=0`$, left derivative $`=a`$. They agree only for $`a=0`$.
- Differentiable at $`0`$ only for $`a=0`$.

#### How I solved it
1. **Continuity:** left limit $`=\lim_{x\to0^-}ax=0`$; right limit $`=\lim_{x\to0^+}x^2=0`$; value $`f(0)=0`$. All three agree for any $`a`$, so $`f`$ is continuous.
2. **Right derivative:** $`\lim_{h\to0^+}\frac{h^2-0}{h}=\lim h=0`$.
3. **Left derivative:** $`\lim_{h\to0^-}\frac{ah-0}{h}=a`$.
4. **Differentiable** means the two one-sided derivatives are equal: $`a=0`$.

**Why continuity alone is not enough:** for $`a\neq0`$ (for example $`a=1`$) the graph has no gap, but it has a **corner** at $`0`$: the slope on the left is $`a`$ and on the right is $`0`$. Without a single tangent line, there is no derivative.

---
