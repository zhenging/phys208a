---
tags: [circuluar motion, centripetal force, normal force, frictionless]
---

### Circular Motion
Important Idea: Any object undergoing circular motion will experience acceleration (**centripetal acceleration** $\vec a_c$ or $\vec a_r$), and by Newton's Second Law, it takes a **Net Force**  to "force" that obect to undergo circular motion. That force is the **centripetal force** ($F_c$ or $F_r$), which is proportional to centripetal acceleration $\vec a_c$.
$$
\vec F_c = m\vec a_c = \frac{mv^2}{R}
$$

#### Circular Basics
+ Circumference: $C = 2\pi r = \pi d$
+ Arc length: $S = r\th $ ($\th$ has the unit of radian)
+ Period of Oscillation $T$: Time to one complete full Revolution/Oscillation.
+ Frequency $f$ (Hz): number of revolution/scillation occur in a given time.

#### Circular Motion Quantities
+ Angular Displacement: $\Delta \th = \Delta \th_f - \Delta \th_i$
+ Angular Velocity $\omega (rad/s)$ , change in $\th$ over time. $\omega_{avg} = \dfrac{\Delta \th}{\Delta t}$
+ Angular Acceleration $a (rad/s^2)$. $a_{avg} = \dfrac{\omega}{\Delta t}$
+ Centripetal acceleration $\vec a_c (m/s^2)$. $\vec a_c = \dfrac{v^2}{r}$
+ Tangential acceleration $\vec a_t (m/s^2)$
Object undergoing circular motion that is **Non-uniform** (speed changes).
+ Linear $\longleftrightarrow	$ Rotational Relations in Motion
$$
\begin{aligned}
v &= r\omega \\
\vec a_c &= \frac{v^2}{r} = r\omega^2\\
\omega &= 2\pi f = \frac{2\pi}{T}
\end{aligned}
$$

#### Exercises
(Mid Term 2) A ball of mass $m$, at the end of a string of length $L$, rotates in a vertical circle just fast enough to prevent the string from going slack at the top of the circle. The speed of the ball at the bottom of the circle is?
![Graph](../assets/mid_term2_circular_motion_1.PNG)
>Solution
Todo
$\sqrt {5gR}$

(Mid Term 2) A ball of mass 8.0kg is suspended by two wired from a horizontal arm, which is attached to a vertical shaft, as show in graph. The shaft is in uniform rotation about its axis such that the linear speed of the ball equals 2.3m/s. The tension in wire 2 is closed to:
>Solution
Todo
66N

(Mid Term 2) A small object slides along the frictionless loop-the-loop with a diameter of 3m. What minimum speed must it have at the top of the loop?
>Solution
Todo
3.8m/s

(Mid Term 2) A ball of mass $m$ is suspended from a rope of length R. The ball is set into freely-swinging circular motion in a vertical plane. The centripetal acceleration of the ball at the top of the circle is $8g$. The centripetal acceleration of the ball at the bottom of the circle is closed to
>Solution
Todo
$12g$

1\. A car is moving along an inclined _frictionless_ circular track. The inclined angle with the horizontal line is $\th = 30\degree$, and the radius of the track is $100$m. Find the velocity $v$, so that the car does not move up or down.
![Graph (1)](../assets/quiz0221_centripetal_force.PNG)
>Solution
$$
\begin{aligned}
\tan \th &= \frac{F_c}{W}\\
\tan 30\degree &= \frac{\frac{mv^2}{R}}{mg}\\
\To v &= \sqrt {gR\tan 30\degree}\\
&= \sqrt {9.8 \times 100 \times \frac{1}{2}} \approx 23.8m/s
\end{aligned}
$$

2\. A car is at the bottom of a circular track with radius of $10$m, and moves along the track.
a. Find the initial velocity $v_0$, so that it just makes over the top.
![Graph (2a)](../assets/quiz0307_car_on_circular_track_a.PNG)
>Solution
At the top of the track, the centripetal force is provided solely by the car's weight and the normal force is zero. Let the centripetal force be $F_c$, the weight of the car be $w$, and the normal be $F_N$.
1\. According to Newton's Second Law
$$
\begin{aligned}
F_c &= \frac{mv_f^2}{R} = w - F_N\\
w &= mg\\
F_N &= 0\\
\To v_f &= \sqrt {gR}
\end{aligned}
$$
2\. By Conservation of Energy
$$
\begin{aligned}
\frac{1}{2}mv_0^2 &= \frac{1}{2}mv_f^2 + mg\cdot 2R\\
\frac{1}{2}mv_0^2 &= \frac{1}{2}m \cdot (\sqrt{gR})^2 + mg\cdot 2R\\
\To v_0 &= \sqrt {5gR} \approx 22.14m/s
\end{aligned}
$$

b. At what height above ground does car leave track, if $v_0$ is 20% less than the initial velocity from part (a).
![Graph (2b)](../assets/quiz0307_car_on_circular_track_b.PNG)
>Solution
In this case, $v_0 = 0.8\sqrt {gR}$.
Whent the car leaves the track, the normal force is zero.
$$
\begin{aligned}
F_c &= \frac{mv_f^2}{R} = w\cos \th - F_N\\
w &= mg\\
F_N &= 0\\
\To v_f &= \sqrt {gR \cos \th}
\end{aligned}
$$
2\. By Conservation of Energy, the height of the car is $y_f = R(1+\cos \th)$
$$
\begin{aligned}
\frac{1}{2}mv_0^2 &= \frac{1}{2}mv_f^2 + mg\cdot y_f\\
\frac{1}{2}m(0.8\sqrt{gR})^2 &= \frac{1}{2}m \cdot (\sqrt{gR \cos \th})^2 + mgR(1+\cos \th)\\
\To \cos \th &= 0.4\\
y_f &= R(1+\cos \th) &\\
&= 10\cdot (1+0.4) = 14m
\end{aligned}
$$
The height of the car is $14$m.
