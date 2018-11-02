---
tags: [fluid flow, continuity equation]
---

### 1204 Fluid Flow

#### The Continuity Equation
The mass of a moving fluid doesn't change as it flows. This leads to an important relationshipt called the **continuity equation**.
In steady flow the total mass in the tube is constant, so $dm_1 = dm_2$
$$
\begin{aligned}
dm_1 &= dm_2\\
\rho A_1v_1 dt &= \rho A_2v_2 dt \quad \text{ or }\\
A_1 v_1 &= A_2 v_2
\end{aligned}
$$
The product $Av$ is the _volume flow rate_ $\dfrac{dV}{dt}$, the rate at which volume crosses a section of the tube:
$$
\begin{aligned}
\frac{dV}{dt} &= Av
\end{aligned}
$$
$A$ - Cross-sectional area of flow tube
$v$ - Speed of flow

#### Examples
(12.6) Incompressible oil of density $850 kg/m^3$ is pumped through a cylindrical pipe at a rate of 9.5 liters per second.
(a) The first section of the pipe has a diameter of 8.0 cm. What is the flow speed of the oil? What is the mass flow rate?
(b) The second section of the pipe has a diameter of 4.0 cm. What are the flow speed and mass flow rate in that section?
>Solution
Let the volume flow rate be $\dfrac{dV}{dt} = 0.0095 m^3/s$, and the mass flow rate be $\dfrac{dm}{dt}$. (Part a and part b have the same mass flow rate)
$$
\begin{aligned}
\frac{dm}{dt} &= \rho \cdot \frac{dV}{dt}\\
&= 850 \cdot 0.0095 = 8.075kg
\end{aligned}
$$
According to the _continuity equation_, we have
$$
\begin{aligned}
\frac{dV}{dt} &= Av = \pi \cdot (\frac{d}{2})^2 v\\
\To v &= \frac{dV}{dt} \cdot \frac{4}{\pi d^2}\\
v_a &= 0.0095 \cdot \frac{4}{\pi \cdot 0.08^2} = 1.89 m/s\\
v_b &= 0.0095 \cdot \frac{4}{\pi \cdot 0.04^2} = 7.56 m/s
\end{aligned}
$$

#### Exercises
38

(12.38) Water is flowing in a pipe with a varying cross-sectional area, and at all points the water completely fills the pipe. At point 1 the cross-sectional area of the pipe is $0.070 m^2$, and the magnitude of the fluid velocity is $3.50$ m/s. (a) What is the fluid speed at points in the pipe where the cross-sectional area is (a) $0.105 m^2$ and (b) 0$.047 m^2$? (c) Calculate the volume of water discharged from the open end of the pipe in 1.00 hour.
>Solution
We calculate the volume flow rate $\dfrac{dV}{dt}$ first
$$
\begin{aligned}
\frac{dV}{dt} &= Av = 0.07 \cdot 3.5 = 0.245 m^3/s\\
v_a &= \frac{\frac{dV}{dt}}{0.105} = 2.3 m/s\\
v_b &= \frac{\frac{dV}{dt}}{0.047} = 5.2 m/s\\
V_{total} &= \frac{dV}{dt} \cdot 3600 = 882 m^3
\end{aligned}
$$
