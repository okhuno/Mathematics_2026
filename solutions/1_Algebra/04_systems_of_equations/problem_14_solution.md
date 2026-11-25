### Exercise 14. A Small Change in the Right-Hand Side
Compare the systems

```math
\begin{cases}
x+y=2, \\
2x-y=1, \\
3x=3
\end{cases}
```

and

```math
\begin{cases}
x+y=2, \\
2x-y=1, \\
3x=3.1.
\end{cases}
```

Check the consistency of each system and explain why a small change in one number can change the type of the system.

> **Why this exercise:** shows the difference between a consistent and an inconsistent system without introducing new theory.

#### Answer
- First system: consistent, unique solution $`(x,y)=(1,1)`$.
- Second system: **inconsistent** (no solution).

#### How I solved it
- **Add the first two equations:** $`(x+y)+(2x-y)=2+1\Rightarrow3x=3\Rightarrow x=1`$, then $`y=1`$.
- **First system:** the third equation $`3x=3`$ is also satisfied by $`x=1`$ ✓. All three agree at $`(1,1)`$.
- **Second system:** the first two equations still force $`x=1`$, but the third needs $`x=\frac{3.1}{3}\approx1.033`$. A contradiction: no solution.

**Why a tiny change matters:** we have three equations but only two unknowns, so the equations must be "perfectly aligned." Geometrically, three lines in the plane pass through one common point $`(1,1)`$ in the first system. Changing $`3x=3`$ to $`3x=3.1`$ moves the third line a little to the side, so it no longer passes through $`(1,1)`$, and the three lines have no common point.

---
