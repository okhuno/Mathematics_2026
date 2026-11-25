### Exercise 13. Does Every Equation Add New Information?
Consider the system

```math
x_1+x_2=10,\qquad x_2+x_3=8,\qquad x_1-x_3=2.
```

Solve it and check whether all three equations are independently necessary to describe the solution set. If one follows from the others, show this by calculation.

> **Why this exercise:** teaches how to recognize redundant equations within a system.

#### Answer
- The third equation is redundant: Eq.1 $`-`$ Eq.2 gives Eq.3.
- Solutions: $`(x_1,x_2,x_3)=(2+t,\ 8-t,\ t)`$, $`t\in\mathbb R`$ (infinitely many).

#### How I solved it
- **Subtract** the second equation from the first: $`(x_1+x_2)-(x_2+x_3)=10-8\Rightarrow x_1-x_3=2`$. That is exactly the third equation. So it carries no new information.
- **Solve using the first two equations:** let $`x_3=t`$. Then $`x_2=8-t`$ and $`x_1=10-x_2=2+t`$.

**Check** with $`t=0`$: $`(2,8,0)`$: $`2+8=10`$ ✓; $`8+0=8`$ ✓; $`2-0=2`$ ✓.

So only two of the three equations are independent. With 3 unknowns and 2 independent equations, one variable stays free.

---
