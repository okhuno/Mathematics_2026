### Problem 7. A Trigonometric Function
On $`[0,2\pi]`$, find the intervals of monotonicity and the extrema of

```math
f(x)=\sin x+\cos x.
```

Include the endpoints of the interval and compare the function values at the critical points and at the endpoints.

> **Why this problem:** it practices the analysis of a periodic function on a bounded interval.

#### Answer
- Critical points: $`x=\frac\pi4`$ and $`x=\frac{5\pi}4`$.
- Increasing on $`[0,\frac\pi4]`$ and $`[\frac{5\pi}4,2\pi]`$; decreasing on $`[\frac\pi4,\frac{5\pi}4]`$.
- Values: $`f(0)=1`$, $`f(\frac\pi4)=\sqrt2`$, $`f(\frac{5\pi}4)=-\sqrt2`$, $`f(2\pi)=1`$.
- Global maximum $`\sqrt2`$ at $`\frac\pi4`$; global minimum $`-\sqrt2`$ at $`\frac{5\pi}4`$.

#### How I solved it
1. **Derivative:** $`f'(x)=\cos x-\sin x`$.
2. **Critical points:** $`\cos x=\sin x\Rightarrow\tan x=1\Rightarrow x=\frac\pi4,\ \frac{5\pi}4`$ in $`[0,2\pi]`$.
3. **Sign (test points):** $`x=0`$: $`\cos0-\sin0=1>0`$. $`x=\frac\pi2`$: $`0-1=-1<0`$. $`x=\frac{3\pi}2`$: $`0-(-1)=1>0`$.
4. **Values:**
   - $`f(0)=0+1=1`$
   - $`f(\frac\pi4)=\frac{\sqrt2}2+\frac{\sqrt2}2=\sqrt2`$
   - $`f(\frac{5\pi}4)=-\frac{\sqrt2}2-\frac{\sqrt2}2=-\sqrt2`$
   - $`f(2\pi)=1`$
5. **Compare:** the largest value is $`\sqrt2`$ (at $`\frac\pi4`$), the smallest $`-\sqrt2`$ (at $`\frac{5\pi}4`$). The endpoint value $`1`$ lies in between, so the endpoints are not extreme values.

(Another way to see it: $`\sin x+\cos x=\sqrt2\sin\!\left(x+\frac\pi4\right)`$, a sine wave with amplitude $`\sqrt2`$.)

---
