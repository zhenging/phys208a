---
tags: [rotational motion, work, power]
---

### 1004 Work and Power in Rotational Motion
![Graph](../assets/fig_1021.png)
The work $dW$ done by the force $\vec F_{tan}$ while a point on the rim moves a distance $ds$ is $dW = F_{tan}ds$. If $d\th$ is measured in radians, then $ds = R\th$ and
$$
\begin{aligned}
dW &= F_{tan} R d\th \quad &\text{(1)}
\end{aligned}
$$
Now $F_{tan}$ is the torque $\tau$ due to the force $\vec F_{tan}$, so
$$
\begin{aligned}
dW &= \tau d\th \quad &\text{(2)}
\end{aligned}
$$
As the disk rotates from $\th_1$ to $\th_2$, the total work done by the torque is
$$
\begin{aligned}
W &= \int_{\th_1}^{\th_2} \tau d\th \quad &\text{(3)}
\end{aligned}
$$
If the torque remains **constant** while the angle changes, then the work is the product of torque and angular displacement
$$
\begin{aligned}
W &= \tau (\th_2 - \th_1) \quad &\text{(4)}
\end{aligned}
$$
When a torque does work on a rotating rigid body, the kinetic energy changes by an amount equal to the work done. The integrand of Eq.(3) can be transformed into an integrand with respect to $\omega$ as follows:
$$
\begin{aligned}
\tau d\th = (I\alpha)d\th &= I\cdot \frac{d\omega}{dt} \cdot d\th\\
&= I\cdot \frac{d\th}{dt} \cdot d\omega\\
&= I\omega d\omega
\end{aligned}
$$
Eq. (3) then becomes
$$
\begin{aligned}
W_{tot} = \int_{\omega_1}^{\omega_2} I\omega d\omega = \frac{1}{2}I\omega_2^2 - \frac{1}{2}I\omega_1^2 \quad &\text{(5)}
\end{aligned}
$$
When we divide both sides of Eq. (2) by the time interval $dt$ during which the angular displacement occurs, we find
$$
\begin{aligned}
\frac{dW}{dt} &= \tau \cdot \frac{d\th}{dt} = \tau \omega \\
P &= \tau \omega \quad &\text{(6)}
\end{aligned}
$$

#### Exercises
(10.31) A 2.80-kg grinding wheel is in the form of a solid cylinder of radius 0.100 m.
(a) What constant torque will bring it from rest to an angular speed of $1200$ rev/min in 2.5 s?
(b) Through what angle has it turned during that time?
(c) Use Eq. (10.21) to calculate the work done by the torque.
(d) What is the grinding wheel's kinetic energy when it is rotating at $1200$ rev/min? Compare your answer to the result in part (c).
>Solution
a. Let the angular acceleration be $\alpha$
$$
\begin{aligned}
\omega &= \frac{1200 \cdot 2\pi}{60} = 40\pi rad/s\\
\alpha &= \frac{\omega}{2.5} = 16\pi rad/s^2\\
I &= \frac{1}{2}mR^2 = \frac{1}{2}\cdot 2.8 \cdot 0.1^2 = 0.014 kg/m^2\\
\tau &= I\alpha  = 16\pi \cdot 0.014 = 0.704 N\cdot m
\end{aligned}
$$
b. Constant angular acceleration
$$
\begin{aligned}
\Delta \th &= \omega_0 t + \frac{1}{2} \alpha t^2\\
&= 0 + \frac{1}{2} \cdot 16\pi \cdot 2.5^2 = 157.1 rad
\end{aligned}
$$
c. $W = \tau \Delta \th = 0.704 \cdot 157.1 = 110.5 J$
d. $K_{rot} = \frac{1}{2}I\omega^1 = \frac{1}{2} \cdot 0.704 \cdot (40\pi)^2 = 110.5 J$

(10.32) An electric motor consumes 9.00 kJ of electrical energy in 1.00 min. If one-third of this energy goes into heat and other forms of internal energy of the motor, with the rest going to the motor output, how much torque will this engine develop if you run it at 2500 rpm?
>Solution
$$
\begin{aligned}
P &= \frac{9 \cdot 10^3 }{60} \frac{2}{3} = 100 J/s\\
\omega &= \frac{2500 \cdot 2\pi}{60} = \frac{250}{3} \pi rad/s\\
P &= \tau \omega \\
\To \tau &= \frac{P}{\omega} \\
&= \frac{100}{\frac{250}{3} \pi} = 0.38 N\cdot m
\end{aligned}
$$

(10.33a) Compute the torque developed by an industrial motor whose output is 150 kW at an angular speed of 4000 rev/min.
>Solution
$$
\begin{aligned}
P &= 1.5 \cdot 10^5 J/s\\
\omega &= \frac{4000 \cdot 2\pi}{60} = \frac{400}{3} \pi rad/s\\
P &= \tau \omega \\
\To \tau &= \frac{P}{\omega} \\
&= \frac{1.5 \cdot 10^5}{\frac{400}{3} \pi} = 358.1 N\cdot m
\end{aligned}
$$

(10.33b)  A drum with negligible mass, 0.400 m in diameter, is attached to the motor shaft, and the power output of the motor is used to raise a weight hanging from a rope wrapped around the drum. How heavy a weight can the motor lift at constant speed and at what constant speed will the weight rise?
>Solution
???
