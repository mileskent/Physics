The product of a function's widths in the time domain ($\Delta t$) and the frequency domain (spectral width) ($\Delta \nu$) must be greater than ~1
* From the [[Scale Theorem]]: the shorter a [[Pulse]] in time, the broader the spectrum, and vice versa
	$\implies$ Cannot have a short pulse that is monochromatic
* Not inherent to [[Quantum Mechanics]], but to [[Wave]]s

$$
\begin{align}
\Delta t = \frac{1}{f(0)} \int^{\infty}_{-\infty}|f(t)| dt \\
\Delta \omega = \frac{1}{F(0)} \int^{\infty}_{-\infty}|F(t)| dt \\
\end{align}
$$

$$
\begin{align}
\Delta t = \frac{1}{f(0)} \int^{\infty}_{-\infty}|f(t)| dt \equiv
\\
\Delta t \geq \frac{1}{f(0)} \int^{\infty}_{-\infty}f(t)dt \equiv  \\
\Delta t \geq \frac{1}{f(0)} \int^{\infty}_{-\infty}f(t) (\exp(i\omega(0))) dt \equiv \\
\Delta t \geq \frac{F(0)}{f(0)}
\end{align}
$$

$$
\begin{align}
\Delta \omega = \frac{1}{F(0)} \int^{\infty}_{-\infty}|F(\omega)| d\omega \equiv
\\
\Delta \omega \geq \frac{1}{F(0)} \int^{\infty}_{-\infty}F(\omega)d\omega \equiv  \\
\Delta \omega \geq \frac{1}{F(0)} \int^{\infty}_{-\infty}F(\omega) (\exp(i\omega(0))) d\omega \equiv \\
\Delta \omega \geq \frac{2\pi f(0)}{F(0)}
\end{align}
$$

$$
\Delta \omega \Delta t \geq 2\pi \equiv \Delta \nu \Delta t \geq 1
$$

Also:
$$
\Delta \omega_{\text{rms}} \Delta t_{\text{rms}} \geq \frac{1}{2}
$$
