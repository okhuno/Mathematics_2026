### Problem 12. Complete Model and Computer Verification
A museum wants to create a rectangular exhibition room next to an existing straight wall. The side along the wall does not need to be built. The remaining three sides are to be constructed to two different standards: the two sides perpendicular to the wall cost $`300\ \mathrm{PLN/m}`$ each, while the side parallel to the wall costs $`500\ \mathrm{PLN/m}`$. The budget is $`30\,000\ \mathrm{PLN}`$.

Build a model that maximizes the area of the room and prepare a complete analysis containing:

- definition of variables and units,
- mathematical model,
- domain resulting from the problem statement,
- computation of the derivative,
- determination and verification of the optimum,
- interpretation of the result,
- graph of the objective function,
- numerical verification of several values near the optimum found.

Finally, indicate which part of the solution required modeling the problem and which part was only the execution of the calculation. Produce the graph and computer calculations only after completing the mathematical solution, and treat them as verification.

> **Why this problem:** it checks full transfer to a new problem with unequal side costs and integrates the process from model construction to independent verification.

#### Answer
- The room should be $`w=25`$ m (perpendicular to the wall) by $`L=30`$ m (parallel to the wall).
- Maximum area: $`750\ \mathrm{m}^2`$, using the full budget of $`30\,000`$ PLN.

#### How I solved it

**1. Variables and units**
- $`w`$ = length of each side perpendicular to the wall (m)
- $`L`$ = length of the side parallel to the wall (m)
- $`A`$ = area (m²), cost in PLN

**2. Mathematical model**
- Objective: maximize $`A=L\cdot w`$.
- Budget constraint (we use the whole budget to get the largest area): $`2\cdot300\,w+500\,L=30000\Rightarrow600w+500L=30000`$.
- Eliminate $`L`$: $`L=\dfrac{30000-600w}{500}=60-1.2w`$.
- Objective as a function of one variable:

```math
A(w)=w(60-1.2w)=60w-1.2w^2.
```

**3. Domain:** $`w>0`$ and $`L>0`$, so $`60-1.2w>0\Rightarrow w<50`$. Domain: $`0<w<50`$.

**4. Derivative:** $`A'(w)=60-2.4w`$.

**5. Optimum:** $`A'(w)=0\Rightarrow w=25`$. Then $`L=60-1.2\cdot25=30`$, and $`A=25\cdot30=750`$.
**Verification:** $`A'>0`$ for $`w<25`$ and $`A'<0`$ for $`w>25`$, and $`A''=-2.4<0`$, so it is a maximum. Also $`A\to0`$ at both ends of the domain. **Budget check:** $`600\cdot25+500\cdot30=15000+15000=30000`$ ✓.

**6. Interpretation:** the best room is $`25\ \mathrm{m}\times30\ \mathrm{m}`$ with area $`750\ \mathrm{m}^2`$. Interesting detail: the cost is split evenly, $`15\,000`$ PLN on the two side walls and $`15\,000`$ PLN on the front wall.

**7. Graph of the objective function** (made after the solution, as verification):

![A(w)](images/app_p12.png)

**8. Numerical verification near the optimum**

| $`w`$ (m) | $`L=60-1.2w`$ (m) | $`A=wL`$ (m²) |
|---|---|---|
| $`24`$ | $`31.2`$ | $`748.8`$ |
| $`24.5`$ | $`30.6`$ | $`749.7`$ |
| **$`25`$** | **$`30`$** | **$`750`$** |
| $`25.5`$ | $`29.4`$ | $`749.7`$ |
| $`26`$ | $`28.8`$ | $`748.8`$ |

The area is largest at $`w=25`$ and symmetric around it, as expected for a parabola.

**What was modeling and what was execution:**
- **Modeling (the thinking):** choosing the variables, recognizing that the wall side costs nothing, writing the budget constraint with the two different prices, deciding to spend the whole budget, eliminating $`L`$, and finding the domain.
- **Execution (the calculation):** differentiating $`60w-1.2w^2`$, solving $`60-2.4w=0`$, and plugging in values.
- **Graph and numerical table:** verification only.
