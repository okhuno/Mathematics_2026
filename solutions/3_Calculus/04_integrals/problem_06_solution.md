### Problem 6. When Does a Logarithm Appear from an Integral?
Compute

```math
\int\frac{2x}{x^2+5}\,dx.
```

Identify the denominator as a candidate for substitution, compare the numerator with its derivative, and explain the source of the logarithm in the result.

> **Why this problem:** it teaches how to recognize the structure “derivative of the denominator over the denominator.”

#### Answer

```math
\ln(x^2+5)+C
```

#### How I solved it
1. **Candidate:** $`u=x^2+5`$ (the denominator).
2. **Its derivative:** $`du=2x\,dx`$, which is exactly the numerator.
3. **Substitute:** $`\int\frac{du}{u}=\ln|u|+C`$.
4. **Back:** $`\ln|x^2+5|+C=\ln(x^2+5)+C`$ (no absolute value needed because $`x^2+5>0`$).

**Source of the logarithm:** the structure "derivative of the denominator over the denominator" is $`\frac{u'}{u}`$, and $`\int\frac1u\,du=\ln|u|`$.

**Verify:** $`(\ln(x^2+5))'=\frac{2x}{x^2+5}`$ ✓

---
