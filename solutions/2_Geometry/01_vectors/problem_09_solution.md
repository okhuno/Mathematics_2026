### Exercise 9. Cross Product as a Perpendicular Direction
For $`u=(1,2,0)`$ and $`v=(0,1,3)`$ compute $`u\times v`$. Use dot products to check perpendicularity to both vectors, compute $`v\times u`$, and compare the results.

> **Why this exercise:** teaches the geometric meaning of the cross product and the effect of changing the order of its arguments.

#### Answer
- $`u\times v=(6,-3,1)`$
- $`v\times u=(-6,3,-1)`$
- Both are perpendicular to $`u`$ and $`v`$; they are opposites of each other.

#### How I solved it
**Idea:** in 3D, the cross product of two vectors is a **new vector** perpendicular to both.

With $`u=(1,2,0)`$ and $`v=(0,1,3)`$, the formula gives:
- first: $`u_2v_3-u_3v_2=2\cdot3-0\cdot1=6`$
- second: $`u_3v_1-u_1v_3=0\cdot0-1\cdot3=-3`$
- third: $`u_1v_2-u_2v_1=1\cdot1-2\cdot0=1`$

So $`u\times v=(6,-3,1)`$.

**Check perpendicularity (dot products must be $`0`$):**
- with $`u`$: $`6\cdot1+(-3)\cdot2+1\cdot0=0`$ ✓
- with $`v`$: $`6\cdot0+(-3)\cdot1+1\cdot3=0`$ ✓

**Swap the order:** using the same formula with $`u`$ and $`v`$ swapped, every sign flips: $`v\times u=(-6,3,-1)=-(u\times v)`$.

**Comparison:** same length, opposite direction. So the order matters for the cross product (unlike ordinary multiplication of numbers).

---
