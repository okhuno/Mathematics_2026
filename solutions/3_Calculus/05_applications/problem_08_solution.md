### Problem 8. Number of Requests Handled by a Server
The rate at which requests arrive at a server during the first 5 minutes is described by the function

```math
r(t)=100+20t\quad [\mathrm{requests/min}],\qquad 0\le t\le5.
```

1. Compute the total number of requests that arrived during this time.
2. Compute the average rate of incoming requests over this interval.
3. Compare the average rate with the values $`r(0)`$ and $`r(5)`$.

> **Why this problem:** it shows the integral as summation of a varying rate in an example directly related to computer science.

#### Answer
1. $`750`$ requests.
2. $`150`$ requests/min.
3. $`r(0)=100`$, $`r(5)=200`$, and the average $`150`$ lies between them (exactly in the middle).

#### How I solved it
1. **Total = integral of the rate:** $`\int_0^5(100+20t)dt=\left[100t+10t^2\right]_0^5=500+250=750`$.
2. **Average rate:** total divided by time: $`\frac{750}{5}=150`$.
3. **Compare:** $`r(0)=100`$ and $`r(5)=100+100=200`$. Since $`r`$ is a straight line, the average over the interval is the midpoint of the end values: $`\frac{100+200}{2}=150`$ ✓.

---
