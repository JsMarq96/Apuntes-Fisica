## Ecuacion diferencial
$$x'' + 2 \gamma x' + \omega_0^2 x = 0$$
- Frequencia natural $\omega_0 = \sqrt{\frac{k}{m}}$
- Frecuencia de amortiguado $\gamma = \frac{b}{2m}$
- Factor de Calidad: $Q = \frac{\omega_0}{2 \gamma}$

## Casos
### Underdamped $\gamma < \omega_0$
$$ x(t) = A_0 e^{-\gamma t} \cos(\omega t + \phi_0) $$
$$ \omega = \omega_0 \sqrt{1-(\frac{\gamma}{\omega_0})^2} $$
$$ E_m(t) = \frac{1}{2} k A_0^2 e^{-2 \gamma t} \ \ \ E_m(t) = E_0 e^{-2 \gamma t} \ \ E_m = \frac{1}{2} k A^2$$

### Amortiguacion critical $\gamma = \omega_0$
$$ x(t) = (C_1 + C_2) e^{-\gamma t} $$
### Overdamped $\gamma > \omega_0$

$$ \beta = \sqrt{\gamma^2 - \omega_0^2}$$
$$ x(t) = C_1 e^{-(\gamma + \beta)t} + C_2 e^{-(\gamma - \beta)t} $$

