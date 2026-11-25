### Exercise 1. Line Through Two Points
Find the equation of the line through $`A=(1,2)`$ and $`B=(4,-1)`$ in parametric and general form. Identify a direction vector and an example of a normal vector. Check that both points satisfy the equation you obtain.

> **Why this exercise:** teaches how to move between equivalent descriptions of a line and connect them with the appropriate vectors.

#### Answer
- Direction vector: $`d=(3,-3)`$ (or $`(1,-1)`$).
- Parametric: $`(x,y)=(1,2)+t(3,-3)`$, i.e. $`x=1+3t,\ y=2-3t`$.
- Normal vector: $`n=(1,1)`$.
- General form: $`x+y-3=0`$.

#### How I solved it
1. **Direction:** end minus start, $`B-A=(3,-3)`$.
2. **Parametric form:** start at $`A`$ and move along $`d`$: $`(1,2)+t(3,-3)`$. At $`t=0`$ we are at $`A`$, at $`t=1`$ at $`B`$.
3. **Normal vector:** a vector perpendicular to $`d`$. Swap the components and change one sign: $`(1,1)`$. Check: $`(1,1)\cdot(3,-3)=3-3=0`$ ✓.
4. **General form:** $`x+y=c`$. Plug in $`A`$: $`1+2=3`$, so $`x+y-3=0`$.

**Check both points:** $`A`$: $`1+2-3=0`$ ✓. $`B`$: $`4-1-3=0`$ ✓.

---
