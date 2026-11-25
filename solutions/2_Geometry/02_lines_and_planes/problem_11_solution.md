### Exercise 11. Plane Containing a Line and a Point
Find the equation of the plane containing

```math
(x,y,z)=(1,0,2)+t(1,1,-1)
```

and the point $`P=(0,2,1)`$. Check that both the entire line and the point lie in the plane you obtain.

> **Why this exercise:** requires independently constructing two linearly independent directions in the plane.

#### Answer

```math
x+2y+3z-7=0
```

#### How I solved it
1. **Two directions in the plane:** the line's direction $`d=(1,1,-1)`$, and the vector from a point of the line $`A=(1,0,2)`$ to $`P`$: $`\overrightarrow{AP}=(-1,2,-1)`$.
2. **Normal = cross product:**
   - first: $`1\cdot(-1)-(-1)\cdot2=1`$
   - second: $`(-1)\cdot(-1)-1\cdot(-1)=2`$
   - third: $`1\cdot2-1\cdot(-1)=3`$

   So $`n=(1,2,3)`$.
3. **Equation:** $`x+2y+3z=d`$. Plug in $`A`$: $`1+0+6=7`$. So $`x+2y+3z-7=0`$.

**Check:**
- $`P`$: $`0+4+3-7=0`$ ✓
- Whole line $`(1+t,\ t,\ 2-t)`$: $`(1+t)+2t+3(2-t)-7=1+t+2t+6-3t-7=0`$ for every $`t`$ ✓

---
