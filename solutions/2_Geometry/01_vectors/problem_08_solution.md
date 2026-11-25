### Exercise 8. Linear Combination and Checking the Result
Check whether $`w=(5,1)`$ can be written as

```math
w=au+bv,
```

where $`u=(1,1)`$ and $`v=(2,-1)`$. If so, find $`a,b`$, reconstruct $`w`$ from them, and explain the geometric meaning of the existence of such coefficients.

> **Why this exercise:** connects linear combinations with the geometry of directions.

#### Answer
- Yes: $`a=\frac73`$, $`b=\frac43`$.
- $`w=\frac73u+\frac43v`$.

#### How I solved it
**Idea:** can we reach $`w`$ by taking $`a`$ copies of $`u`$ and $`b`$ copies of $`v`$?

1. **Write it out:** $`a(1,1)+b(2,-1)=(a+2b,\ a-b)`$. Setting it equal to $`(5,1)`$ gives the system $`a+2b=5`$ and $`a-b=1`$.
2. **Solve:** subtract the second equation from the first: $`3b=4`$, so $`b=\frac43`$.
3. **Find $`a`$:** from $`a-b=1`$, $`a=1+\frac43=\frac73`$.
4. **Check:** $`\frac73(1,1)+\frac43(2,-1)=\left(\frac73+\frac83,\ \frac73-\frac43\right)=(5,1)`$ ✓

**Geometric meaning:** $`u`$ and $`v`$ point in two different directions (they are not on one line). With two different directions you can reach **any** point in the plane by going some distance along $`u`$ and some along $`v`$. That is why the coefficients exist.

---
