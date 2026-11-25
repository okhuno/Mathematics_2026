### Exercise 1. Recognizing Curves from Canonical Form
Recognize the curves

```math
x^2+y^2=9,
```

```math
\frac{x^2}{16}+\frac{y^2}{9}=1,
```

```math
y^2=8x,
```

```math
\frac{x^2}{9}-\frac{y^2}{4}=1.
```

For each one, identify the most important features and make a sketch. Explain which parts of the equation let you recognize the type of curve.

> **Why this exercise:** builds the basic dictionary: canonical equation → type of curve → shape and scale.

#### Answer
| Equation | Curve | Key features |
|---|---|---|
| $`x^2+y^2=9`$ | Circle | center $`(0,0)`$, radius $`3`$ |
| $`\frac{x^2}{16}+\frac{y^2}{9}=1`$ | Ellipse | semi-axes $`4`$ (along $`x`$) and $`3`$ (along $`y`$); vertices $`(\pm4,0)`$, $`(0,\pm3)`$ |
| $`y^2=8x`$ | Parabola | vertex $`(0,0)`$, opens to the right, focus $`(2,0)`$ |
| $`\frac{x^2}{9}-\frac{y^2}{4}=1`$ | Hyperbola | vertices $`(\pm3,0)`$, asymptotes $`y=\pm\frac23x`$, two branches (left and right) |

![Curves of Exercise 1](images/curves_ex1.png)

#### How I solved it
- **Circle:** $`x^2+y^2=r^2`$ with $`r^2=9`$, so $`r=3`$.
- **Ellipse:** compare with $`\frac{x^2}{a^2}+\frac{y^2}{b^2}=1`$: $`a^2=16\Rightarrow a=4`$, $`b^2=9\Rightarrow b=3`$. Setting $`y=0`$ gives $`x=\pm4`$; setting $`x=0`$ gives $`y=\pm3`$.
- **Parabola:** compare with $`y^2=4px`$: $`4p=8`$, so $`p=2`$. The focus is $`(p,0)=(2,0)`$. Since $`x=y^2/8\ge0`$, the curve opens to the right.
- **Hyperbola:** $`a^2=9`$, $`b^2=4`$. Setting $`y=0`$ gives $`x=\pm3`$ (vertices). Setting $`x=0`$ gives $`y^2=-4`$, impossible, so the curve never crosses the $`y`$-axis. The asymptotes come from replacing the $`1`$ with $`0`$: $`\frac{x^2}{9}-\frac{y^2}{4}=0\Rightarrow y=\pm\frac23x`$.

**What lets us recognize the type:** same coefficients on $`x^2,y^2`$ means circle; a plus sign with different denominators means ellipse; only one squared variable means parabola; a minus sign between the squares means hyperbola.

---
