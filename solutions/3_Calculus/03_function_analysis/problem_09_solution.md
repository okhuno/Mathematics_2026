### Problem 9. An Oblique Asymptote
Analyze the asymptotes of

```math
f(x)=\frac{x^2+1}{x-1}.
```

Perform polynomial division and explain why the remainder term vanishes for large $`|x|`$.

> **Why this problem:** it teaches how to recognize an oblique asymptote and interpret the decomposition of a function.

#### Answer
- $`f(x)=x+1+\dfrac{2}{x-1}`$.
- Vertical asymptote $`x=1`$; oblique asymptote $`y=x+1`$. No horizontal asymptote.

#### How I solved it
1. **Division:** $`x^2+1=(x-1)(x+1)+2`$ (because $`(x-1)(x+1)=x^2-1`$, and we need $`+2`$ more). So

```math
\frac{x^2+1}{x-1}=x+1+\frac{2}{x-1}.
```

2. **Vertical asymptote:** the denominator is $`0`$ at $`x=1`$, while the numerator is $`2\neq0`$ there. As $`x\to1^+`$, $`f\to+\infty`$; as $`x\to1^-`$, $`f\to-\infty`$.
3. **Oblique asymptote:** the term $`\frac2{x-1}\to0`$ as $`x\to\pm\infty`$, so $`f(x)-(x+1)\to0`$. The graph hugs the line $`y=x+1`$.

**Why the remainder vanishes:** a fixed number $`2`$ divided by a huge number $`x-1`$ is tiny. So for large $`|x|`$, $`f`$ is almost exactly $`x+1`$.

---
