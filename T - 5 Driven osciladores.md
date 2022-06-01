## Ecuaciones diferencian no-homgeneas
La solcuieon es la suma de una ecuacion homogenea y una so;ucion partuclar

- Homogeneas: $f(x,x',x'') = 0$
- No-Homogeneas $f(x,x',x'') = f(t)$

$$ x(t) = x_h(t)+x_p(t)$$

# Casos:
## Fuerza constante
$$ mx'' + kx = F_0$$$$ x'' + \omega_0^2 x = \frac{F_0}{m}$$
$$ x(t) = A \cos(\omega_0 t + \phi_0) + \frac{F_0}{m \omega_0}
$$
Es igual de forma pero con el pto de equilibrio cambiado

## Fuerza no Constante
$$ x'' + \omega_0^2 = \frac{F_0}{m} \cos(\omega_f t)$$
$$ C = \frac{F_0}{m(\omega_0^2 - \omega_f^2)} $$
$$x(t) = A \cos(\omega_0t + \phi_0) + C \cos(\omega_f t) $$

Y si el en t=0 es el pto de equilibrio es 0, es decir x(0) = 0 y v(0) = 0:
$$ x(t) = C[\cos(\omega_f t) - \cos(\omega_0t)] $$

## Fuerza no Constante con friccion
$$x'' + \frac{b}{m}x' + \frac{k}{m} = \frac{F_0}{m} \cos(\omega_f t)$$
$$ A = \frac{\frac{F_0}{m}}{\sqrt{(\omega_0^2 - \omega_f^2)^2 + (2\gamma \omega_f)^2}} $$
$$ \tan \partial = \frac{2 \gamma \omega_f}{\omega_0^2 - \omega_f^2} $$
La fase $\partial$ determina la diferencia de fase entre la fuerza y el desplazamiento

$$ x(t) = B e^{- \gamma t} \cos(\omega t + \phi_0) + A \cos(\omega_f t - \partial)$$


## damped & force: steady
Eso significa que ya hemos llegado a un punto en el que solo la fuerza es la que proboca la oscilacion del puesrpo, asi que la ecuacion de movimiento pasa a ser:
$$ x(t) = \cos(\omega_f t - \partial) $$