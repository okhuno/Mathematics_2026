### Exercise 3. Plane Through a Point with a Given Normal Vector
Find the equation of the plane through $`P=(1,-2,3)`$ and perpendicular to $`n=(2,1,-1)`$. Check the result by substituting the point $`P`$ and explain the role of the normal vector.

> **Why this exercise:** shows the basic construction of a plane from a point and a normal vector.

#### Answer

```math
2x+y-z+3=0
```

#### How I solved it
A point $`X=(x,y,z)`$ is in the plane exactly when the arrow from $`P`$ to $`X`$ is perpendicular to $`n`$: $`n\cdot(X-P)=0`$.

```math
2(x-1)+1\cdot(y+2)-1\cdot(z-3)=0\ \Rightarrow\ 2x-2+y+2-z+3=0\ \Rightarrow\ 2x+y-z+3=0.
```

**Check $`P`$:** $`2\cdot1+(-2)-3+3=0`$ ✓.

**Role of the normal vector:** it gives the plane's "tilt." It fixes the coefficients $`(2,1,-1)`$ of $`x,y,z`$; the point only fixes the constant term.

---
