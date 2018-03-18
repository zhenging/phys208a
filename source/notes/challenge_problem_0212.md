---
tags: [integration, varying acceleration]
---

The acceleration of a particle is given by $a(t) = 2.00m/s^2 + (3.00m/s^3) t$. Find the initial $v_{0}$ such that the particle have the x-coordinate, at $t=4s$ and $t=0s$.
>Solution
$$
\begin{aligned}
v-v_0 &= \int_0^t adt\\
v&= v_0 + \int_0^t (2+3t)dt\\
&= v_0 + 2t + \frac{3}{2}t^2\\
x-x_0 &= \int_0^t vdt\\
x&= x_0 + \int_0^t (v_0 + 2t + \frac{3}{2}t^2)dt\\
&= x_0 + v_0 t + t^2 +\frac{1}{2}t^3\\
x\mid_{t=0} &= x_0 + 0\\
x\mid_{t=4} &= x_0 + 4v_0 + 16 + \frac{1}{2} \cdot 64\\
x\mid_{t=0} &= x\mid_{t=4} \To v_0 = -12m/s
\end{aligned}
$$
