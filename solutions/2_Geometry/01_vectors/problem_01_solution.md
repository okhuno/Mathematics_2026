### Exercise 1. Vector Operations and Their Meaning
For $`u=(2,-1,3)`$ and $`v=(-1,4,2)`$ compute

```math
u+v,\qquad u-v,\qquad 3u-2v.
```

Then verify that $`(u+v)-v=u`$, and explain geometrically what adding two vectors means.

> **Why this exercise:** reinforces basic operations and immediately connects them with their geometric meaning.

#### Answer
- $`u+v=(1,3,5)`$
- $`u-v=(3,-5,1)`$
- $`3u-2v=(8,-11,5)`$
- $`(u+v)-v=(2,-1,3)=u`$ ✓

#### How I solved it
**Idea:** work on each position separately: first numbers with first numbers, and so on.

- $`u+v=(2+(-1),\ -1+4,\ 3+2)=(1,3,5)`$
- $`u-v=(2-(-1),\ -1-4,\ 3-2)=(3,-5,1)`$
- For $`3u-2v`$, first multiply: $`3u=(6,-3,9)`$ and $`2v=(-2,8,4)`$. Then subtract: $`(6+2,\ -3-8,\ 9-4)=(8,-11,5)`$.
- Check: $`(1,3,5)-(-1,4,2)=(2,-1,3)`$, which is $`u`$. We added $`v`$ and took it away again, so we are back at the start.

**Geometric meaning of addition:** draw $`u`$. From the tip of $`u`$, draw $`v`$. The arrow from the start of $`u`$ to the tip of $`v`$ is $`u+v`$. It is like walking: first along $`u`$, then along $`v`$. The sum is the straight path from where you began to where you ended.

---
