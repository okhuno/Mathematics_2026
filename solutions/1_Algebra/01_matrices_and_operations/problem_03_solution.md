### Exercise 3. When Can Matrices Be Multiplied?
The matrix sizes are

$$
A_{2\times3},\qquad B_{3\times4},\qquad C_{4\times2},\qquad D_{2\times2}.
$$

For the products

$$
AB,\ BA,\ BC,\ CB,\ AC,\ CA,\ AD,\ DA
$$

determine whether they are defined. If so, state the size of the result. Justify each decision using the dimension compatibility condition.

> **Why this exercise:** forces an understanding of dimension compatibility before carrying out any calculation.

#### Answer

| Product | Sizes | Defined? | Result size |
|---|---|---|---|
| $AB$ | $2\times3$ and $3\times4$ | yes | $2\times4$ |
| $BA$ | $3\times4$ and $2\times3$ | **no** | — |
| $BC$ | $3\times4$ and $4\times2$ | yes | $3\times2$ |
| $CB$ | $4\times2$ and $3\times4$ | **no** | — |
| $AC$ | $2\times3$ and $4\times2$ | **no** | — |
| $CA$ | $4\times2$ and $2\times3$ | yes | $4\times3$ |
| $AD$ | $2\times3$ and $2\times2$ | **no** | — |
| $DA$ | $2\times2$ and $2\times3$ | yes | $2\times3$ |

#### How I solved it
**Condition:** $X_{m\times n}\cdot Y_{p\times q}$ is defined only if the **inner numbers match**, $n=p$. The result then has the **outer numbers**, $m\times q$.

- $AB$: inner $3=3$ ✓, outer $2\times4$.
- $BA$: inner $4$ vs $2$ ✗.
- $BC$: inner $4=4$ ✓, outer $3\times2$.
- $CB$: inner $2$ vs $3$ ✗.
- $AC$: inner $3$ vs $4$ ✗.
- $CA$: inner $2=2$ ✓, outer $4\times3$.
- $AD$: inner $3$ vs $2$ ✗.
- $DA$: inner $2=2$ ✓, outer $2\times3$.

---
