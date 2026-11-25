### Problem 11. A Parameter and the Number of Extrema
For

```math
f_a(x)=x^3-3ax
```

depending on $`a`$, determine the number of critical points and their character. Separate the parameter cases and justify why the structure of the graph changes.

> **Why this problem:** it teaches how to analyze an entire family of functions instead of a single example.

#### Answer

| Case | Critical points | Character |
|---|---|---|
| $`a<0`$ | none | $`f'>0`$ always: increasing, no extrema |
| $`a=0`$ | $`x=0`$ only | $`f=x^3`$: $`f'`$ does not change sign, so **no** extremum (flat inflection) |
| $`a>0`$ | $`x=-\sqrt a`$ and $`x=\sqrt a`$ | local **max** at $`x=-\sqrt a`$ ($`f=2a\sqrt a`$), local **min** at $`x=\sqrt a`$ ($`f=-2a\sqrt a`$) |

#### How I solved it
1. **Derivative:** $`f_a'(x)=3x^2-3a=3(x^2-a)`$.
2. **Critical points:** $`x^2=a`$.
   - If $`a<0`$: $`x^2=a`$ has no real solutions. And $`x^2-a>0`$ always, so $`f'>0`$: always increasing.
   - If $`a=0`$: $`f'=3x^2\ge0`$, zero only at $`x=0`$. It does not change sign, so no extremum.
   - If $`a>0`$: $`x=\pm\sqrt a`$. $`f'>0`$ for $`|x|>\sqrt a`$ and $`f'<0`$ between. So $`+\to-`$ at $`-\sqrt a`$ (max), $`-\to+`$ at $`\sqrt a`$ (min).
3. **Values:** $`f_a(\sqrt a)=a\sqrt a-3a\sqrt a=-2a\sqrt a`$, and $`f_a(-\sqrt a)=2a\sqrt a`$.

**Why the structure changes:** the equation $`f'=0`$ (a quadratic) switches from no solutions, to one, to two, depending on the sign of $`a`$. The graph goes from a plain increasing curve to a curve with a "hill and a valley."

---
