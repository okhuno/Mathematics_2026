### Problem 1. Motion — from Position to Velocity
The position of a point is described by

```math
s(t)=t^3-6t^2+9t+2,\qquad t\ge0.
```

1. Determine the velocity and acceleration.
2. Find the times at which the point stops.
3. Determine on which intervals the point moves in the positive direction of the axis and on which intervals it moves in the negative direction.

> **Why this problem:** it shows the derivative as a real rate of change and requires interpretation of the sign of the derivative in the context of motion.

#### Answer
1. $`v(t)=3t^2-12t+9=3(t-1)(t-3)`$, $`\ a(t)=6t-12`$.
2. The point stops at $`t=1`$ and $`t=3`$.
3. Moves in the positive direction on $`[0,1)`$ and $`(3,\infty)`$; in the negative direction on $`(1,3)`$.

#### How I solved it
1. **Derivatives:** $`v=s'=3t^2-12t+9`$. Factor: $`3(t^2-4t+3)=3(t-1)(t-3)`$. Then $`a=v'=6t-12`$.
2. **Stops:** $`v=0\Rightarrow t=1`$ or $`t=3`$.
3. **Sign of $`v`$** (test points): $`t=0`$: $`v=9>0`$; $`t=2`$: $`v=3(1)(-1)=-3<0`$; $`t=4`$: $`v=3(3)(1)=9>0`$.

**Extra information:** $`s(0)=2`$, $`s(1)=1-6+9+2=6`$, $`s(3)=27-54+27+2=2`$. So the point goes from $`2`$ up to $`6`$, turns around, goes back down to $`2`$, and then moves forward forever.

---
