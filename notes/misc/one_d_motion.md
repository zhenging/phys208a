---
tags: [displacement-velocity relation, displacement-time relation, constant acceleration, gravity, initial velocity, final velocity, kinematic equation, 1-D motion]
---

### Motion Along a Straright Line
+ Straight-line motion, average and instantaneous x-_velocity_:
$$
\begin{aligned}
v_{av} &= \frac{\Delta x}{\Delta t} = \frac{x_2-x_1}{t_2-t_1}\\
v &= \lim_{\Delta t \to 0} \frac{\Delta x}{\Delta t} = \frac{dx}{dt}
\end{aligned}
$$
+ Average and instantaneous x-_acceleration_:
$$
\begin{aligned}
a_{av} &= \frac{\Delta v}{\Delta t} = \frac{v_2-x_1}{v_2-t_1}\\
a &= \lim_{\Delta t \to 0} \frac{\Delta v}{\Delta t} = \frac{dv}{dt}
\end{aligned}
$$
+ Straight-line motion with _constant acceleration_
When the x-acceleration is constant, four equations relate the position $x$ and the x-velocity $v$ at any time $t$ to the initial position $x_0$, the initial x-velocity $v _{0}$ (both measured at time $t = 0$), and the x-acceleration $a$.
$$
\begin{aligned}
x &= \frac{v_0 + v_f}{2} \cdot t  \qquad
&v_f &= v_0 + a\cdot t\\
x &= v_0 t + \frac{1}{2}at^2 \qquad
&v_f^2 &= v_0^2 + 2a\cdot x
\end{aligned}
$$

#### Exercises
1\. Describe the motion at interval $[t_0, t_6]$.
![Graph 1](../assets/quiz0122_displacement_vs_time_1.PNG)
>Solution
$[t_0, t_2]$, Moving backward at a constant acceleration.
$[t_2, t_4]$, Moving forward at a constant acceleration.
$[t_4, t_6]$, At rest.
$[t_6, )$, Moving forward at a constant accleration.

2\. Grasshopper jumps upward, and reaches a max height of $1m$. Find the total time it is in the air. (up and down).
![Graph 2](../assets/quiz0122_displacement_vs_time_2.PNG)
>Solution
When the grasshopper reaches the max height, $v_f = 0m/s$.
$$
\begin{aligned}
v_f^2 &= v_0^2 + 2ay & a=9.8m/s^2, y=1m\\
0 &=  v_0^2 + 2\cdot9.8\cdot 1 \To v_0 = \sqrt {19.6} m/s
\end{aligned}
$$
When the grasshopper finally hits the ground, $y_f = 0m$
$$
\begin{aligned}
y_f &= v_0 t + \frac{1}{2}at^2 \\
0 &= \sqrt {19.6} t + \frac{1}{2} \cdot 9.8 \cdot t^2\\
\To t &\approx 0.89s
\end{aligned}
$$

3\. An object is thrown upward on a cliff $20m$ from the ground at an intial velocity of $30m/s$. Find the final velocity before it hits the ground.
b. Find how long is the object in the air.
![Graph 3](../assets/quiz0122_throw_upward.PNG)
>Solution
a. According the kinematic equation, $v_f^2 = v_0^2 + 2ay$. We have $v_0=-30m/s, a=9.8m/s^2, y=20m$ (moving downward being positive direction).
$$
\begin{aligned}
v_f^2 &= (-30)^2 + 2\cdot 9.8 \cdot 20\\
\To &v_f = \sqrt {1292} m/s \approx 35.94m/s
\end{aligned}
$$

(Mid Term 1) A stone is thrown outward from the top of a 59.4-m high cliff with an upward velocity component of 19.5m/s. How long is the stone in the air.
![Graph ](../assets/stone_in_air.PNG)
>Solution
$$
\begin{aligned}
y_f - y_0 &= v_0 t + \frac{1}{2} a t^2\\
y_f &= 0m\\
y_0 &= 59.4m\\
a &= -9.8m/s^2\\
v_0 &= 19.5m/s\\
0-59.4 &= 19.5t - \frac{1}{2} \cdot 9.8 t^2\\
\To t &= 6s
\end{aligned}
$$
