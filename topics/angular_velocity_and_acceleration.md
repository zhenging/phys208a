---
tags: [angular velocity, angular acceleration]
page: 273
---

### Angular Velocity And Acceleration

+ Circumference: $C = 2\pi r = \pi d$
+ Arc length: $S = r\th$ ($\th$ has the unit of radian)
+ Period of Oscillation $T$: Time to one complete full Revolution/Oscillation.
+ Frequency $f$ (Hz): number of revolution/scillation occur in a given time.

+ Angular Displacement: $\Delta \th = \Delta \th_f - \Delta \th_i$
+ Angular Velocity $\omega (rad/s)$ , change in $\th$ over time. $\omega_{avg} = \dfrac{\Delta \th}{\Delta t}$
+ Angular Acceleration $a (rad/s^2)$. $a_{avg} = \dfrac{\omega}{\Delta t}$
+ Centripetal acceleration $\vec a_c (m/s^2)$. $\vec a_c = \dfrac{v^2}{r}$
+ Tangential acceleration $\vec a_t (m/s^2)$
Object undergoing circular motion that is **Non-uniform** (speed changes).
+ Linear $\longleftrightarrow$ Rotational Relations in Motion
$$
\begin{aligned}
v &= r\omega \\
\vec a_c &= \frac{v^2}{r} = r\omega^2\\
\omega &= 2\pi f = \frac{2\pi}{T}
\end{aligned}
$$

#### Exerices
(9.14 )A circular saw blade of diameter $0.205 m$ starts from rest. In a time interval of $6.35 s$ it accelerates with constant angular acceleration to an angular velocity of $133 rad/s$. Find the angular acceleration and the angle through which the blade has turned.
>Solution
$$
\begin{aligned}
\alpha &= \frac{\omega_f}{t}\\
&= \frac{133}{6.35} = 20.9 rad/s^2\\
\th &= \frac{1}{2}(\omega_0 + \omega_f) t\\
&= \frac{1}{2}(0 + 133) \cdot 6.35 = 422.3 rad
\end{aligned}
$$

(9.16) At $t=0$ a grinding wheel has an angular velocity of $29.0 rad/s$. It has a constant angular acceleration of $35.0 rad/s^2$ until a circuit breaker trips at time $t = 1.90s$. From then on, it turns through an angle $431 rad$ as it coasts to a stop at constant angular acceleration.
a. Through what total angle did the wheel turn between $t=0$ and the time it stopped?
b. At what time did it stop?
c. What was its acceleration as it slowed down?
>Solution
a. Let the angular displacement from $t=0$ to $t=1.9$ be $\th_1$, and that from $t=1.9$ to stop be $\th_2 = 431rad$. The total angular displacement $\th$ is
$$
\begin{aligned}
\th &= \th_1 + \th_2\\
&= \omega t + \frac{1}{2} \alpha t^2 + \th_2\\
&= 29.0 \cdot 1.9 + \frac{1}{2} \cdot 35.0 \cdot 1.9^2 + 431\\
&= 549rad
\end{aligned}
$$
b. Let the angular acceleration after the breakers trips be $\alpha_2$
$$
\begin{aligned}
\omega_f^2 &= \omega_0^2 + 2\alpha_2 \th_2\\
\omega_f &= 0 rad/s\\
\omega_0 &= 29.0 + 35.0 \cdot 1.9 = 1044 rad/s\\
\To \alpha_2 &= -\frac{\omega_0^2}{2\th_2}\\
&= - 10.6 rad/s^2
\end{aligned}
$$
c. $t_2 = 0 - \frac{\omega_0}{\alpha} = 9.0s$. The total time is $t = t_1 + t_2 = 1.9 + 9 = 10.9s$
