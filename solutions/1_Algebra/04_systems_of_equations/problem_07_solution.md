### Exercise 7. Choosing a Method Deliberately
Do not solve all of the following systems completely. For each situation, choose the method that best uses its structure and justify your choice:

1. one system with a triangular coefficient matrix

```math
\begin{cases}
2x-y=3, \\
4y=8;
\end{cases}
```

2. three systems $`Ax=b_i`$ with the same invertible matrix $`A`$, when $`A^{-1}`$ is already known;
3. one $`3\times3`$ system for which the inverse matrix is not given and the goal is only to find one solution vector.

For case 1, carry out the chosen method completely. For cases 2 and 3, describe the plan and indicate which part of the computation would be reusable or unnecessary. Do not judge a method by its name alone — refer to the number of right-hand sides and the structure of the matrix.

> **Why this exercise:** practices choosing a method based on the structure of the problem instead of solving another small system by two methods.

#### Answer
1. **Back substitution** (the matrix is already triangular): $`(x,y)=\left(\frac52,\ 2\right)`$.
2. **Multiply by the known inverse:** $`x_i=A^{-1}b_i`$ for each $`i`$.
3. **Gaussian elimination** directly on $`[A\mid b]`$ (do not compute the inverse).

#### How I solved it
1. **Triangular system:** no elimination is needed. The second equation has only $`y`$: $`4y=8\Rightarrow y=2`$. Put it into the first: $`2x-2=3\Rightarrow x=\frac52`$.
   **Check:** $`2\cdot\frac52-2=3`$ ✓ and $`4\cdot2=8`$ ✓.
2. **Three right sides, same $`A`$, $`A^{-1}`$ known:** the expensive part (finding $`A^{-1}`$) is already done and is **reusable**. Each new system costs just one matrix–vector multiplication: $`x_1=A^{-1}b_1`$, $`x_2=A^{-1}b_2`$, $`x_3=A^{-1}b_3`$.
3. **One $`3\times3`$ system, no inverse:** use Gaussian elimination on $`[A\mid b]`$. Computing $`A^{-1}`$ would take about as much work as solving three systems, which is **unnecessary** when we have only one right-hand side.

The choice depends on structure (triangular) and on the number of right-hand sides (1 or many), not on the name of the method.

---
