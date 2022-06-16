La electricidad fluye por un cirtuito hasta que un equilibrio se consigue.
Pero, que oicrre si la carga se emplea constantemente y se evita llegar al equlibrio?

La corriente electrica se define como un flujo constante de electrones en una region concreta.

### Intensidad:
Cantidad de electrones que circulan en un segmento, en una unidad de tiempo, y se mide en Amperios:
$$ I = \frac{\Delta Q}{\Delta t} \ (intensidad\ media)$$
$$ I = \frac{\partial Q}{\partial t} \ (Inteisidad\ instantanea) $$

Tambiien se puede medir la corriente en funcion de la densidad (intesidad por unidad de area):
$$ \overrightarrow{J} = \frac{I}{A} = \frac{1}{A}\frac{\partial Q}{\partial t} $$
El resultado de esto es un vector de magnitud J, que se tiene que intefaf esn un segmento para comporbarlo

### Intensidad a Nivel Microscopico:
Dado n (la densidad de transporte(??)) la velocidad media del transporte de la carga $v_d$ y q, que es la carga electrica de la corriente:
$$ I = n \ q \ v_d \ A $$
$$ J = n\ q \ v_d $$
Pero hay que tener en cuenta que el flujo se puede ver afectado en funcion de el campo electrico.
La densidad del campo (J) es porporcinal a el campo electrico E

## ley de Ohm
$$ R = \frac{\Delta V}{I} $$
para esto tenemos que tenr encuenta 2 propiedades:
- Conductividad ($\sigma$): es la constante de proporcionalidad entre la intensidad y el campo electrico: $\sigma = \frac{J}{E}$ 
- Resistividad ($\rho$) la inversa de conductividad

Entonces: 
 $$ R = \frac{1}{\sigma}\frac{L}{A} = \rho \frac{L}{A} $$
## Ley de joule
sin embargo, cuando la electricidad se transmite por un objeto, se produce una aprdida de energia, ya que parte se transpfrma en calor y se pierde por el sistema
##### Perdida de energia  electrostativa:
$$ \Delta U = I\ \Delta V\ \Delta t = \frac{v^2}{R} \Delta t $$
#### Potencia perdida de energia:
Se mire en vatios watt
$$ P = \frac{V^2}{R} =  I^2 R$$


# Corriente continua en circuitos electricos
Es decir, nunca se llega al equlibrio
## Fuerza electromotiva (emf)
Es la que producen fuentes no electricas (??)
Rollo pilas, generadores
Se mire en $\varepsilon$ y si es constante es un cincuido DC en le que la intensidad de corriente es constante
Si no es constante, generlamente una sinusiode, es corriente alterna AC


## Cirucitos en Serie
- La intensidad es igual en todos los componentes
- El voltaje total es la suma de las diferencias de voltage en cada pomponente
- La resistencia total es la suma de todas las resistencias.

## Circuitos en Paralelo
- El voltaje es el mismo en todos los cirucitos
- La intensidad total de la corriente es la suma de la intensidad de cada componente
- La resistencia equilibalente es igual a la inversa de la suma de todas las reistencias invertidas

## Leyes de cirucitos de Kirchhoff
Partes:
 - Nodo: punto de separacion o nexo de branches
 - Ciclo cerrado, un camino cerrado por todas las branches
 - Branch: una serie de componentes en 2 nodos
###### Leyes#
- Ley de corriente  (o nodal): la intensidad neta que llega a un empalme es 0 (la corriente que entra es la misma que tiene que salir, pero negativo) Y las intensidades represetan el flujo de la corriente
$$ I_1 + I_2 + .. + I_n = \sum_{i=0}^n I_i = 0$$
- Regla de voltaje o regla de bucle: la suma de todos los voltajes diferenciales de todos los componentes es 0.
$$ \sum_{i=1}^n \Delta V_i = 0$$

## Circuitos RC
Por ejemplo, cuandos e inclue un condensador, no es corriente continua, ya que va decallendo
- Transiente de carga: curva que describe el tiempo de cargarse al 100% un condensador. Se da cuando una corriente externa circula por el condensador; con als condiciones iniciales de que el voltaje y la carga son 0
- Transiente de descarga: idem, pero descargandose