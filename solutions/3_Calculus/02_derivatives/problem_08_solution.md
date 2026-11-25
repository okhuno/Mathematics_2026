### Problem 8. Two Exponential Functions
For

```math
f(x)=e^{2x-3}+5^x
```

compute the derivative. Explain why the factor $`2`$ appears in the first term and why $`\ln5`$ appears in the second.

> **Why this problem:** it organizes two different mechanisms that produce additional factors.

#### Answer

```math
f'(x)=2e^{2x-3}+5^x\ln5
```

#### How I solved it
- **First term (chain rule):** outer $`e^u`$ has derivative $`e^u`$; inner $`u=2x-3`$ has derivative $`2`$. So $`(e^{2x-3})'=e^{2x-3}\cdot2`$.
- **Second term:** $`(a^x)'=a^x\ln a`$ with $`a=5`$.

**Why the factor $`2`$:** it is the derivative of the inner function $`2x-3`$ (chain rule).

**Why $`\ln5`$:** write $`5^x=e^{x\ln5}`$. Using the chain rule, the inner function $`x\ln5`$ has derivative $`\ln5`$, so $`(5^x)'=e^{x\ln5}\cdot\ln5=5^x\ln5`$.

---
