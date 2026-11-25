### Problem 3. A Box Made from Cardboard
From a $`30\,\mathrm{cm}\times40\,\mathrm{cm}`$ sheet, squares of side length $`x`$ are cut from the corners and the edges are folded up to form an open box.

Write the volume as a function of $`x`$, determine the physically meaningful domain, and find the value of $`x`$ for which the volume is greatest.

> **Why this problem:** it develops optimization modeling in a situation where the objective function is not given and must be built independently from the geometry.

#### Answer
- $`V(x)=x(40-2x)(30-2x)=4x^3-140x^2+1200x`$, domain $`0<x<15`$.
- Maximum at $`x=\dfrac{35-5\sqrt{13}}{3}\approx5.66`$ cm, with $`V\approx3032`$ cm³.

#### How I solved it
1. **Dimensions of the box:** cutting a square of side $`x`$ from each corner and folding gives height $`x`$, length $`40-2x`$, width $`30-2x`$.
2. **Volume:** $`V=x(40-2x)(30-2x)=x(1200-140x+4x^2)=4x^3-140x^2+1200x`$.
3. **Domain:** $`x>0`$ and the shorter side $`30-2x>0\Rightarrow x<15`$. So $`0<x<15`$.
4. **Derivative:** $`V'=12x^2-280x+1200=0`$. Divide by $`4`$: $`3x^2-70x+300=0`$.
   $`x=\dfrac{70\pm\sqrt{4900-3600}}{6}=\dfrac{70\pm\sqrt{1300}}{6}=\dfrac{35\pm5\sqrt{13}}{3}`$.
   Numerically: $`x\approx5.66`$ or $`x\approx17.68`$. Only $`5.66`$ is in $`(0,15)`$.
5. **Maximum:** $`V''=24x-280`$. At $`x\approx5.66`$: $`V''\approx-144<0`$, so it is a maximum. (Also $`V\to0`$ at both ends of the domain.)
6. **Value:** the box is about $`5.66\times18.69\times28.69`$ cm and $`V\approx3032\ \mathrm{cm}^3`$.

---
