---
tags: [Newton's Second Law, frictionless, incline]
---

1\. **Frictionless** incline. Force $F$ is applied upon mass $m=10kg$.
![Graph 1](../assets/frictionless_incline.PNG)
a). Find $F$, so that $m$ moves up along the incline at constant velocity.
b). Find $F_N$ (Normal Force).
>Solution
a. Constant velocity indicates **zero** acceleration.
$$
\begin{aligned}
\sum F_x &= F_x - W_x = 0\\
F_x &= F\cos \th\\
W_x &= mg\sin \th\\
\To F &= \frac{mg \sin \th}{\cos\th} = \frac{10*9.8*\sin 30^{\circ}}{\cos 30^{\circ}} \approx 57.7 N
\end{aligned}
$$
b. In $y$-direction, the net force is zero too.
$$
\begin{aligned}
\sum F_y &= F_N - W_y - F_y = 0\\
W_y &= mg\cos \th\\
F_y &= F\sin\th\\
\To F_N &= mg\cos \th + F\sin \th\\
& = 10*9.8*\cos 30^{\circ} + 57.7 \sin 30^{\circ} \approx 115.5N
\end{aligned}
$$

2\. Find maximum velocity $v$ before mass breaks loose and slides sideways.
![Graph 2](../assets/quiz0226_circular_track.PNG)
>Solution
Normal force $F_N$
Static Friction $F_s = F_N \cdot u_s$
Centripetal Force $F_c = \dfrac{mv^2}{R}$
According to the diagram, we have
$$
\begin{aligned}
mg &= F_N \cos \th - F_s\sin th\\
&= F_N (\cos \th - u_k\sin th)\\
\To & F_N=\frac{mg}{\cos \th - u_k\sin th} &\text{Eq 1}\\
F_c &= F_N \sin \th + F_s \cos \th\\
&= F_N (\sin \th + u_k \cos \th) \\
&= \frac{mg}{\cos \th - u_k\sin \th} \cdot (\sin \th + u_k \cos \th)\\
F_c &= \frac{mv^2}{R}\\
\To &v = \sqrt {\frac{gR(\sin \th + u_k \cos \th)}{\cos \th - u_k\sin \th}}\\
&= \sqrt {\frac{9.8\cdot 100 \cdot (\sin 30^\degree + 0.4 \cdot \cos 30^\degree)}{\cos 30^\degree - 0.4\cdot \sin 30^\degree}} \approx 35.29m/s
\end{aligned}
$$
