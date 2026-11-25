### Problem 11. Derivative from the Definition
Using only

```math
f'(x)=\lim_{h\to0}\frac{f(x+h)-f(x)}h,
```

find the derivative of $`f(x)=x^2`$. Compare the result with the power rule and indicate where the limit is used in the calculation.

> **Why this problem:** it shows the origin of the power rule and the direct connection between the derivative and a limit.

#### Answer

```math
f'(x)=2x
```

#### How I solved it
1. Write the difference quotient: $`\dfrac{(x+h)^2-x^2}{h}`$.
2. Expand: $`(x+h)^2=x^2+2xh+h^2`$, so the numerator is $`2xh+h^2`$.
3. Cancel one $`h`$ (allowed because $`h\ne0`$ while $`h\to0`$): $`\dfrac{2xh+h^2}{h}=2x+h`$.
4. **Take the limit:** $`\lim_{h\to0}(2x+h)=2x`$.

**Compare with the power rule:** $`(x^2)'=2x^{2-1}=2x`$ ✓.

**Where the limit is used:** only in the last step: after the algebra, $`h\to0`$ makes the leftover $`h`$ disappear. Before that, we could not substitute $`h=0`$ directly because we would get $`\frac00`$.

---
