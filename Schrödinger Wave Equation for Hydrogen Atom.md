Getting from the [[Schrödinger Wave Equation]], to a better model than the [[Bohr Model]].
![[Pasted image 20250328001551.png|500]]

The Potential energy of the electron-proton system is electrostatic.
$$
V(r) = - \frac{e^2}{4 \pi \epsilon_{0}r}
$$
Negative means potential is attractive

Transform the [[#Time-dependent Equation]] into spherical coordinates. Also use [[Bohr Model#Bohr Reduced Mass of Electron|reduced mass]] in the equation, because it gives a more accurate result for free.
![[Pasted image 20250327230926.png|500]]

Assume $\psi(r, \theta, \phi) = R(r) f(\theta) g(\phi)$, so it is a separable function. This makes the above equation simplify **a lot**!

###### Azimuthal-angle equation
![[Pasted image 20250327231521.png|400]]
$$
g_{\phi\phi} = -m_{l}^2 g
$$
$$
\text{Solution: } g(\phi) = \exp(\pm im_{l} \phi)
$$
Sines and cosines satisfy this equations, but its convenient to choose the complex exponential.

###### Quantizing $m_l$
Because $\phi$ and $\phi + 2 \pi$ are the same angle, you can set g of each equal and you solve for this:
$$
\exp(\pm 2 \pi im_{l} \phi) = 1
$$
$m_{l}$ must be an integer for this to be true.

###### Polar Equation for H
$$
\frac{1}{\sin \theta} \frac{d}{d \theta} \left( \sin \theta  \frac{\partial f}{\partial \theta} \right) + \left[ l(l + 1) - \frac{m^2_{l}}{\sin^2 \theta} \right]f = 0
$$
See [[Polar-Angle Equation]]

###### Radial Equation for H
$$
\frac{1}{r^2} \frac{d}{dr} \left( r^2 \frac{dR}{dr} \right) + \frac{2\mu}{\hbar^2}
\left[E + \frac{e^2}{4\pi\epsilon_{0}r} - \frac{\hbar^2}{2\mu} \frac{l(l+1)}{r^2}\right] R = 0
$$
See [[Radial Wave Equation]]

###### Complete Hydrogen Wave Functions
$$
\Psi_{nlm_{l}}(r, \theta, \phi, t) = R_{nl}(r) f_{lm_{l}}(\theta) \exp(i(\omega_{n}t \pm m_{l} \phi))
$$
$$
\text{where } \omega_{n} = \frac{E_{n}}{\hbar}, \text{and } n, l, m_{l} \text{ are constrained}
$$
The result is a wave; states have some angular momentum proportional to $m_{l}$.
However, such motion can only be inferred indirectly, so we opt for the spatial wave-function instead, which is a product of the radial wave function $R_{nl}$ and the spherical harmonics $Y_{lm}$:
$$
\Psi_{nlm_{l}}(r, \theta, \phi) = R_{nl}(r) Y_{lm_{l}}(\theta, \phi)
$$
$$
\text{where } n, l, m_{l} \text{ are constrained}
$$
### Quantum Numbers
The 3 quantum numbers:
* $n$ is the principal quantum number
* $l$ is the ortbial angular momentum quantum number
* $m_l$ is the magnetic (azimuthal) quantum number
The constraints of the quantum numbers are as follows:
$$
n, l, m_{l} \in \mathbb{Z}
\quad \quad
n > 0
\quad \quad
l < n
\quad \quad
|m_{l}| \leq l
$$
* Total number of states is $n^2$
* Higher values of $n$ correspond to higher orbits from the nucleus, by a factor of $n$
* $E_{n} = -\frac{E_{0}}{n^2}$, $E_{0} = \frac{\hbar^2}{2\mu a_{0}^2}$
* Energy only depends on $n$, therefore $l$ and $m_l$ can vary while maintaining a constant energy. This means there are a lot of *degenerate* states!

| Orbital Angular Momentum Quantum Number $l$ |     |     |     |     |     |     |     |     |     |
| ------------------------------------------- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **$l$**                                     | 0   | 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   |
| Letter                                      | s   | p   | d   | f   | g   | h   | a   | b   | c   |
A state with $n = 2, l = 1$ is called a $2p$ state


