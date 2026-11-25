### Problem 5. Distance from Velocity
The velocity of a car during the first five seconds is described by the function

```math
v(t)=4t+2\quad [\mathrm{m/s}].
```

Compute the distance traveled and explain why the integral of velocity gives the change in position.

Then answer what would have to be changed in the reasoning if the velocity also took negative values.

> **Why this problem:** it connects the integral with accumulation and distinguishes displacement from the actual distance traveled.

#### Answer

```math
\int_0^5(4t+2)\,dt=60\ \text{m}
```

#### How I solved it

```math
\int_0^5(4t+2)dt=\left[2t^2+2t\right]_0^5=50+10=60.
```

**Why the integral gives the change in position:** velocity is the derivative of position, $`s'(t)=v(t)`$. By the fundamental theorem, $`\int_0^5v\,dt=s(5)-s(0)`$, the change in position. Another view: in a tiny time $`dt`$ the car moves about $`v\cdot dt`$, and the integral adds all these tiny pieces.

**If the velocity were negative sometimes:** $`\int v\,dt`$ would give the **net displacement** (backward motion counts negatively). The **total distance traveled** would be $`\int|v|\,dt`$: we would split the interval where $`v`$ changes sign and add the absolute values of the pieces.

---
