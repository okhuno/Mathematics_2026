### Problem 10. A Cable Through Water and Land
Point $`A`$ lies on one bank of a river of width $`100`$ m, and point $`B`$ lies on the other bank, $`500`$ m along the bank from the point directly opposite $`A`$.

The cost per meter of cable underwater is twice the cost per meter of cable on land.

Build a cost function depending on the point where the cable comes out of the water, determine the domain, and find the solution that minimizes the cost.

> **Why this problem:** it checks whether the student can independently translate a spatial description and two different costs into a single function to be optimized.

#### Answer
- Let $`x`$ be the distance (in m) along the far bank from the point directly opposite $`A`$ to the point where the cable leaves the water. With $`c`$ = cost per meter on land:

```math
C(x)=c\left[2\sqrt{100^2+x^2}+(500-x)\right],\qquad 0\le x\le500.
```

- Minimum at $`x=\dfrac{100}{\sqrt3}\approx57.7`$ m, with cost $`c\,(500+100\sqrt3)\approx673.2\,c`$.

#### How I solved it
1. **Variables and model:** the underwater part goes from $`A`$ straight across the river and $`x`$ meters along. By Pythagoras its length is $`\sqrt{100^2+x^2}`$ and it costs $`2c`$ per meter. The land part along the bank has length $`500-x`$ and costs $`c`$ per meter.
2. **Domain:** $`0\le x\le500`$.
3. **Derivative** (dividing out the constant $`c`$): $`\dfrac{d}{dx}\left[2\sqrt{10000+x^2}+500-x\right]=\dfrac{2x}{\sqrt{10000+x^2}}-1`$.
4. **Set to zero:** $`2x=\sqrt{10000+x^2}\Rightarrow4x^2=10000+x^2\Rightarrow x^2=\frac{10000}{3}\Rightarrow x=\frac{100}{\sqrt3}\approx57.7`$.
5. **Compare with the ends** (cost in units of $`c`$):
   - $`x=0`$: $`200+500=700`$
   - $`x=57.7`$: $`500+100\sqrt3\approx673.2`$ (the smallest)
   - $`x=500`$: $`2\sqrt{260000}\approx1019.8`$

   So the minimum cost is at $`x\approx57.7`$ m.

---
