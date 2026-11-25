### Exercise 2. Different Growth Rates
Compute

```math
\lim_{n\to\infty}\frac{3n+1}{n^2+4},\qquad \lim_{n\to\infty}\frac{2n^3-n}{5n^2+1}.
```

Compare the two cases and formulate a general observation about the degrees of the polynomials in the numerator and denominator.

> **Why this exercise:** teaches how to compare growth rates and recognize qualitatively different cases.

#### Answer
- First limit: $`0`$
- Second limit: $`+\infty`$

#### How I solved it
- **First:** divide by $`n^2`$: $`\dfrac{\frac3n+\frac1{n^2}}{1+\frac4{n^2}}\to\dfrac{0}{1}=0`$. The denominator grows faster.
- **Second:** divide by $`n^2`$: $`\dfrac{2n-\frac1n}{5+\frac1{n^2}}`$. The numerator $`\to\infty`$ and the denominator $`\to5`$, so the quotient $`\to+\infty`$. The numerator grows faster.

**General observation** (polynomial quotient as $`n\to\infty`$):
- degree of numerator **<** degree of denominator: limit $`0`$
- degrees **equal**: limit is the ratio of leading coefficients (as in Exercise 1)
- degree of numerator **>** degree of denominator: the limit is infinite

---
