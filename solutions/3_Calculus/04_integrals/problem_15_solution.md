
### Problem 15. Recovering a Function from Its Derivative and a Condition
The function $`F`$ satisfies

```math
F'(x)=2xe^{x^2}
```

and

```math
F(0)=3.
```

1. Recognize the method needed to find the function $`F`$.
2. Determine the entire family of functions with the given derivative.
3. Use the condition $`F(0)=3`$ to determine the correct constant.
4. Verify the final result by differentiation and substitution of $`x=0`$.

> **Why this problem:** it combines recognition of substitution, the meaning of the constant of integration, and an initial condition in one problem, using only mechanisms introduced earlier.

#### Answer

```math
F(x)=e^{x^2}+2
```

#### How I solved it
1. **Method: substitution.** The inside $`x^2`$ has derivative $`2x`$, which appears as a factor.
2. **Family:** let $`u=x^2`$, $`du=2x\,dx`$: $`\int e^u\,du=e^u+C`$. So $`F(x)=e^{x^2}+C`$.
3. **Use $`F(0)=3`$:** $`F(0)=e^0+C=1+C=3\Rightarrow C=2`$.
4. **Final:** $`F(x)=e^{x^2}+2`$.

**Verify:** $`F'(x)=2xe^{x^2}`$ ✓ and $`F(0)=e^0+2=3`$ ✓.
