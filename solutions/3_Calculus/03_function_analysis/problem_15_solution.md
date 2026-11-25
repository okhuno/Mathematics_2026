### Problem 15. Find the Error in the Monotonicity Analysis
For the function

```math
f(x)=x^3-3x
```

the derivative was correctly computed as

```math
f'(x)=3(x-1)(x+1).
```

However, a student wrote the following conclusion:

> The derivative is positive between its zeros and negative outside them. Therefore, the function is decreasing on $`(-\infty,-1)\cup(1,\infty)`$, increasing on $`(-1,1)`$, has a local minimum at $`x=-1`$, and a local maximum at $`x=1`$.

1. Without differentiating again, explain why merely identifying the zeros of the derivative does not justify the stated sign chart, and find the error in the student's reasoning.
2. Construct the correct sign chart for $`f'(x)`$.
3. Give the correct intervals of monotonicity and the character of the extrema.
4. In each of the three intervals, choose one simple test point and show that the sign of the derivative confirms your classification.

> **Why this problem:** it teaches how to diagnose an error in a completed argument and shows that a correct derivative formula is not enough if its sign is interpreted incorrectly.

#### Answer
1. The zeros $`\pm1`$ only tell where $`f'`$ **could** change sign. They do not say which side is positive. The student assumed "positive between zeros," but $`f'=3(x^2-1)`$ is an upward-opening parabola, which is positive **outside** its zeros and negative **between** them. The student's signs are reversed.
2. Sign chart:

| Interval | $`(-\infty,-1)`$ | $`(-1,1)`$ | $`(1,\infty)`$ |
|---|---|---|---|
| $`f'`$ | $`+`$ | $`-`$ | $`+`$ |

3. $`f`$ is **increasing** on $`(-\infty,-1)`$ and $`(1,\infty)`$, **decreasing** on $`(-1,1)`$. Local **maximum** at $`x=-1`$ ($`f=2`$), local **minimum** at $`x=1`$ ($`f=-2`$). (The student swapped everything.)
4. Test points:
   - $`x=-2`$: $`f'(-2)=3(-3)(-1)=9>0`$ ✓ increasing
   - $`x=0`$: $`f'(0)=3(-1)(1)=-3<0`$ ✓ decreasing
   - $`x=2`$: $`f'(2)=3(1)(3)=9>0`$ ✓ increasing

#### How I solved it
- **Where the error is:** the zeros of a factored expression split the line into intervals, but each interval's sign must be checked separately (by a test point, or from the leading coefficient). Two sign changes at $`-1`$ and $`1`$ with an upward-opening parabola give $`+,-,+`$.
- **Extrema:** $`+\to-`$ at $`x=-1`$: maximum, $`f(-1)=-1+3=2`$. $`-\to+`$ at $`x=1`$: minimum, $`f(1)=1-3=-2`$.
- **The student's conclusion was wrong in all four statements:** the intervals of increase and decrease are swapped, and so are the maximum and the minimum.
