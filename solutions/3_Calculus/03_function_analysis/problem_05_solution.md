### Problem 5. An Exponential Function with a Maximum
Analyze the monotonicity and extrema of

```math
f(x)=xe^{-x}.
```

Also examine the behavior as $`x\to\infty`$ and explain how the limit affects the shape of the graph on the right-hand side.

> **Why this problem:** it combines the derivative with a limit in the description of the global behavior of a function.

#### Answer
- $`f'(x)=e^{-x}(1-x)`$. Increasing on $`(-\infty,1)`$, decreasing on $`(1,\infty)`$.
- Maximum at $`x=1`$: $`f(1)=\frac1e\approx0.368`$.
- $`\lim_{x\to\infty}xe^{-x}=0`$: the $`x`$-axis is a horizontal asymptote on the right.

![P5](images/fa_p5.png)

#### How I solved it
1. **Derivative (product rule):** $`f'=1\cdot e^{-x}+x\cdot(-e^{-x})=e^{-x}(1-x)`$.
2. **Sign:** $`e^{-x}>0`$ always, so the sign of $`f'`$ equals the sign of $`1-x`$: positive for $`x<1`$, negative for $`x>1`$. Zero at $`x=1`$.
3. **Extremum:** $`+\to-`$ at $`x=1`$, so a maximum, with value $`1\cdot e^{-1}=\frac1e`$.
4. **Limit at $`+\infty`$:** $`xe^{-x}=\frac{x}{e^x}\to0`$ because the exponential grows much faster than $`x`$.

**Effect on the graph:** after the peak at $`x=1`$ the graph falls and flattens out, getting closer and closer to the $`x`$-axis but staying above it (since $`f>0`$ for $`x>0`$). On the left, $`f\to-\infty`$ as $`x\to-\infty`$.

---
