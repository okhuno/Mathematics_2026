### Exercise 6. Shifted Ellipse
Reduce

```math
4x^2+9y^2-16x+18y-11=0
```

to canonical form. Give the center and semiaxis lengths. Check that substituting the coordinates of the center into the left-hand side gives a value consistent with the form you obtained.

> **Why this exercise:** reinforces completing the square and recognizing a shift of the coordinate system.

#### Answer
- Canonical form: $`\dfrac{(x-2)^2}{9}+\dfrac{(y+1)^2}{4}=1`$
- Center $`(2,-1)`$, semi-axes $`3`$ (along $`x`$) and $`2`$ (along $`y`$).

![Shifted ellipse](images/curves_ex6_15.png)

#### How I solved it
1. **Group and factor out coefficients:** $`4(x^2-4x)+9(y^2+2y)=11`$.
2. **Complete the squares:** $`x^2-4x=(x-2)^2-4`$ and $`y^2+2y=(y+1)^2-1`$.
3. **Substitute:** $`4[(x-2)^2-4]+9[(y+1)^2-1]=11\Rightarrow4(x-2)^2+9(y+1)^2=11+16+9=36`$.
4. **Divide by 36:** $`\frac{(x-2)^2}{9}+\frac{(y+1)^2}{4}=1`$.

**Check at the center $`(2,-1)`$:** the original left side gives $`4\cdot4+9\cdot1-32-18-11=-36`$. In the form $`4(x-2)^2+9(y+1)^2-36=0`$ the left side at the center is $`0+0-36=-36`$ ✓. They match.

---
