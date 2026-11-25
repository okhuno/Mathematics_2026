### Exercise 7. Linear Dependence Without Heavy Computation
Given

```math
u=(1,2,3),\qquad v=(2,4,6),\qquad w=(0,1,1).
```

Identify a specific relation between $`u`$ and $`v`$, decide whether the three vectors can be linearly independent, and explain why no long calculation is needed.

> **Why this exercise:** develops the habit of recognizing structure before applying a computational procedure.

#### Answer
- Relation: $`v=2u`$.
- The three vectors are **linearly dependent** (they cannot be independent).
- Proof: $`2u-v+0\cdot w=0`$.

#### How I solved it
**What "linearly dependent" means:** at least one vector can be built from the others (or: you can combine them with coefficients that are not all zero and get the zero vector).

1. **Spot the relation:** every number in $`v`$ is double the matching number in $`u`$, so $`v=2u`$.
2. **Turn it into a zero combination:** $`2u-v+0\cdot w=(2,4,6)-(2,4,6)+(0,0,0)=(0,0,0)`$. The coefficients $`2,-1,0`$ are not all zero, so the set is dependent.

**Why no long calculation is needed:** $`u`$ and $`v`$ lie on the same line, so one of them is redundant. If any vector in a set is a multiple of another one, the whole set is dependent, whatever $`w`$ is.

---
