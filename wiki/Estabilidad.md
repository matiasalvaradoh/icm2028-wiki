# Estabilidad
Cuando en un sistema actúan fuerzas y se produce una alteración en su equilibrio, es de especial interés lo que ocurre con el sistema en si ya que 
se quiere saber si este vuelve a su estado inicial, lo cambia permanentemente o si no ocurre nada. A esto se le llama estabilidad. 

Podemos clasificar en tres tipos diferentes de equilibrio: estable (donde las fuerzas que actuan sobre el cuerpo van a tender a regresarlo a su equilibrio inicial), 
inestable (las fuerzas van a alejar del equilibrio inicial al cuerpo) y neutro (donde se alcanza un nuevo equilibrio). En la figura 1 podemos ver de manera gráfica 
que ocurre a nivel diferencial con el material cuando se aplica una fuerza que perturba el equiibrio.

## Pandeo
Cuando se aplica una fuerza que comienza a provocar desplazamientos ortogonales a la dirección de aplicación de la fuerza, ocurre un fenómeno llamado "pandeo" o 
inestabilidad. Si tomamos por ejemplo una barra esbelta apoyada, y aplicamos una fuerza de compresión en su extremo libre, vemos que a medida que aumentamos la carga la 
barra comienza a doblarse (como se ve en la figura 2); en este momento, comienza a pandearse.

Es de especial interés la carga crítica que produce este pandeo. Esta carga en barras está
 determinada por la fórmula:
 
<p align="center">
 <img src="https://render.githubusercontent.com/render/math?math=P_{c}=\frac{\pi^{2}E\Omega}{\lambda^{2}}" width="70" height="70">
</p>

Donde

_E_: módulo de elasticidad del material

<img src="https://render.githubusercontent.com/render/math?math=\Omega">: área de la sección

<img src="https://render.githubusercontent.com/render/math?math=\lambda">: esbeltez de la pieza, determinada por

<p align="center">
  <img src="https://render.githubusercontent.com/render/math?math=\lambda=\frac{l}{I_{min}}" width="70" height="70">
</p>

En que

_l_: longitud de la sección

<img src="https://render.githubusercontent.com/render/math?math=I_{min}">: radio de giro de la sección respecto del eje neutro

Otra expresión de interés es el esfuerzo crítico, dado por

<p align="center">
  <img src="https://render.githubusercontent.com/render/math?math=\sigma_{c}=\frac{P_{c}}{\Omega}" width="70" height="70">
</p>

-----------

Si graficamos la carga aplicada con el desplazamiento del objeto, vemos que mientras la carga no supere el pandeo crítico, la estructura se 
va a seguir deformando. Notamos que a medida que nos vamos acercando mas al valor crítico, el desplazamiento aumenta rápidamente.

## Pandeo como criterio de falla

Usando la fórmula de pandeo crítico, podemos determinar el lugar donde va a ocurrir la falla por pandeo al despejar P_{c} de la fórmula de tensión


<p align="center">
  <img src="https://render.githubusercontent.com/render/math?math=\sigma_{Y}=\frac{P_{c}}{A}" width="70" height="70">
</p>

<p align="center">
  <img src="https://render.githubusercontent.com/render/math?math=P_{c}=A\sigma_{Y}" width="70" height="70">
</p>

Igualando la exprosión anterior con la dicha anteriormente para pandeo crítico, y despejando L, encontramos el lugar donde se produciría la falla una vez que 
se supere el valor crítico.

### Ejemplo

Determinemos el largo crítico de una viga esbelta con un extremo empotrado u otro sobre un apoyo móvil a la que se le aplica un esfuerzo de compresión en la misma 
dirección que su eje neutro.

Resolviendo la ecuación diferencial

<img src="https://bit.ly/3euvrgj" align="center" border="0" alt=" EI\frac{\partial^4v}{\partial x^4}+P\frac{\partial^2v}{\partial x^2}=0 " width="150" height="46" />

a la que llegamos desde el equilibrio de fuerzas y momentos de la viga, obtenemos que 

![equation](https://render.githubusercontent.com/render/math?math=P_{c}=\frac{2\pi^{2}EI}{l^{2}})

Ahora, igualando con ![equation](https://render.githubusercontent.com/render/math?math=P_{c}=\sigma_{Y}A) y despejando _l_, se llega a que la falla se produce en

![equation](https://render.githubusercontent.com/render/math?math=l_{c}=\pi\sqrt{\frac{2EI}{\sigma_{Y}A}})

----

## Caso práctico

En el año 2010, Mark Cavendish (ciclista profesional que esa temporada corría por el equipo _HTC Highroad_) se encontraba cerca de ganar la etapa 4 del _Tour de Suisse_ 
con un final en sprint. Sin embargo, a pocos metros de terminar, sufrió una caída producto de una falla en su rueda delantera, lo que le costó la victoria.

Analizando el [video](https://www.youtube.com/watch?v=lNsnpmvO7YU)  de la carrera, se ve que la rueda sufre una flexión, provocando el accidente. Sin embargo, viendo mejor, se ve que la rueda solo se pandeo ya que volvió a su forma original.
La falla se atribuye a las fuerzas laterales que Cavendish puso sobre rueda delantera cuando estaba atacando, llevando al límite su equipo de competencia.


