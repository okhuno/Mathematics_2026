### Exercise 15. Observation Versus Proof
Choose one sequence and one function from this set. For the sequence, compute several values for increasingly large $`n`$. For the function, prepare a table of values with arguments approaching the limit point from the left and right. Sketch the behavior of both objects.

Compare the observation with the analytical result and explain why a finite number of calculations or a sketch does not constitute a proof that the limit exists.

> **Why this exercise:** teaches how to distinguish intuition and observation from mathematical argument.

#### Answer
**Sequence** (from Exercise 5): $`a_n=\left(1+\frac1n\right)^n`$

| $`n`$ | $`a_n`$ |
|---|---|
| $`10`$ | $`2.5937`$ |
| $`100`$ | $`2.7048`$ |
| $`1000`$ | $`2.7169`$ |
| $`10000`$ | $`2.7181`$ |

Observation: the values rise toward about $`2.718`$. Analytical result: the limit is $`e\approx2.71828`$ ✓.

**Function** (from Exercise 7): $`f(x)=\dfrac{x^2-4x+3}{x-3}`$, $`x\to3`$

| $`x`$ (from the left) | $`f(x)`$ | $`x`$ (from the right) | $`f(x)`$ |
|---|---|---|---|
| $`2.9`$ | $`1.9`$ | $`3.1`$ | $`2.1`$ |
| $`2.99`$ | $`1.99`$ | $`3.01`$ | $`2.01`$ |
| $`2.999`$ | $`1.999`$ | $`3.001`$ | $`2.001`$ |

Observation: from both sides the values approach $`2`$. Analytical result: $`f(x)=x-1`$ for $`x\ne3`$, so the limit is $`2`$ ✓.

**Sketch of the function:** the straight line $`y=x-1`$ with a single **hole** (open circle) at the point $`(3,2)`$.

#### How I solved it
I computed the table values (for the function, $`f(x)=x-1`$ except at $`x=3`$, so for example $`f(2.9)=1.9`$ and $`f(3.1)=2.1`$), then compared them with the exact limits from Exercises 5 and 7.

**Why observation is not proof:** a table or sketch shows only finitely many cases. A sequence could behave like it is converging for a million terms and then change. For example, define $`b_n=\frac1n`$ for $`n<10^6`$ and $`b_n=5`$ for $`n\ge10^6`$: all the early values look like they go to $`0`$, but the limit is $`5`$. Only an argument that covers **all** large $`n`$ (algebra, squeeze theorem, known limits) proves that a limit exists.
