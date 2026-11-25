### Problem 13. A Logarithm and an Asymptote
Perform a complete analysis of

```math
f(x)=\frac{\ln x}{x},\qquad x>0.
```

Find the maximum and the behavior at the ends of the domain. Explain which information is necessary for a correct sketch.

> **Why this problem:** it combines the domain, limits, and derivative in a less obvious example.

#### Answer
- Zero: $`x=1`$.
- $`f'(x)=\dfrac{1-\ln x}{x^2}`$: increasing on $`(0,e)`$, decreasing on $`(e,\infty)`$.
- Maximum: $`\left(e,\frac1e\right)`$, $`\frac1e\approx0.368`$.
- $`x\to0^+`$: $`f\to-\infty`$ (vertical asymptote $`x=0`$). $`x\to\infty`$: $`f\to0^+`$ (horizontal asymptote $`y=0`$, approached from above).
- $`f''(x)=\dfrac{2\ln x-3}{x^3}`$: concave on $`(0,e^{3/2})`$, convex after; inflection at $`x=e^{3/2}\approx4.48`$.

![P13](images/fa_p13.png)

#### How I solved it
1. **Domain:** $`x>0`$ (given).
2. **Zero:** $`\ln x=0\Rightarrow x=1`$. For $`x<1`$, $`f<0`$; for $`x>1`$, $`f>0`$.
3. **Derivative (quotient rule):** $`f'=\dfrac{\frac1x\cdot x-\ln x\cdot1}{x^2}=\dfrac{1-\ln x}{x^2}`$. The denominator is positive, so the sign is that of $`1-\ln x`$: positive when $`\ln x<1`$ (i.e. $`x<e`$), negative when $`x>e`$. Maximum at $`x=e`$, $`f(e)=\frac{1}{e}`$.
4. **Limits:** as $`x\to0^+`$: $`\ln x\to-\infty`$ and $`\frac1x\to+\infty`$, so the product $`\to-\infty`$. As $`x\to\infty`$: $`\ln x`$ grows much more slowly than $`x`$, so $`\frac{\ln x}{x}\to0`$.
5. **Second derivative:** $`f''=\dfrac{2\ln x-3}{x^3}`$, zero when $`\ln x=\frac32`$.

**What a correct sketch needs:** the domain ($`x>0`$ only), the zero at $`1`$, the plunge to $`-\infty`$ near $`0`$, the peak at $`(e,\frac1e)`$, and the slow decay toward $`y=0`$ from above for large $`x`$.

---
