### Exercise 13. Intersection of a Sphere and a Plane
Given the sphere

```math
x^2+y^2+z^2=25
```

and the plane $`z=3`$, find the equation of the intersection curve and its radius. Then describe what happens for $`z=c`$ depending on $`c`$.

> **Why this exercise:** connects a surface equation with the geometry of its intersection.

#### Answer
- Intersection: $`x^2+y^2=16`$ at height $`z=3`$ — a circle of radius $`4`$ with center $`(0,0,3)`$.
- For $`z=c`$: circle of radius $`\sqrt{25-c^2}`$ if $`|c|<5`$; a single point if $`|c|=5`$; empty if $`|c|>5`$.

#### How I solved it
Substitute $`z=3`$ into the sphere: $`x^2+y^2+9=25`$, so $`x^2+y^2=16`$, a circle of radius $`\sqrt{16}=4`$.
For a general height: $`x^2+y^2=25-c^2`$. A circle needs $`25-c^2>0`$, i.e. $`|c|<5`$. If $`c=\pm5`$ we get $`x^2+y^2=0`$: just the north or south pole. If $`|c|>5`$ the plane misses the sphere.

---
