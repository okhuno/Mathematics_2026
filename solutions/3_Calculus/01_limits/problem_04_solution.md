
### Exercise 4. Powers and Oscillation
Analyze

```math
\left(\frac23\right)^n,\qquad \left(\frac32\right)^n,\qquad (-1)^n,\qquad \frac{(-1)^n}{n}.
```

For each sequence, describe the type of behavior and justify your answer.

> **Why this exercise:** organizes the basic types of sequence behavior and shows that oscillation does not always rule out convergence.

#### Answer

| Sequence | Behavior |
|---|---|
| $`\left(\frac23\right)^n`$ | converges to $`0`$ |
| $`\left(\frac32\right)^n`$ | diverges to $`+\infty`$ |
| $`(-1)^n`$ | diverges (oscillates between $`-1`$ and $`1`$, no limit) |
| $`\frac{(-1)^n}{n}`$ | converges to $`0`$ (oscillates, but with shrinking size) |

#### How I solved it
- $`\left(\frac23\right)^n`$: the base is between $`-1`$ and $`1`$ (in absolute value less than $`1`$), so repeated multiplication makes it smaller and smaller, toward $`0`$.
- $`\left(\frac32\right)^n`$: the base is greater than $`1`$, so it grows without bound.
- $`(-1)^n=-1,1,-1,1,\dots`$: it keeps jumping between two values and never settles, so there is no limit.
- $`\frac{(-1)^n}{n}`$: the absolute value is $`\frac1n\to0`$. Since $`-\frac1n\le\frac{(-1)^n}{n}\le\frac1n`$ and both bounds go to $`0`$, the sequence is squeezed to $`0`$ (squeeze theorem).

**Lesson:** oscillation does not forbid convergence if the oscillations shrink to zero.

---
