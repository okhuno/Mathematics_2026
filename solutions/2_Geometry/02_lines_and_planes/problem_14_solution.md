### Exercise 14. Contrast: Intersection and Parallelism
From the point $`P=(0,0,1)`$, two lines are drawn with direction vectors

```math
v_1=(2,1,-1),\qquad v_2=(2,1,0).
```

For each line, analyze its position relative to the plane $`z=0`$.

For the line that intersects the plane, find the intersection point. For the other line, explain how you can recognize parallelism without solving an equation.

> **Why this exercise:** compares two very similar data sets that lead to different outcomes and forces recognition of the geometric condition before calculation.

#### Answer
- Line 1 ($`v_1`$) **intersects** the plane at $`(2,1,0)`$.
- Line 2 ($`v_2`$) is **parallel** to the plane (no common points).

#### How I solved it
- The plane $`z=0`$ has normal $`n=(0,0,1)`$.
- $`v_1\cdot n=-1\neq0`$: the line is not parallel, so it crosses the plane.
- $`v_2\cdot n=0`$: the line is parallel to the plane. Since $`P=(0,0,1)`$ is at height $`1`$ (not on the plane), the line never touches the plane.

**Intersection for line 1:** points are $`(2t,\ t,\ 1-t)`$. We need $`z=0`$: $`1-t=0\Rightarrow t=1`$, giving $`(2,1,0)`$.

**Recognizing parallelism without solving:** the direction $`v_2`$ has third coordinate $`0`$, so moving along the line never changes the height. The line stays at height $`z=1`$ forever and can never reach $`z=0`$.

---
