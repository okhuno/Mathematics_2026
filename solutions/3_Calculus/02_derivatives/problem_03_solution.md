### Problem 3. The Product Rule — Why Is It Needed?
For

```math
f(x)=(x^2+1)e^x
```

compute the derivative. Then compare the correct result with the incorrect idea

```math
f'(x)\stackrel{?}{=}(2x)e^x
```

and explain which term is missing.

> **Why this problem:** it teaches the product rule by analyzing a common mistake.

#### Answer

```math
f'(x)=e^x(x+1)^2
```

The incorrect idea is missing the term $`(x^2+1)e^x`$.

#### How I solved it
**Product rule:** $`(uv)'=u'v+uv'`$ with $`u=x^2+1`$, $`v=e^x`$.

```math
f'(x)=2x\cdot e^x+(x^2+1)\cdot e^x=e^x(x^2+2x+1)=e^x(x+1)^2.
```

**The mistake:** $`(2x)e^x`$ is only $`u'v`$: it differentiates the first factor and forgets that the second factor $`e^x`$ also changes. The missing term is $`uv'=(x^2+1)e^x`$. The derivative of a product is **not** the product of the derivatives.

---
