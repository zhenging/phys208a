---
tags: [momentum, conservation of momentum, calculus]
---

### Newton's Second Law in Terms of Momentum
Consider a particle of constant mass $m$. Because $\vec a = \dfrac{d\vec v}{dt}$,
$$
\begin{aligned}
\sum \vec F = m \cdot \frac{d\vec v}{dt} = \frac{d}{dt}(m\vec v)
\end{aligned}
$$
The net force $\sum \vec F$ acting on a particle equals the time rate of change of the product of the particle's mass and velocity. This product is called **momentum**, of the particle:
$$
\begin{aligned}
\vec p &= m\vec v\\
\sum \vec F &= \frac{d\vec p}{dt}
\end{aligned}
$$

### Exercises
8.14 Starting $t=0s$, a horizontal net force $\vec F = (0.275 N/s) \hat i + (-0.460N/s^2)t^2 \hat j$ is applied to a bos that has an initial momentum $p=(-3.10kg \cdot m/s)\hat i + (3.85kg \cdot m/s)\hat j$. What is the momentum of the box at $t = 2.15 s$?
>Solution
$p_x,p_y = -2.46, 2.33 kg \cdot m/s$

8.33 A $15.0 kg$ fish swimming at $1.10 m/s$ suddenly gobbles up a $4.30 kg$ fish that is initially stationary. Neglect any drag effects of the water.
>Solution
Todo

8.16 A $64.5 kg$ astronaut is doing a repair in space on the orbiting space station. She throws a $2.35 kg$ tool away from her at $3.50 m/s$ relative to the space station. Find the speed and direction she begin to move.
>Solution
**Identify**: Conservation of Momentum
**Setup**: Let the mass of the astronaut be $m_1$, and the mass of the tool be $m_2$. Without external force, the total momentum is zero before and after she throws the tool. Let the direction of motion of the astronaut be positive. $v_2=-3.5m/s$
$$
\begin{aligned}
0 &= m_1 v_1 + m_2 v_2\\
\To & v_1 = -\frac{m_2 v_2}{m_1}\\
&= -\frac{2.35 \times (-3.5)}{64.5} \approx 0.128m/s
\end{aligned}
$$
She will move **opposite** to the direction in which she throws the tool.

8.17 The expanding gases that leave the muzzle of a rifle also contribute to the recoil. A $.30$-caliber bullet has mass $0.00720 kg$ and a speed of $601 m/s$ relative to the muzzle when fired from a rifle that has mass $2.80 kg$. The loosely held rifle recoils at a speed of $1.85 m/s$ relative to the earth. Find the momentum of the propellant gases in a coordinate system attached to the earth as they leave the muzzle of the rifle.
>Solution
**Identify**: The rifle, the bullet and the propellant gases are initially at rest, so the total momentum is zero. After the short is fired, the rifle, the bullet and the propellant all gain momentum.
**Set up**: Let $+x$ direction be the bullet's direction.
$$
\begin{aligned}
p_1 &= 0 = p_2 = p_r + p_b + p_g\\
p_r &= m_r v_r = 2.80 \times (-1.85)\\
p_b &= m_b v_b = 0.0072 \times 601\\
p_g &= -p_r - p_b = 0.8528 N/s
\end{aligned}
$$
