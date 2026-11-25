### Problem 6. A Logarithmic Function
Analyze the domain, zero, and monotonicity of

```math
f(x)=\ln x-x+1.
```

Explain why the analysis must begin with the domain.

> **Why this problem:** it reinforces the role of the domain and derivative in the analysis of a logarithmic function.

#### Answer
- Domain: $`x>0`$.
- Zero: $`x=1`$.
- $`f'(x)=\dfrac{1-x}{x}`$: increasing on $`(0,1)`$, decreasing on $`(1,\infty)`$.
- Maximum at $`x=1`$ with value $`0`$. So $`f(x)\le0`$ everywhere, i.e. $`\ln x\le x-1`$.

#### How I solved it
1. **Domain:** $`\ln x`$ exists only for $`x>0`$.
2. **Zero:** $`f(1)=0-1+1=0`$ ✓. It is the only zero, because $`x=1`$ is the maximum with value $`0`$.
3. **Derivative:** $`f'(x)=\frac1x-1=\frac{1-x}{x}`$. For $`x>0`$ the denominator is positive, so the sign is that of $`1-x`$: positive for $`0<x<1`$, negative for $`x>1`$.
4. **Limits:** as $`x\to0^+`$, $`\ln x\to-\infty`$ so $`f\to-\infty`$; as $`x\to\infty`$, $`-x`$ wins so $`f\to-\infty`$.

**Why start with the domain:** the formula for $`f'`$ looks fine for negative $`x`$ too, but the function itself does not exist there. Any conclusion about signs is valid only for $`x>0`$.

---
