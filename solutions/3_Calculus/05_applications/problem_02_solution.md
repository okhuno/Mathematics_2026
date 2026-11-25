### Problem 2. Maximum Area of a Rectangle
A rectangle has perimeter $`40`$.

1. Write its area as a function of the length of one side.
2. Determine the domain of this function resulting from the geometry of the problem.
3. Find the dimensions that give the maximum area.
4. Justify that the point found actually gives a maximum.

> **Why this problem:** it teaches the complete optimization scheme: model → domain → derivative → verification and interpretation of the maximum.

#### Answer
- $`A(x)=x(20-x)=20x-x^2`$, domain $`0<x<20`$.
- Maximum at $`x=10`$: the rectangle is a $`10\times10`$ square, area $`100`$.

#### How I solved it
1. **Variables:** sides $`x`$ and $`y`$. Perimeter: $`2x+2y=40\Rightarrow y=20-x`$. Area: $`A=xy=x(20-x)=20x-x^2`$.
2. **Domain:** both sides must be positive: $`x>0`$ and $`20-x>0`$, so $`0<x<20`$.
3. **Derivative:** $`A'(x)=20-2x=0\Rightarrow x=10`$, so $`y=10`$. $`A(10)=100`$.
4. **Why it is a maximum:** $`A'>0`$ for $`x<10`$ and $`A'<0`$ for $`x>10`$, so $`A`$ goes up and then down (also $`A''=-2<0`$). Near the ends of the domain, $`A\to0`$, which is smaller than $`100`$.

---
