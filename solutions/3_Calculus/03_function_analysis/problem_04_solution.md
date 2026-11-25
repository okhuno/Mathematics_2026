### Problem 4. A Function with Two Vertical Asymptotes
Analyze

```math
f(x)=\frac1{x^2-1}.
```

Determine the domain, asymptotes, sign, and monotonicity on the intervals of the domain. Explain why each interval must be analyzed separately.

> **Why this problem:** it practices the analysis of a function on several disjoint intervals.

#### Answer
- Domain: $`x\neq\pm1`$, i.e. $`(-\infty,-1)\cup(-1,1)\cup(1,\infty)`$. $`f`$ is even.
- Asymptotes: $`x=-1`$, $`x=1`$ (vertical), $`y=0`$ (horizontal).
- No zeros. Sign: positive for $`|x|>1`$, negative for $`|x|<1`$.
- $`f'(x)=-\dfrac{2x}{(x^2-1)^2}`$.

| Interval | $`f'`$ | Behavior |
|---|---|---|
| $`(-\infty,-1)`$ | $`+`$ | increasing, from $`0`$ up to $`+\infty`$ |
| $`(-1,0)`$ | $`+`$ | increasing, from $`-\infty`$ up to $`-1`$ |
| $`(0,1)`$ | $`-`$ | decreasing, from $`-1`$ down to $`-\infty`$ |
| $`(1,\infty)`$ | $`-`$ | decreasing, from $`+\infty`$ down to $`0`$ |

Local maximum at $`(0,-1)`$ (inside the middle interval).

![P4](images/fa_p4.png)

#### How I solved it
1. **Domain:** $`x^2-1\ne0`$, so $`x\ne\pm1`$.
2. **Sign:** $`x^2-1>0`$ when $`|x|>1`$, and $`<0`$ when $`|x|<1`$. The numerator is $`1`$ (never $`0`$), so there are no zeros.
3. **Limits at the holes:** $`x\to1^+`$: $`x^2-1\to0^+`$, so $`f\to+\infty`$. $`x\to1^-`$: $`f\to-\infty`$. By symmetry $`x\to-1^-`$: $`+\infty`$ and $`x\to-1^+`$: $`-\infty`$.
4. **Derivative:** $`f=(x^2-1)^{-1}`$, so $`f'=-(x^2-1)^{-2}\cdot2x=-\dfrac{2x}{(x^2-1)^2}`$. The denominator is positive, so the sign of $`f'`$ is opposite to the sign of $`x`$: positive for $`x<0`$, negative for $`x>0`$.
5. **Horizontal asymptote:** $`\lim_{x\to\pm\infty}\frac1{x^2-1}=0`$.

**Why each interval separately:** the function does not exist at $`\pm1`$, so the graph is broken into three separate pieces. We cannot say "increasing" across a gap, and the three pieces behave differently (different signs, different limits).

---
