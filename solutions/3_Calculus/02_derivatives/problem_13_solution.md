### Problem 13. A Multi-Layer Composition
For

```math
f(x)=e^{\sin(x^2)}
```

compute the derivative. First write the layers

```math
x\longrightarrow x^2\longrightarrow \sin(x^2)\longrightarrow e^{\sin(x^2)}
```

and explain why differentiation moves through them in the reverse order.

> **Why this problem:** it develops the chain rule as a method for working with multiple layers.

#### Answer

```math
f'(x)=2x\cos(x^2)\,e^{\sin(x^2)}
```

#### How I solved it
Layers (from the inside out): $`x^2`$, then $`\sin(\cdot)`$, then $`e^{(\cdot)}`$.

Differentiate from the **outside in**, multiplying:
1. Outer layer $`e^{(\cdot)}`$: derivative $`e^{\sin(x^2)}`$ (keeping the inside unchanged).
2. Next layer $`\sin(\cdot)`$: derivative $`\cos(x^2)`$.
3. Inner layer $`x^2`$: derivative $`2x`$.

```math
f'(x)=e^{\sin(x^2)}\cdot\cos(x^2)\cdot2x.
```

**Why reverse order:** the function is computed from the inside out (first square, then sine, then exponential). But the derivative of an outer layer must be evaluated at the output of the inner layers, so we begin with the outermost layer and peel inward, multiplying each layer's derivative.

---
