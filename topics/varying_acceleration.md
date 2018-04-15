---
tags: [calculus, varying acceleration, velocity and position integration]
---

### Straight-line motion with varying acceleration
When the acceleration is not constant but is a known function of time, we can find the velocity and position as functions of time by integrating the acceleration function.
$$
\begin{aligned}
v_x &= v_{0x} + \int_0^t a_x dt\\
x_x &= x_0 + \int_0^t v_x dt
\end{aligned}
$$

#### Exercises
(2.50) A small object moves along the x-axis with acceleration $a(t) = -(0.0320m/s^3)(15.0s-t)$. At $t = 0$ the object is at $x_0 = -14.0 m$ and has velocity $v_0 = 4.50 m/s$. What is the x-coordinate of the object when t = 10.0 s?
>Solution
_Identify_: Motion with varying acceleration. (Integration)
_Setup and Execute_:
$$
\begin{aligned}
v(t) & = v_0 + \int a(t) dt\\
&= 4.5 + \int (-0.48+0.032t) dt\\
&= 0.016t^2 -0.48t + 4.5\\
x(t) &= x_0 + \int_0^t vdt\\
&= -14.0 + \int_0^t (0.016t^2 -0.48t + 4.5)dt\\
&= \frac{0.016}{3}t^3 -0.24t^2 + 4.5t - 14.0\\
x(10.0) &= \frac{0.016}{3}(10)^3 -0.24 \cdot (10)^2 + 4.5 \cdot 10 - 14.0\\
&= \frac{37}{3} \approx 12.3m
\end{aligned}
$$

The acceleration of a particle is given by $a(t) = 2.00m/s^2 + (3.00m/s^3) t$. Find the initial $v_{0}$ such that the particle have the x-coordinate, at $t=4s$ and $t=0s$.
>Solution
$$
\begin{aligned}
v(t) &= v_0 + \int_0^t adt\\
&= v_0 + \int_0^t (2+3t)dt\\
&= v_0 + 2t + \frac{3}{2}t^2\\
x(t) &= x_0 + \int_0^t vdt\\
&= x_0 + \int_0^t (v_0 + 2t + \frac{3}{2}t^2)dt\\
&= x_0 + v_0 t + t^2 +\frac{1}{2}t^3\\
x(0) &= x(t)\\
x_0 + 0 &= x_0 + 4v_0 + 16 + \frac{1}{2} \cdot 64\\
\To v_0 &= -12m/s
\end{aligned}
$$
