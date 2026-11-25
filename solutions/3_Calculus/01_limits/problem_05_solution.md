### Exercise 5. The Classical Limit Leading to the Number $`e`$
Compute

```math
\lim_{n\to\infty}\left(1+\frac1n\right)^n.
```

Calculate several values for increasing $`n`$ and compare the observed behavior with the value of the limit. Explain why a few values do not constitute a proof.

> **Why this exercise:** connects a central limit with intuition based on concrete terms of a sequence.

#### Answer

```math
e\approx2.71828
```

| $`n`$ | $`\left(1+\frac1n\right)^n`$ |
|---|---|
| $`1`$ | $`2`$ |
| $`10`$ | $`2.5937`$ |
| $`100`$ | $`2.7048`$ |
| $`1000`$ | $`2.7169`$ |
| $`10000`$ | $`2.7181`$ |
| $`100000`$ | $`2.71827`$ |

#### How I solved it
- **The limit:** this is the standard definition-type limit of the number $`e`$.
- **The values:** I computed $`\left(1+\frac1n\right)^n`$ for increasing $`n`$. The values grow and get closer to $`2.71828\ldots`$, matching $`e`$.

**Why a few values are not a proof:** numbers only show what happens for those particular $`n`$. They do not guarantee what happens for all larger $`n`$ (a sequence could look like it settles and then change). A proof needs a general argument valid for all $`n`$.

---
