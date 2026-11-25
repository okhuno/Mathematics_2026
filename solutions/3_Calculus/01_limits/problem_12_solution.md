### Exercise 12. Exponential Function Limit
Compute

```math
\lim_{x\to0}(1+3x)^{1/x}.
```

Connect the result with the limit from Exercise 5 and show the appropriate transformation.

> **Why this exercise:** teaches how to recognize the classical pattern after a transformation.

#### Answer

```math
e^3
```

#### How I solved it
The classical limit is $`\lim_{u\to0}(1+u)^{1/u}=e`$ (it is Exercise 5 with $`u=\frac1n`$).
1. Let $`u=3x`$. As $`x\to0`$, $`u\to0`$, and $`\frac1x=\frac3u`$.
2. $`(1+3x)^{1/x}=(1+u)^{3/u}=\left[(1+u)^{1/u}\right]^3\to e^3`$.

**Connection:** the expression has the shape "$`(1+\text{small})^{1/\text{small}}`$" only after we rewrite the exponent to match the small quantity $`3x`$; the extra factor $`3`$ becomes the power $`3`$ on $`e`$.

---
