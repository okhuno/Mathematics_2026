### Problem 11. Volume of a Solid of Revolution
The region under the graph

```math
y=\sqrt{x},\qquad x\in[0,4],
```

is rotated about the $`x`$-axis.

1. Construct the integral describing the volume using the disk method.
2. Compute the volume.
3. Explain where the factor $`\pi y^2`$ in the integral comes from.

> **Why this problem:** it teaches how to construct an integral from the geometry of cross-sections instead of applying a volume formula without understanding its origin.

#### Answer

```math
V=\pi\int_0^4(\sqrt x)^2\,dx=8\pi\approx25.13
```

#### How I solved it
1. **Setup:** $`V=\pi\int_0^4(\sqrt x)^2dx=\pi\int_0^4x\,dx`$.
2. **Compute:** $`\pi\left[\frac{x^2}{2}\right]_0^4=\pi\cdot\frac{16}{2}=8\pi`$.
3. **Origin of $`\pi y^2`$:** slice the solid with thin planes perpendicular to the $`x`$-axis. Each slice is a thin disk (a coin) with radius $`y=\sqrt x`$ and thickness $`dx`$. Its volume is (area of a circle) × (thickness) $`=\pi y^2\,dx`$. The integral adds up all these thin disks.

---
