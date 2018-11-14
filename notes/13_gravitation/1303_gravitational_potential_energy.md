---
tags: [gravitational potential energy]
---

### 1303 Gravitational Potential Energy
For problems in which a body can be far from the earth's surface, we need a more general expression for gravitational potential energy.
![Graph](../assets/fig_1310.png)
The work $W_{grav}$ done by the gravitational force when the body moves directly away from the center of the earth from $r_1$ to $r_2$ is given by
$$
\begin{aligned}
W_{grav} = \int_{r_1}^{r_2} F_r dr \quad &\text{(1)}
\end{aligned}
$$
$F_r$ is opposite to the moving direction of the object, so $F_r$ is negative
$$
\begin{aligned}
F_r = -\frac{GM_Em}{r^2} \quad &\text{(2)}
\end{aligned}
$$
Substituting Eq. (2) into Eq. (1), we have
$$
\begin{aligned}
W_{grav} &= -GM_Em \int_{r_1}^{r_2} \frac{dr}{r^2} \quad &\text{(3)}\\
&= \frac{GM_Em}{r_2} - \frac{GM_Em}{r_1}
\end{aligned}
$$
We now define the corresponding potential energy $U$, so that $W_{grav} = U_1 - U_2$. Comparing with Eq. (3), we see that the appropriate definition for **gravitational potential energy** is
$$
\begin{aligned}
U = -\frac{GM_Em}{r}\quad &\text{(4)}
\end{aligned}
$$

#### More on Gravitational potential energy
When we are close to the earth's surface, in the denominator we may replace $r_1$ and $r_2$ by the radius of Earth $R_E$, so
$$
\begin{aligned}
W_{grav} &= GM_Em \cdot \frac{r_1-r_2}{r_1 r_2} \\
&= GM_Em \cdot \frac{r_1-r_2}{R_E^2}
\end{aligned}
$$
$g = \frac{GM_E}{R_E^2}$, therefore
$$
\begin{aligned}
W_{grav} = mg(r_1 - r_2)
\end{aligned}
$$

#### Examples
(13.5) In Jules Verne's 1865 story with this title, three men went to the moon in a shell fired from a giant cannon sunk in the earth in Florida.
(a) Find the minimum muzzle speed needed to shoot a shell straight up to a height above the earth equal to the earth’s radius $R_E$.
(b) Find the minimum muzzle speed that would allow a shell to escape from the earth completely (the escape speed). Neglect air resistance, the earth's rotation, and the gravitational pull of the moon.
![Graph](../assets/ex_1305.png)
>Solution
a. By energy convervation equation, we have
$$
\begin{aligned}
k_1 + U_1 &= k_2 + U_2\\
\frac{1}{2}mv^2 + (- \frac{GM_E}{R_E}) &= 0 + (- \frac{GM_E}{2R_E})\\
\To v &= \sqrt{\frac{GM_E}{R_E}}\\
&= \sqrt{\frac{G \cdot 5.97 \cdot 10^{24}}{6.37 \cdot 10^6}}\\
&= 7910m/s
\end{aligned}
$$
b. Now $r_2 = \infty$, so $U_2 = 0$
$$
\begin{aligned}
\frac{1}{2}mv^2 + (- \frac{GM_E}{R_E}) &= 0 + 0\\
\To v &= \frac{2GM_E}{R_E}\\
&= \sqrt{\frac{2G \cdot 5.97 \cdot 10^{24}}{6.37 \cdot 10^6}}\\
&= 1.12 \times 10^4m/s
\end{aligned}
$$

#### Exercises
16, 17, 18, 19

(13.16) **Volcanoes on Io**. Jupiter's moon Io has active volcanoes (in fact, it is the most volcanically active body in the solarsystem) that eject material as high as 500 km (or even higher) above the surface. Io has a mass of $8.93 \times 10^{22}$ kg and a radius of 1821 km. For this calculation, ignore any variation in gravity over the 500-km range of the debris. How high would this material go on earth if it were ejected with the same speed as on Io?
>Solution
Todo

(13.17) Use the results of Example 13.5 (Section 13.3) to calculate the escape speed for a spacecraft (a) from the surface of Mars and (b) from the surface of Jupiter. Use the data in Appendix F. (c) Why is the escape speed for a spacecraft independent of the spacecraft's mass?
>Solution
From example 13.5
$$
\begin{aligned}
v_{esc} &= \sqrt{\frac{2GM_{planet}}{R_{planet}}}\\
v_{Mars} &= \sqrt{\frac{2G \cdot 6.42 \cdot 10^{23}}{3.39 \cdot 10^6}}\\
&= 5026m/s\\
v_{Jupiter} &= \sqrt{\frac{2G \cdot 1.90 \cdot 10^{27}}{6.99 \cdot 10^7}}\\
&= 60210m/s\\
\end{aligned}
$$

(13.18) Ten days after it was launched toward Mars in December 1998, the Mars Climate Orbiter spacecraft (mass 629 kg) was $2.87 \times 10^6$km from the earth and traveling at $1.20 \times 10^4$km/h relative to the earth. At this time, what were (a) the spacecraft's kinetic energy relative to the earth and (b) the potential energy of the earth–spacecraft system?
>Solution
Todo

(13.19) A planet orbiting a distant star has radius $3.24 \times 10^6$ m. The escape speed for an object launched from this planet's surface is $7.65 \times 10^3$ m/s. What is the acceleration due to gravity at the surface of the planet?
>Solution
$$
\begin{aligned}
v_{esc} &= \sqrt{\frac{GM}{R}} \text{ and } g = \frac{GM}{R^2}\\
\To g &= \frac{v_{esc}^2}{2R}\\
&= \frac{(7.65 \cdot 10^3)^2}{2\cdot 3.24 \cdot 10^6} = 9.03m/s^2
\end{aligned}
$$
