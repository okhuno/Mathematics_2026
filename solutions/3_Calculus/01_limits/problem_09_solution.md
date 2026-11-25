### Exercise 9. One-Sided Limits and an Asymptote
Analyze the left-hand and right-hand limits of

```math
f(x)=\frac1{x-2}
```

as $`x\to2`$. Does the two-sided limit exist? Interpret the result on a sketch of the graph and identify the vertical asymptote.

> **Why this exercise:** teaches how to distinguish one-sided limits and connect them with the geometry of an asymptote.

#### Answer
- $`\lim_{x\to2^-}\frac1{x-2}=-\infty`$
- $`\lim_{x\to2^+}\frac1{x-2}=+\infty`$
- The two-sided limit **does not exist**. Vertical asymptote: $`x=2`$.

![1/(x-2)](images/lim_ex9.png)

#### How I solved it
- **From the right** ($`x=2.1,\ 2.01,\ 2.001,\dots`$): $`x-2`$ is a tiny positive number, so $`\frac1{x-2}`$ is a huge positive number: $`+\infty`$.
- **From the left** ($`x=1.9,\ 1.99,\ 1.999,\dots`$): $`x-2`$ is a tiny negative number, so $`\frac1{x-2}`$ is a huge negative number: $`-\infty`$.
- The two sides disagree, so the two-sided limit does not exist.

**Graph:** the curve shoots up on the right of $`x=2`$ and down on the left, hugging the vertical line $`x=2`$, which is the vertical asymptote.

---
