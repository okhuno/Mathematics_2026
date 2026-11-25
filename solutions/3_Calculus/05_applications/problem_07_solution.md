### Problem 7. Exponential Growth
Assume the model

```math
N(t)=N_0e^{kt},\qquad k>0.
```

1. Verify by differentiation that the model satisfies the relation $`N'(t)=kN(t)`$.
2. Find the population doubling time.
3. Explain why the doubling time does not depend on $`N_0`$.

> **Why this problem:** it shows the connection between the exponential function and a growth rate proportional to the current value, without introducing a separate technique for solving differential equations.

#### Answer
1. $`N'(t)=kN_0e^{kt}=kN(t)`$ ✓
2. Doubling time $`T=\dfrac{\ln2}{k}`$.
3. $`N_0`$ cancels out of the equation.

#### How I solved it
1. **Chain rule:** $`N'(t)=N_0\cdot e^{kt}\cdot k=k\cdot N_0e^{kt}=kN(t)`$. So the growth rate is proportional to the current size.
2. **Doubling:** we want $`N(T)=2N_0`$: $`N_0e^{kT}=2N_0\Rightarrow e^{kT}=2\Rightarrow kT=\ln2\Rightarrow T=\frac{\ln2}{k}`$.
3. **Why independent of $`N_0`$:** it cancels from both sides in step 2. Doubling means multiplying by $`2`$, and the growth factor $`e^{kT}`$ is the same no matter what the starting size is.

---
