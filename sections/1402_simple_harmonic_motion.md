---
tags: [SHM, simple harmonic motion]
---

### 1402 Simple Harmonic Motion
The force acting on a stretched ideal spring as $F_x = kx$. The x-component of force the spring exerts on the body is the negative of this, so
$$
\begin{aligned}
F_x &= -kx \quad &\text{(1)}
\end{aligned}
$$
where $F_x$ is the restoring force exerted by an ideal spring, $k$ is the force constant of spring and $x$ is the displacement of the spring.
When the restoring force is directly proportional to the displacement from
equilibrium, as given by Eq. (1), the oscillation is called simple harmonic
motion (SHM). The acceleration is
$$
\begin{aligned}
a_x = \frac{d^2 x}{dt^2} = -\frac{k}{m}x \quad &\text{(2)}
\end{aligned}
$$

#### Displacement, Velocity, and Acceleration in SHM
$$
\begin{aligned}
x (t) &= A\cos(\omega t + \phi)  \quad &\text{(3)}
\end{aligned}
$$
We find the velocity $v_x$ and acceleration $a_x$ as functions of time for a harmonic oscillator by taking derivatives of Eq. (3) with respect to time:
$$
\begin{aligned}
v_x &= \frac{dx}{dt} = -A\omega \sin(\omega t + \phi) \\
a_x &= \frac{dv}{dt} = \frac{d^2 x}{dt^2} = -A\omega^2 \cos(\omega t + \phi)
\end{aligned}
$$

#### Exercises
10, 13, 16, 21, 28, 37

(14.10) When a 0.850-kg mass oscillates on an ideal spring, the frequency is 1.95 Hz.
a. What will the frequency be if 0.160 kg are added to the original mass? Try to solve this problem without finding the force constant of the spring.
b. What will the frequency be if 0.160 kg are subtracted from the original mass? Try to solve this problem without finding the force constant of the spring.
>Solution
$$
\begin{aligned}
\omega &= 2\pi f = \sqrt {\frac{k}{m}}\\
\To f &=\frac{1}{2\pi}\sqrt {\frac{k}{m}}\\
f_{new} &= \frac{1}{2\pi}\sqrt {\frac{k}{m_{new}}}\\
&= \frac{1}{2\pi}\sqrt {\frac{k}{m}} \cdot \sqrt{\frac{m}{m_{new}}}\\
&= f \cdot \sqrt{\frac{m}{m_{new}}}\\
f_a &= f\sqrt{\frac{0.85}{0.85+0.16}} = 1.79hz\\
f_b &= f\sqrt{\frac{0.85}{0.85-0.16}} = 2.16hz\\
\end{aligned}
$$

(14.13) A frictionless block of mass 2.05 kg is attached to an ideal spring with force constant 330 N/m . At t=0 the spring is neither stretched nor compressed and the block is moving in the negative direction at a speed of 11.2 m/s.
a. Find the amplitude.
b. Find the phase angle.
c. Write an equation for the position as a function of time.
>Solution
a\. Amplitude
$$
\begin{aligned}
v(0) &= -A\omega \sin(0 + \phi) = -11.2m/s\\
\omega &= \sqrt {\frac{k}{m}} = \sqrt {\frac{330}{2.05}} = 12.69rad/s\\
\end{aligned}
$$
The block has the velocity of maximum magnitude when $t=0$
$$
\begin{aligned}
v(t) &= -A\omega \sin(\omega t + \phi)\\
v(0) &= -A\omega \cdot 1\\
\To A &=\frac{11.2}{12.69} = 0.883m
\end{aligned}
$$
b. Phase angle
$$
\begin{aligned}
x(t) &= A\cos (\omega t + \phi)\\
x(0) &= A\cos (0 + \phi) = 0 \To \phi = \pm \frac{\pi}{2}\\
v(t) &= -A\omega \sin(\omega t + \phi)\\
v(0) & = -A\omega \sin(0 + \phi) = -11.2 \To \sin(\phi) > 0\\
\end{aligned}
$$
Therefore the phase angle $\phi = +\frac{\pi}{2} = 1.57rad$.
c. Equation for position as a function of time
$$
\begin{aligned}
x(t) &= A\cos (\omega t + \phi)\\
x(t) &= 0.883\cos (12.69 t + \frac{\pi}{2})\\
\end{aligned}
$$

(14.16) A small block is attached to an ideal spring and is moving in SHM on a horizontal, frictionless surface. When the amplitude of the motion is 0.090 m, it takes the block 2.43 s to travel from x= 0.090 m to x= -0.090 m.
a. If the amplitude is doubled, to 0.180 m , how long does it take the block to travel from x= 0.180 m to x= -0.180 m?
b. If the amplitude is doubled, to 0.180 m , how long does it take the block to travel from x= 0.090 m to x= -0.090 m ?
>Solution
a. $t=2.43s$
b. $\Delta t = 0.81s = \dfrac{2.43 \times 2}{6}s$

(14.21) A 3.00 kg mass on a spring has displacement as a function of time given by the equation  $x(t)=(7.40cm)cos[(4.16rad/s)t - 2.42rad]$.
a. Find the time for one complete vibration.
b. Find the force constant of the spring.
c. Find the maximum speed of the mass.
d. Find the maximum magnitude of force on the mass.
>Solution
a. Period $T$
$$
\begin{aligned}
\omega &= 4.16 rad/s\\
T &= \frac{2\pi}{\omega}\\
& = \frac{2\pi}{4.16} = 1.51s
\end{aligned}
$$
b. Force constant $k$
$$
\begin{aligned}
\omega &= \sqrt{\frac{k}{m}}\\
\To k &= m\omega^2\\
&= 3.00 \cdot 4.16^2 = 51.9 N/m
\end{aligned}
$$
c. Max magnitude speed
$$
\begin{aligned}
v_{max} &= A\omega\\
&= 0.074 \cdot 4.16 = 0.308m/s
\end{aligned}
$$
d. Maximum magnitude of force
$$
\begin{aligned}
F_{max} &= kA\\
&= 51.9 \cdot 0.074 = 3.84N
\end{aligned}
$$

(14.28) A harmonic oscillator has angular frequency $\omega$ and amplitude $A$.
a. What is the magnitude of the displacement when the elastic potential energy is equal to the kinetic energy? (Assume that $U=0$ at equilibrium.)
b. What is the magnitude of the velocity when the elastic potential energy is equal to the kinetic energy? (Assume that $U=0$ at equilibrium.)
c. At an instant when the displacement is equal to $A/2$, what fraction of the total energy of the system is kinetic?
>Solution
a. $x = \frac{\sqrt 2}{2}A$
b. $v_x = \frac{\sqrt 2}{2}A \omega$
c. $\frac{K}{E} = 0.75$

(14.37) A 175-g glider on a horizontal, frictionless air track is attached to a fixed ideal spring with force constant 155 N/m. At the instant you make measurements on the glider, it is moving at 0.815 m/s and is 3.00 cm from its equilibrium point. Use energy conservation to find (a) the amplitude of the motion and (b) the maximum speed of the glider. (c) What is the angular frequency of the oscillations?
>Solution
Todo
