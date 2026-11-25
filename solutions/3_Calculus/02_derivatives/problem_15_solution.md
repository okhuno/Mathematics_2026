### Problem 15. The Difference Quotient as a Check of the Derivative
Choose one function from the problem set and a point $`x_0`$ at which the derivative exists. Compute $`f'(x_0)`$ exactly, and then calculate

```math
\frac{f(x_0+h)-f(x_0)}h
```

for $`h=1`$, $`0.1`$, and $`0.01`$. Compare the values with $`f'(x_0)`$ and explain why the difference quotient approaching a single number is consistent with the definition of the derivative, while a few computations do not replace a limit argument.

> **Why this problem:** it connects the definition of the derivative with concrete calculations and teaches the distinction between observation and proof.

#### Answer
Chosen function: $`f(x)=x^2`$ (from Problem 11), point $`x_0=1`$.
- Exact: $`f'(1)=2\cdot1=2`$.

| $`h`$ | $`\dfrac{f(1+h)-f(1)}{h}`$ |
|---|---|
| $`1`$ | $`3`$ |
| $`0.1`$ | $`2.1`$ |
| $`0.01`$ | $`2.01`$ |

The values approach $`2=f'(1)`$.

#### How I solved it
- **Exact derivative:** $`f'(x)=2x`$, so $`f'(1)=2`$.
- **Difference quotient:** $`\dfrac{(1+h)^2-1}{h}=\dfrac{2h+h^2}{h}=2+h`$.
  - $`h=1`$: $`2+1=3`$
  - $`h=0.1`$: $`2.1`$
  - $`h=0.01`$: $`2.01`$

**Comparison:** the numbers get closer to $`2`$ as $`h`$ gets smaller. This matches the definition: $`f'(x_0)`$ is the limit of the difference quotient as $`h\to0`$, and here the quotient equals $`2+h\to2`$.

**Observation vs. proof:** three values suggest the limit but do not prove it. A different function could look like it approaches $`2`$ for $`h=1,0.1,0.01`$ and still behave differently for smaller $`h`$. A proof needs an argument that works for **all** small $`h`$, like the algebra $`2+h\to2`$ above.
